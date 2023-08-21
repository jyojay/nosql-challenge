# nosql-challenge
MongoDB challenge

This repository contains:
*   **NoSQL_setup_starter** jupyter notebook containing code that imports the data and sets up and updates the uk_food database.
*   **NoSQL_analysis_starter** jupyter notebook containing code that performs the exploratory analysis queries in the database.
*   A Resources folder with provided data file

# Notes:
* Jupyter Notebook used
* **Please note that for Question 2 of analysis section, establishments in London having a RatingValue greater than or equal to 4 is 33 after converting numeric RatingValue to Int. I have directly queried the database and double checked this as well. The result expected in Canvas has to be reviewed and will come up as 34 only if string to Int conversion is not done and string comparison is done to fir RatingValue $gte 4 since non-numeric value is also included in the result**.
* I have converted RatingValue to int only in NoSQL_analysis_starter

# Assumption:
*  To find BusinessTypeID corresponding to 'BusinessType': 'Restaurant/Cafe/Canteen', find_one was used assuming BusinessTypeID should be standard. Wecould have also used find and got all occurences of the same.

# References:
* https://www.mongodb.com/docs/manual/reference/method/db.collection.distinct/
