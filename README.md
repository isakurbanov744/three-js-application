# Three.js Boilerplate Application
https://github.com/isakurbanov744/three-js-application

## Project Structure
```
build - Build Directory for compressed files
src - Source Directory for project files
├── css - CSS Directory for all Styling files
├── js - Directory for THREE JS Files
│   ├── app
│   │   ├── components - Three.js components that get initialized in `main.js`
│   │   ├── helpers - Classes that provide ideas on how to set up and work with defaults
│   │   ├── managers - Manage complex tasks such as GUI or input
│   │   └── model - Classes that set up the model object
│   ├── data - Any data to be imported into app
│   └── utils - Various helpers and vendor classes
└── public - Used by webpack-dev-server to serve content. Webpack builds local dev files here. 
    └── assets - Is copied over to build folder with build command. Place external asset files here.
```

## Getting started
Install dependencies:

```
npm install
```

Developer Server:

```
npm run dev
```

Spins up a webpack dev server at localhost:8080 and keeps track of all js and sass changes to files.

## Build
```
npm run build
```

## Input Controls
* Press H to hide dat.GUI
* Arrow controls will pan
* Mouse left click will rotate/right click will pan
* Scroll wheel zooms in and out
