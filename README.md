# ETL-Project
A complete project built of ETL process with Python. For the past few months since September 1st, 2022, I've tried to build an ETL pipeline of my curiosity about Data Engineering. The fact that there are tons of non-coding or user-friendly pipelines that can be used to demonstrate this task, I decided that it was better for me to learn the mindset rather than the technology application. Mistakes are inevitable, however, there were so many things that I've learned from the project and things that I can improve in the future. 
The Project can be divided into 6 steps: 
1. Choosing the data to analyze(I took Dataset 'USSales' from Kaggle)
2. Setup MSSQL Server for storing data
3. Connect to MSSQL Server and Extract Data (I have lots of trouble with this part since choosing the right server, the connection string format confuse me a lot)
4. Transform and Split (The initial table has 20 columns, it was to analyze so I decided to split it into 3 smaller and more convenient tables. At this point I also learn how to follow BNCF and design ERD as Star schema)
5. Load the data to PostgreSQL
6. Import data from PostgreSQL to PowerBI and build a dashboard.

