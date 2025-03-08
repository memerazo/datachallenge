# Datachallenge
In this section, we will set up an ETL (Extract, Transform, Load) pipeline using PostgreSQL and Python.   The goal is to efficiently load raw data, perform necessary data cleaning and transformations,  and store the processed data in a structured format for analysis.  
Power BI Hiring Analysis

Project Overview

This project analyzes hiring trends based on data imported from PostgreSQL. The dataset contains information about hired candidates, including technology, seniority, year, and country. The goal is to identify patterns and insights to better understand recruitment trends.

Data Source

The data was imported directly from a PostgreSQL database, specifically from the candidates database, using the clean_applicants table. The dataset was previously processed through an ETL pipeline to clean and transform the data.

Visualizations Created

Hires by Technology (Pie Chart)

Displays the distribution of hires by technology.

Helps identify which technologies have the highest number of hires.

Hires by Year (Horizontal Bar Chart)

Shows hiring trends over time.

Facilitates the analysis of yearly hiring patterns.

Hires by Seniority (Bar Chart)

Segments hires by seniority level (Intern, Mid-Level, Junior, etc.).

Helps understand the demand for different experience levels.

Hires by Country Over Years (Multi-Line Chart)

Displays hiring trends in the USA, Brazil, Colombia, and Ecuador over the years.

Allows comparison of hiring patterns between these countries.

Geographic Map

Shows the distribution of hires by country.

Highlights regions with the highest hiring activity.

Considerations & Limitations

The dataset only includes records until 2022, meaning more recent trends are not reflected.

Additional analysis could have been performed, such as correlations between technologies and seniority levels.

Duplicate records were not removed, which was an oversight. Future projects will take this into account to ensure data accuracy.

Technologies Used

Power BI: Data visualization and dashboard creation.

PostgreSQL: Database management and data storage.

Python (ETL process): Data cleaning and transformation.

Future Improvements

Extend the dataset with more recent hiring data.

Implement data deduplication before visualization.

Conduct deeper statistical analysis to extract more insights.

How to Run the Project

Ensure you have access to the PostgreSQL database.

Load the clean_applicants table from the candidates database.

Open Power BI and connect to PostgreSQL.

Load the dataset and refresh the visuals.

Explore the dashboard and analyze the insights.

Conclusion

This project provided valuable insights into hiring trends and helped develop skills in Power BI, data visualization, and database connections. Lessons learned include the importance of data cleaning and more in-depth analysis. Future iterations will aim to improve data quality and expand the analysis for better decision-making.
