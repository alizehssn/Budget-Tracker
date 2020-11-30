# PWA Budget Tracker Application
***

## Project Description
***
The Budget Tracker is a progressive web application(PWA) which allows the user to track their expenses. The user can record a title or category for each expense as well as the amount which can be added or subtracted from their budget totals. The application will display these expenses graphically over time.


## Table of Contents
***
* Title
* Description
* Installation
* Usage
* Tests
* Technologies Used
* Author
* License

## Installation
***
Users may clone this [Github repository](https://github.com/alizehssn/Budget-Tracker) into their local drive and run start in their terminal command line,
 or use the [Budget Tracker application](https://warm-anchorage-06719.herokuapp.com/)

 ## Usage
 ***

 ![Budget-Tracker Image](/budgettracker.png)
 This application takes users to a dashboard in which the user can enter the name, amount, and whether to add or subtract funds from each transaction. The application then displays the entered information graphically. The application utilizes webpack package as a node module builder in order to consolidate a large number of files into one bundle to run the application. The webpack for this application contained the icon image information with the manifest file, the webpack and manifest communicate to the browser how to respond to the application. In order to allow the application to have offline functionality a IndexDB was created to store the offline transactions and then put in the MongoDB when the application returns online.
 

 ## Tests
 ***
 The application was tested with various console.logs to track errors throughout the application's code.

 ## Technologies Used
 ***

 * HTML         
 * CSS
 * Bootstrap 4
 * Javascript
 * Node.JS
 * Express.JS
 * Mongo.DB
 * Webpack
 * IndexedDB

 ## Author
 ***
This application was created by Alize Hassan. 
Contact: 
[alizehssn@gmail.com](alizehassan@gmail.com)
[LinkedIn](https://www.linkedin.com/in/alize-hassan/)

## License
MIT License

Copyright (c) 2020 Alize Hassan

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.




