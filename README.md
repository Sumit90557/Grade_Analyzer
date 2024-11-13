This Grade Analyzer application, built with Streamlit, allows users to upload an Excel file containing student grades and processes it to generate a summary with detailed grading statistics. The app applies custom scaling and grading logic to help visualize grade distribution and provides options to download the processed data.

Features
Upload Excel File: Upload a .xlsx file containing student grades.
Custom Grading and Scaling: Calculates total marks based on max marks and weightage for each assessment.
Grade Assignment: Automatically assigns grades to students based on specified grade distribution schema.
Summary Table: Displays a summary of grade distribution, including IAPC recommendations and verification of grade counts.
Download Processed Data: Allows users to download the processed data and summary in Excel format.
How to Use
Upload File: Use the file uploader to upload an Excel file in the required format:

The first row should contain column names.
The second row should contain the maximum marks for each assessment.
The third row should specify the weightage of each assessment towards the total grade.
Grade Calculation:

The app calculates scaled grades based on input scores, max marks, and weightage.
Grades are assigned using a predefined schema:
AA: 5%
AB: 15%
BB: 25%
BC: 30%
CC: 15%
CD: 5%
DD: 5%
View Results:

After processing, the app displays a dataframe of students’ scaled marks and assigned grades.
A summary table shows the breakdown of grades and verifies counts against IAPC recommendations.
Download Processed Data: Download the processed data and summary table in Excel format.
