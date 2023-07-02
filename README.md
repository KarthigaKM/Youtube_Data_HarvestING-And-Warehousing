# Youtube_Data_HarvestING-And-Warehousing
Overview:Building a simple UI with Streamlit, retrieving data from the YouTube API, storing it in a MongoDB data lake, migrating it to a SQL data warehouse, querying the data warehouse with SQL, and displaying the data in the Streamlit app.
steps:
    1. Install and Import all neccessary libraries.
    2. Develop basic streamlit with a required structure and set page cofigurations, title , sidebar(Menus) ,etc..
    3. Make connections with  youtube api using api  key , with mongodb using pymongo and with mysql using Mysql connection.
    4. Create  4 seperate  functions to retrieve channel Details, video ids(using channel_id), all video details, comments's Details of each videos.
    5. Here I've created a seperate  function to keep comments of all videos inside their corresponding videos as a "comments" array.
    6. Then created a function to store retrieved datas in mongodb by mongodb quries
    7. After that, created a function to store all the user inputs's channel in a Dropdown list.
    8. Function for 10 queries which was asked by guvi team to display  a answer as a dataframe when user selectede the qestion.
    9. Then created a function to migrate stored mongodb datas to Mysql by  mysql querying.
    10. Then added code to display everything in a  streamlit app.
    
    
    
    
