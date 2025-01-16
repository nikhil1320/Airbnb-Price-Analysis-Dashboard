B41_DA_014_Stat_Seekers
Dynamic Dashboard Project

Objective

The objective of this project is to process a dataset, load it into an SQL database, and create a dynamic Power BI dashboard that reflects real-time updates from the database. This ensures actionable insights that adapt dynamically to changes in the underlying data.

Project Workflow

Initial Setup: Install required tools (Python, SQL, Power BI).

Data Preprocessing: The multiple raw CSV files are combined into a single file for analysis. The python code for the same is provided in the combine_europe_data.ipynb file.

Data Cleaning: Process and clean the dataset in Python. Exploratory data analysis is done to handle the missing values, duplicates and possible outliers. The python code for that is provided in the EDA_europe_data.ipynb And the cleaned csv file is provided as cleaned_europe_data.

Database Creation: Define and populate the SQL database. We have created a separate airbnb database and make a connection between python and MySql database. The code for the same is provided in the EDA_europe_data.ipynb. After that we have created a connection between MySql database and PowerBI in order have dynamic dashboard where any change in the database is automatically reflected on the PowerBI.

Dashboard Design: Create a Power BI dashboard connected to the SQL database. We created our own theme and produced all the determinants that are influencing the airbnb price in different cities in Europe as chart to visualize the data. We have made the dashboard interactive by providing the slicers.

Validation: Test real-time updates and dashboard accuracy. We tested the dynamic aspect of the dashboard by making changes in the sql database it automatically reflected on the PowerBI dashboard. The file for the dashboard is Airbnb Price Analysis Dashboard.pbix .

Video Presentation : https://www.youtube.com/watch?v=wyHjZdGvgZc
