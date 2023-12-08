# Python_Final_Project
 Final project for group 3 St Clair College

For this final project which involves SQLite3, Flask, and Pandas with an Airbnb dataset in New York City, the integration of these modules follows a systematic approach. 
First, the dataset source is an CSV file, which is loaded into an SQLite database using Pandas. 
Pandas simplifies data manipulation and transformation, allowing for seamless conversion of the dataset into a structured SQLite database. 
A connector file was created, making a link between the unchanging dataset and the interactive features of an SQLite database allowing storage, retrieval, and manipulation from the data.

Once the dataset is housed in the SQLite database, Flask, a modular web framework, comes into play to build the web application. 
Flask provides an environment to create routes, define views, and connect the backend with the frontend. 
Flask routes can execute queries on the SQLite database using the built-in SQLite3 module, allowing for dynamic generation of web content based on user requests. 
HTML templates are used to structure the presentation of the data, and Flask injects data into these templates, 
creating a cohesive and interactive web application. The combination of SQLite3 for database management, 
Pandas for data manipulation, and Flask for web development facilitates the creation of a user-friendly platform showcasing insights derived 
from the Airbnb dataset in New York City.
