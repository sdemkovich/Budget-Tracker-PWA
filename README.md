# Budget-Tracker-PWA (https://sd-budget-tracker-pwa.herokuapp.com/)

## Description
Budget Tracker is a progressive web application that allows the user to track their finances, 
with or without internet connection. My task with this project was to add functionality to a 
pre-built application to allow for offline access and functionality. This application achieves offline functionality by utilizing 
Service Workers and the Cache API to store static files and API responses in the users local cache. 
When the user is offline they have access to this data and these cached files. While offline, they may 
add an expense or deposit, which is stored in their local IndexedDB database. When internet connection is detected, 
those transactions are posted from their IndexedDB database to their MongoDB database. Their total budget is then updated, 
and their IndexedDB pending object store is cleared.

## Table of Contents
* [Technologies](#technologies)
* [Usage](#usage)
* [Finished Product](#finished-product)
* [Questions](#questions)

## Technologies
* HTML
* CSS
* JavaScript
* Node.js
* Express.js
* MongoDB
* Mongoose
* IndexedDB
* Web manifest
* Service Workers
* Cache API

## Usage
* Navigate to the [deployed Heroku App](https://sd-budget-tracker-pwa.herokuapp.com/).
* Enter a transaction name and amount. Choose to add or subtract funds.
* The table shows previously entered transactions.
* View a chart to tracks the total budget over the time.
* Beeing offline you will continue to view the application and add transactions.
* When internet is up and running again, the total budget will be updated with those transactions.
* To test offline capabilities either:
    * Turn your wifi off or 
    * Open your browsers' Dev Tools --> Application --> Service Workers --> Check the "Offline" box.

## Finished Product
View deployed Heroku app [here](https://sd-budget-tracker-pwa.herokuapp.com/). <br>

![](

## Questions
​If you have any questions about the repo, please contact me:

On GitHub: [sdemkovich](https://github.com/sdemkovich)
