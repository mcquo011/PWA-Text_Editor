# Progressive Web Application: Text Editor
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

 ## Table of Contents 📑

  * [Description](#description)
  * [Dependencies](#dependencies)
  * [Usage](#usage)
  * [Built With](#built-with)
  * [Screenshots](#screenshots)
  * [Contributers](#contributers)
  * [License](#license)
  * [Questions](#questions)

## Description 

This is a text editor program that runs in a web browser and meets the requirements for being a Progressive Web App (PWA). As a PWA, the program is capable of functioning offline and includes multiple data persistence strategies as a fallback in case the browser doesn't support a particular strategy.

## Dependencies  

* babel-loader: 8.2.2
* css-loader: 6.2.0
* html-webpack-plugin: 5.3.2
* http-server: 0.11.1
* mini-css-extract-plugin: 2.7.5
* style-loader: 3.2.1
* webpack: 5.51.1
* webpack-cli: 4.8.0
* webpack-dev-server: 4.0.0
* webpack-pwa-manifest: 4.3.0
* workbox-webpack-plugin: 6.2.4
* code-mirror-themes: 1.0.0
* idb: 6.1.2
You can find more information about each dependency in the project's package.json file.

 ## Usage 

  1. Create your own repository using the starter code by cloning the starter code repository. 
  2. In order to launch the backend and serve the client, run npm run start from the root directory.
  3. IndexedDB will immediately construct a database store when the text editor is opened.
  4. When you enter content and then close the DOM window, the content is saved with IndexedDB.
  The content will be retrieved from IndexedDB when the text editor is reopened after being closed.
  5. To download the online application as a desktop icon, click the Install button.
  6. When the web application is loaded, a registered service worker utilizing Workbox will be present.
  Pre-caching of static assets will be used.

  ## Built with

* idb - a lightweight wrapper around the IndexedDB API used for storing and retrieving data
* Webpack - used for bundling JavaScript files and generating an HTML file, service worker, and manifest file
* Workbox - used for registering a service worker and pre-caching static assets upon loading

  ## Screenshots

![Alt Text](./client/src/images/Screen%20Shot%202023-04-30%20at%205.44.39%20PM.png?raw=true)

  ## Contributers 

  Starter code from UMN Full-Stack Flex Web Development Bootcamp

  ## License 
  
  Copyright (c)
  [MIT](https://opensource.org/licenses/MIT)

  ## Questions 

  You can visit my Github Profile here: [mcquo011](https://github.com/mcquo011/) 
  If you have any questions please email me at omcquown@gmail.com
  