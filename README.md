
# Interactive Graphics Final Project :dog: :softball:

![Screenshot](https://raw.githubusercontent.com/SapienzaInteractiveGraphicsCourse/final-project-pluto/create-react-app/documentation%20assets/screenshot.png)

LIVE LINK: https://sapienzainteractivegraphicscourse.github.io/final-project-pluto/ 

## Idea

In this project we have simulated a dog ball fetching game in a house garden. :dog:  :softball:

## Controls

In order to try the simulator, use the following controls:
* in order to take and throw the ball press **"Enter"**, **"Shift"** or **"Space"** buttons;
* It is possible to rotate the camera, as well as zoom-in/zoom-out using the mouse;
* You can use left and right arrow buttons to rotate the human and throw the ball in different directions.

## Technologies used

### Graphics
The graphic part of the project is written using [THREE.JS](https://threejs.org/) library. The animation is implemented using [TWEEN.JS](https://github.com/tweenjs/tween.js/).


### User interfaces
User interface and the shell of the project is done by [React.js](https://reactjs.org/) library.

### Developing environment

Since we decided to use React.js for building user interface of the project and for structuring it, we used the [create-react-app](https://github.com/facebook/create-react-app). It creates for us a developing server which serves all the static files (textures, models), assembles all the *.js files into a single file called "bundle" and transpile our js code written in es6/es7 into the es5 standard, so our project will also run on old browsers.



## How to continue developing

### Start developing server

In order to run the developing server of the project, you need to have [Node.ls](https://nodejs.org/).

Before starting, we need to download all the dependencies. To do that, go to the root directory of the project and run the following command:

```sh
npm install
```

Then, we can run the developing server:

```sh
npm start
```

The server have been started and if you go to the http://localhost:3000 you should see the working project.

### Build the project

When you finish developing the project and want to deploy it, run this command:

```sh
npm run build
```

This command prepares the app for production and place all the files into `build` folder.

The app is ready to be deployed.

You can learn more about the create-react-app commands [here](https://github.com/facebook/create-react-app).

## Authors

Artsiom Sauchuk

Berrak Senses

