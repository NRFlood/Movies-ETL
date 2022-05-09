# Movies-ETL

## Overview of Movie Database Analysis

This purpose of this project was to help Britta create a movie database to be used at the hackothon the her company Amazing Prime was planning to host.  In order to create this database we extracted movie information from Wikipedia and Kaggle, and then cleaned up the information so the two sets of data would be joined together.  After we had extracted the data and combined the information we were then able to load the clean dataset into a SQL database.

We also automated the database dynamic by creating an automated pipeline that takes in new data on a daily basis, performs all needed data transformations, and then loads the data into our existing tables.  This will enable new movies to be added to the dataset on a regular basis so that similar analysis could be performed at any point in time.  This will enable Amazing Prime to determine which movies make the most sense for them to offer on their service.  
