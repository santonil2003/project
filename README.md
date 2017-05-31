
# RESTFUL API with JSON response was developed

# PDO was used for database interactions 

#  .htaccess used for hiding PHP extension and redirect API request to index.php with URI params

# Average rating calculated using AVG MySQL function 

# Sorting menu by name and rating implemented using MySQL ORDER BY

# Ajax polling implemented on client side using SetTimeInterval javascript function. Polling interval time can be defined from /project/site/js/app.js



# Database dump, Sample XML, Sample JSON and their validation screen shots can be found in
 /project/documents

# API source path
/project/api

# Frontend web site source path
/project/site




# Actions and request method used are given below.

Request method POST used for adding new coffee review

Request method PUT used for updating existing coffee review 

Request method DELETE used for deleting a coffee review 

Request method GET used for fetching coffee and coffee details.

Refer to /project/api/index.php for URL pattern to access different services provided by API.







# Project setup guide

Extract the zip folder into the document root of WAMP, XAMMP or MAMP.

Note: make sure root project folder name is something like /project 
Else we will need to update the base path in .htaccess 

Database connection details  can be configured  from
/project/api/config.php
