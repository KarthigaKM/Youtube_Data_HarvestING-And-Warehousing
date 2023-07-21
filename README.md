# [PROJECT 1: Youtube_Data_Harvesting_And_Warehousing](https://github.com/KarthigaKM/Youtube_Data_HarvestING-And-Warehousing)
![](https://github.com/KarthigaKM/Youtube_Data_HarvestING-And-Warehousing/blob/main/Capture.PNG)
## Overview:
  * The "YouTube Data Analysis with Streamlit and Data Warehousing" project involves building a simple user interface (UI) with Streamlit, retrieving data from the YouTube 
    API, storing it in a MongoDB data lake, migrating it to a SQL data warehouse, querying the data warehouse with SQL, and displaying the data in the Streamlit app. The 
    project aims to provide valuable insights into YouTube channel performance and video details using interactive visualizations and SQL queries.

    
## Technologies Used:   
  * Python
  * Streamlit: For building the interactive web application.
  * MongodB : For storing extracted youtube datas ina data lake.
  * MYSQL : For Migrating stoed data into Data Warehouse.
  * Pandas : For data manipulation and preprocessing.
## Steps:
## Install and Import Necessary Libraries:
  * Ensure all required libraries, such as Streamlit, pymongo, and MySQL Connector, are installed and imported to set up the development environment.
## Develop Basic Streamlit Application:
  * Create a Streamlit web application with a user-friendly structure. Set the page configurations, title, and sidebar (menus) to enhance the app's aesthetics and 
    navigation.
## Establish API and Database Connections:
  * Establish connections to the YouTube API using an API key, connect to MongoDB using pymongo, and set up a connection with MySQL using MySQL Connector.
## Retrieve YouTube Data:
  * Create four separate functions to retrieve channel details, video IDs (using channel IDs), all video details, and comments' details for each video. Organize the 
    comments as arrays within their corresponding videos.
## Store Data in MongoDB:
  * Develop a function to store the retrieved data in MongoDB using appropriate queries.
## Channel Dropdown List:
  * Implement a function to allow users to store their input channels in a dropdown list for easy selection and analysis.
## Performance Queries:
 * Design a function to perform ten queries that assess the performance of all channels by conducting comparisons. Display the query results as dataframes when users select 
   a specific question.
## Migrate Data to MySQL:
 * Create a function to migrate the stored MongoDB data to MySQL using SQL queries.
## Display Data in Streamlit App:
  * Incorporate the code to display all the collected and analyzed data in the Streamlit app. Utilize interactive visualizations and user-friendly interfaces to present 
    insights effectively.
## Deployment:
  * The completed project can be deployed using Streamlit Sharing or any other hosting platform, allowing users to access the YouTube data analysis web application online.
## Future Enhancements:
  * Implementation of machine learning models for predictive analysis.
  * Incorporation of user authentication to allow personalized data exploration.
    
    
    
