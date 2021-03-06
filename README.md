# E-Commerce-Backend
This project is the creation of the back end for an e-commerce site.

## Table Of Contents
* [Description](#description)
* [Technologies](#technologies)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Questions](#questions)

## Description
This application displays creation of database using mySQL with models and associations. Then demonstrates the API Routes to perform RESTful CRUD operations displayed in my walk through videos.



Demonstration Videos
View video to see MySQL walk through via [Screencastify](https://drive.google.com/file/d/1qmqSBz07Z8U_U3szOPPNbYFQokn5CRvp/view)<br>

View video to see Insomnia walk through via [Screencastify](https://drive.google.com/file/d/1f_zyPexR1tb70oALmkEXjwstSrZ3lApS/view)<br>



## Technologies
Project is created with 
* [Javascript](https://www.javascript.com/)
* [Node.js](https://nodejs.org/en/)
* [Sequelize](https://www.npmjs.com/package/sequelize)
* [MySQL2](https://www.npmjs.com/package/mysql2)
* [Express](https://www.npmjs.com/package/express)
* [Dotenv](https://www.npmjs.com/package/dotenv)

## Installation
To get started clone this repository using 
<br>
```terminal
git clone git@github.com:keltonlea/retail-backend.git
```
Both Node.js and MySQL must be installed on your computer.

Install dependencies 
```terminal
npm init --y
``` 
```terminal
npm install express sequelize mysql2
```
Open up MySQL shell and input 
```terminal
source db/schema.sql
```
and 
```terminal
use ecommerce_db
```
Then quit MySQL shell and input the following in your terminal
```terminal
npm run seed
```
to start running application simply input 
```terminal
node server.js
```
Open up Insomnia core to GET, POST, PUT and DELETE from different routes.

## Usage
The application is used to GET data for each route(categories, products, or tags) as well as create, update, and delete data in those routes.
