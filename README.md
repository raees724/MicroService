# MERN Microservices

A comprehensive guide to building microservices architecture using the MERN stack.

## Getting Started

To set up the project, run the following commands:

```bash
npm install
npm install --only=dev
npm run start:dev

```
## Project structure


[mern-microservice]
	|- [node_modules]
	|- [config]
	|	|- config.js
	|	|- config.json
	|- [build]
	|	|- React build files
	|- [database]
	|	|- [models]
	|	|	|- Database models
	|	|- {db-init}.js
	|- [handlers]
	|	|- [controllers]
	|	|	|- Route controller files
	|	|- [middlewares]
	|	|	|- middleware files
	|- [public]
	|	|- React dependencies
	|- [src]
	|	|- React jsx files
	|- [services]
	|	|- [micros]
	|	|	|- service files
	|	|- {service-init}.js
	|- {app/server}.js
	|- package.json
	|- package-lock.json

```

  

##  Available Scripts

### Arguments
| Argument | Usage| Default Value|Description|
|--|--|--|--|
| `--env`| `--env=<ENV>` |`development` | Set the `NODE_ENV` value in `process.env.NODE_ENV`. Values: `development`, `production`, `test`
|`--service`| `--service=<SERVICES>` |`all`|Select the services to be used. `<SERVICES>` can contain a single service or a list of services. Ex: `--service="service1, service2"`.



In the project directory, you can run:

###  `npm start`

Starts the app in `production` mode with argument `--service=all`.  
  

###  `npm run start:dev`
Starts the React APP and NodeJS app in `development` mode with argument `--service=all`.

Open [http://localhost:3000](http://localhost:3000) to view the React App in browser and [http://localhost:5000](http://localhost:5000) to access the API.

  

###  `npm run start:api`

Only starts NodeJS app in `development` mode with argument `--service=all`.

Open [http://localhost:5000](http://localhost:5000) to access the API.  

###  `npm run start:react`

  
Runs the app in the development mode.<br>

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

  

The page will reload if you make edits.<br>

You will also see any lint errors in the console.

  

###  `npm run test:react`

  

Launches the test runner in the interactive watch mode.<br>

See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

  

###  `npm run build:react`

  

Builds the app for production to the `build` folder.<br>

It correctly bundles React in production mode and optimizes the build for the best performance.

  

The build is minified and the filenames include the hashes.<br>

Your app is ready to be deployed!

  

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

  

###  `npm run eject:react`

  

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

  

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

  

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

  

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

  

##  Learn More

  

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

  

To learn React, check out the [React documentation](https://reactjs.org/).

  

###  Code Splitting

  

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

  

###  Analyzing the Bundle Size

  

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

  

###  Making a Progressive Web App

  

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

  

###  Advanced Configuration

  

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

  

###  Deployment

  

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

  

###  `npm run build` fails to minify

  

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
