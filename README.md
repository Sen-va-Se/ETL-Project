# ETL-Project
A complete project built of ETL process with Python. For the past few month since September 1st 2022, I've tried to built an ETL pipeline for my curiosity of Data Engineering. The fact that there is tons of non-coding or user-friendly pipeline that can be used to demonstrate this task, I decided that it was better for me to learn the mindset rather than the technology application. Mistakes is inevitable, however there was so much things that I've learn from the project and things that I can improved in the future. 
The Project can be divided in 6 steps: 
1. Choosing the data to analyze(I took Dataset 'USSales' from Kaggle)
2. Setup MSSQL Server for storing data
3. Connect to MSSQL Server and Extract Data (I have lots trouble with this part since choosing the right server, connection string format confuse me a lot)
4. Transform and Split (The initial table has 20 columns, it was to analyze so I decided to split into 3 smaller and convenience tables. At this point I also learn how to follow BNCF and design ERD as Star schema)
5. Load the data to PostgreSQL
6. Import data from PostgreSQL to PowerBI and build dashboard.
