# Building Footprints: AWS Redshift & Tableau Pipeline

This project focuses on processing and analyzing building footprint data using AWS services, SQL, Python, and Tableau.
The goal is to clean raw data, load it into Amazon Redshift, and visualize insights using Tableau.

## Technologies Used
- AWS (Redshift, S3, IAM, EC2)
- SQL for database management and queries
- Python for data cleaning and transformation
- Tableau for data visualization

## Project Workflow
The raw dataset was first cleaned using Python to remove inconsistencies and ensure data accuracy.
The cleaned dataset was then uploaded to an S3 bucket and loaded into Amazon Redshift using SQL.
Several analytical queries were performed to extract insights from the data. Finally, Tableau was connected to Redshift to create interactive visualizations.

## Key Steps
- Created an S3 bucket to store cleaned data.
- Set up and configured Amazon Redshift for data storage.
- Loaded data from S3 to Redshift using SQL.
- Executed SQL queries to analyze building footprint attributes.
- Connected Tableau to Redshift to generate visual reports.

## Results & Insights
The project helped in identifying patterns in urban development, analyzing variations in building footprints, and visualizing key attributes like
structure height and footprint type. The Tableau dashboards provide an interactive way to explore these insights.

## How to Use
1. Clean the dataset using the provided Python script.
2. Upload the cleaned dataset to S3.
3. Load data into Redshift using the provided SQL scripts.
4. Run queries for analysis.
5. Connect Redshift to Tableau and explore the visualizations.
