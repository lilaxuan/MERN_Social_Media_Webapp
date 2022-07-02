# MERN_Social_Media_Webapp

reference: 
youtube link: https://www.youtube.com/watch?v=VsUzmlZfYNg
github link: https://github.com/adrianhajdin/project_mern_memories

Notes For the project: 
### This is the part1 and part2 of this project. 


### Prerequiste:
### install the node.js either using nvm or download from the internet
https://github.com/nodejs/node/issues/38367
https://michael.codes/posts/nodejs_apple_silicon/

### Tech stack for this project
MERN Stack
M: MangoDB
E: Express
R: React
N: Node.js runtime environment, allows you to write code in js. node can be installed either using npm/nvm or download it using the ui from the internet

Heroku: deploy the web on Heroku

### How the re-use the app:
1. create a `client` and `sevrer` folder 
2. create a react app in the client folder using `npx create-react-app ./` 
3. create a package.json file in the server folder using `npm init -y`
4. Copy the src folder of the client and server folder from https://github.com/adrianhajdin/project_mern_memories
5. Create your own ddb instance on https://www.mongodb.com/atlas/database
6. replace the connect code in the index.js under server folder based on the DDB you created (refer to section)
7. Run `npm install` under client and server folder
8. Run `npm start` under the server folder, and then run the `npm start` under the client folder. If the server and the client are under the same folder, then only need to run `npm start` once.  



### How the run the app:
under client and server folder, run `npm install` to install all the dependencies
sudo npm install -g nodemon // install the nodemon for the node.js server to run
under the server folder, run `npm start` to start the server and connect to the ddb
under the client folder, run `npm start` to start the front end ui. // in order to successfully run the app, i added the `.env` file


### Process of developing the web app: 
npm init -y // add a new package.json file
add all the depdencies in the package.json file, run `npm install`, which will install all the required dependencies.

## 1. Create a new MangoDB:
https://www.mongodb.com/atlas/database

https://cloud.mongodb.com/v2/62c078397acd3a504e4819aa#clusters (I used google account to log in)
 1. create a new database, the following options will be promoted out. 
 2. create a user: lilaxuan123 1234567890
 3. add my current ip address to the whitelist
 4. click `connect` -> connect to your applictaion, and then the ddb will show the starter code to connect to the db, 
 5. connect to MangoDB in the server -> put the starter code in the index.js file under the server folder


`




other unused code:
1. package.json for the client
<!-- // {
//   "name": "client",
//   "version": "0.1.0",
//   "private": true,
//   "dependencies": {
//     "@testing-library/jest-dom": "^5.14.1",
//     "@testing-library/react": "^13.0.0",
//     "@testing-library/user-event": "^13.2.1",
//     "react": "^18.2.0",
//     "react-dom": "^18.2.0",
//     "react-scripts": "5.0.1",
//     "web-vitals": "^2.1.0"
//   },
//   "scripts": {
//     "start": "react-scripts start",
//     "build": "react-scripts build",
//     "test": "react-scripts test",
//     "eject": "react-scripts eject"
//   },
//   "eslintConfig": {
//     "extends": [
//       "react-app",
//       "react-app/jest"
//     ]
//   },
//   "browserslist": {
//     "production": [
//       ">0.2%",
//       "not dead",
//       "not op_mini all"
//     ],
//     "development": [
//       "last 1 chrome version",
//       "last 1 firefox version",
//       "last 1 safari version"
//     ]
//   }
// } -->