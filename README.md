# nosql-challenge: UK Food

![GettyImages-1450329221_0](https://github.com/IsmaelG8/nosql-challenge/assets/128990362/2862661e-b15d-46ae-8404-d4b7b47fed61)

Project Overview:

In this project, I leveraged MongoDB, a leading NoSQL database, to import and analyze data from the UK Food Standards Agency. Using PyMongo for database operations and Jupyter Notebook for an interactive analysis environment, I performed comprehensive data manipulations and exploratory analysis to uncover insights into food establishment hygiene ratings across the UK.

Objective:

The goal was to create a MongoDB database to house the UK food establishments data, perform updates and data type corrections on the collection, and conduct exploratory analysis to understand hygiene standards and ratings across various establishments, particularly focusing on aspects like hygiene scores, rating values, and geographical analysis.

Technical Execution:

Database and Collection Creation:

Imported establishments.json into MongoDB, creating a uk_food database and establishments collection using mongoimport.
Established a connection to MongoDB in Jupyter Notebook, verified the database and collection creation, and assigned the establishments collection to a variable for easy manipulation.
Update Documents and Field Datatypes:

Added a new document for "Penang Flavours", a recent restaurant opening.
Updated document fields to ensure accurate BusinessTypeID association and removed establishments in "Dover" to align with project focus.
Converted field datatypes where necessary, such as changing latitude and longitude to decimals and RatingValue to integers, ensuring data integrity and consistency.
Exploratory Analysis:

Conducted queries to extract specific subsets of the data for analysis, including:
Establishments with a hygiene score of 20.
London establishments with a RatingValue of 4 or higher.
Top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score and proximity to "Penang Flavours".
Analysis of hygiene score distribution across different local authority areas.
Each analysis step was complemented by converting the results to a Pandas DataFrame, providing a clear, tabular view of the data, and facilitating the output of CSV files for each query result.
Outcomes:

This project not only demonstrated my proficiency in using MongoDB for real-world data analysis but also highlighted my ability to apply data manipulation and exploratory analysis techniques to derive meaningful insights. Key outcomes included:

Identification of hygiene and rating standards across UK food establishments.
Geographical analysis of food establishments in relation to hygiene standards.
Enhanced understanding of data management and analysis in a NoSQL database environment.
Skills and Tools Used:

MongoDB: For database creation and management.
PyMongo: For interacting with MongoDB from Python.
Jupyter Notebook: For executing Python code and conducting data analysis.
Pandas: For data manipulation and conversion to DataFrame for analysis.
Conclusion:

The NoSQL challenge project underscores my capabilities in database management, data analysis, and insight generation using MongoDB and Python. It reflects my adaptability to different data storage models and my ability to leverage NoSQL databases for complex data analysis tasks, showcasing my technical skills in a practical, real-world data scenario.
