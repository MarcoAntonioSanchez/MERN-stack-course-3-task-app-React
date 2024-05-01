# MERN-stack-course-3-task-app-React

## 11. Start React project
With command "npx create-react-app frontend"

The last part of the command (frontend) is the folder where the React app is beign created.

## 12. Cleanup React default's
Into the frontend folder where the React app it's contained, you can delete the following file, as none of them are going to be needed:

- src/App.css
- src/App.test.js
- src/logo.svg
- src/reportWebVitals.js
- src/SetupTests.js

To run the frontend just like the backend, you need a package.json script, for example: "react": "npm start --prefix frontend"

So the execution command will be: "npm run react".

Next you need to install a couple of npm packages but first your are going to move to the frontend folder with command: "cd frontend" to install the packages for the frontend React app only.

Axios npm package install, with command: "npm i axios".
React-icons npm package install, with command: "npm i react-icons".
React-tostify npm package install, with command: "npm i react-toastify".
Node-sass npm package install, with command: "npm i node-sass".
Concurrently npm package install, with command: "npm i concurrently -D" (as a development dependency).

Or you can do all of them at once, with command: "npm i axios react-icons react toastify node-sass" (excluding concurrently).

React-icons package has already a every dscriptive name by it self, it's for icons implementation with ES6 imports / syntax.
https://www.npmjs.com/package/react-icons

React-toastify will help with pre built alert messages in the frontend.
https://www.npmjs.com/package/react-toastify

Axios has some usefull features, like:
- XMLHttpRequests from the browser.
- http requests from node.js.
- Supports the Promise API.
https://www.npmjs.com/package/axios

Node-sass provides a binding with LibSass the C version of the popular stylesheet reprocessor and this will be helpfull to compile .scss files to .css.

Note: The node-sass is deprecated, new releases were moved to Dart Sass.
https://www.npmjs.com/package/node-sass

Concurrently will help you to run both, the dev (backend) app of the project and the react (frontend) app of the project, at once.

Script set it on the package.json: "concurrently \"npm run dev\" \"npm run react\""

Note the back-slash scaping chars, the above script is set to run with: "npm run both".

