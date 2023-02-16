## Goals
* Explain React's default folder structure
* Outline the benefits of React's folder structure
* Customize React's folder structure
* Explain the benefits of planning folder use

## Folder Structure in React
* robots.txt is used for search engine optimization
* manifest.json is used to provide some metadata to a device when your react powered web app is installed on it.
* index.js and app.js are used to render the root components of the app
* setupTests.js and reportWebVitals.js are files related to the app's performance and testing
* index.js, this file imports everything that this react app needs to render a working react app
* package-lock.json file holds the list of all dependencies with their specific versions
* package.json file helps npm rebuild the app on another machine or if we delete the node modules folder with all the files that our project needs to run, the package-lock.json file has all the information for npm to be able to rebuild those files reliably.