# MONGODB

# Description
 This readme file contains the project about crud operation using mongodb database
 
# Prerequisites
 The software required to run the project are the following,
 1.Mongodb(https://www.mongodb.com/try/download/community)
 2.visual Studio Code(https://code.visualstudio.com/download)
 3.Node.js(https://nodejs.org/)
    Kindly make that the above mentioned software are installed in your PC
# frontend specification
   The frontend used for this project is hbs(Handlebars).Handlebars is a simple templating language. It uses a template and an input object to generate HTML or other text formats. Handlebars templates look like regular text with embedded Handlebars expressions and also javascript(	JavaScript is the Programming Language for the Web.
JavaScript can update and change both HTML and CSS.JavaScript can calculate, manipulate and validate data.)
   
# backend specification
   The backend used for this project is node.js(Node.js is a cross-platform, open-source server environment that can run on Windows, Linux, Unix, macOS, and more. Node.js is a back-end JavaScript runtime environment, runs on the V8 JavaScript Engine, and executes JavaScript code outside a web browser.) and utilizes mongodb-atlas(MongoDB Atlas is a fully-managed cloud database that handles all the complexity of deploying, managing, and healing your deployments on the cloud service provider of your choice (AWS , Azure, and GCP). MongoDB Atlas is the best way to deploy, run, and scale MongoDB in the cloud.) and it can be accessed through compass(MongoDB Compass is a powerful GUI for querying, aggregating, and analyzing your MongoDB data in a visual environment. Compass is free to use and source available, and can be run on macOS, Windows, and Linux.)
   
# CRUD operation
   
                 create:User can enter their data.
                 
                 Read:entered data can be read.
                 
                 Update:if user wants to made correction it can be done.
                 
                 Delete:data can be easily deleted.
                 
# How to run this?
   open the code in Visual studio code. 
    To connect the backend we have used mongodb atlas and accessed through mongodb compass,create the new connection in the mongodb and copy the connection link paste it in the database.js to get the data in the database.
    Here i create the application for hospital management, if the patient visits the hospital the details of the patient can be collected and the data is stored in the database and can be view whenever needed.
    Here i included the fields like patient name,patient id,patient gender,patient location and patient number.
    If the details are entered in the form it is stored in the database and it perform CRUD operation.
    once we connected to the backend we can run the code using the following command:
                                         
                                         nodemon app.js
                                         
   After run this command the application will be running in http://localhost:8000/                                   
    
    
