# mousekyc-fe
This is the front end interface component of the system build with react.js. It handles the user input and webcam api to accept face images for the KYC process.
[Click here to see the project description.](https://github.com/norestlabs/mousekyc)

![Interface screenshot](https://github.com/norestlabs/mousekyc-fe/mousekyc-screenshot.png)

## Installation Instructions
***Prerequisites:*** Prior to running this repo, please ensure you have completed the back end installation and have it running. For details see [mousekyc-be](https://github.com/norestlabs/mousekyc/mousekyc-be)

1. Clone the repo and install dependencies:

```
git clone https://github.com/norestlabs/mousekyc-fe.git
npm install
```

2. Run the web interface on localhost. (This may ask you to change the port number)

```
npm start
```


## Configuration
### How to config .env file

```
    REACT_APP_NODE_PTH=src/
    NODE_PATH=src/
```

### API Endpoint
you can change api endpoint in services/constants.js
```
    export const apiEndpoint = 'YOUR API ENDPOINT';
```

## Project Structure
Core includes redux structure(redux store, redux saga)

### src
*   assets
    * img
    * styles
*   components
    * DocumentSelect
    * DropdownSelect
    * List
    * PrivateRoute
    * UploadDocument
*   containers
    * MatchContainer
    * RoutesContainer
    * SigninContainer
    * TakePhotoContainer
    * UploadDocContainer
    * UploadSelfieContainer
    * ValidationContainer
*   core
    * modules
    * store
    * index.js
*   services
    * common.js
    * constant.js
    * index.js
    * localStorage.js
    * restService.js
*   utilities
    * index.js
    * promisify.js
*   App.test.js
*   config.js
*   index.js
*   registerServiceWorker.js
