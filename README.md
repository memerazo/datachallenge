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

### Running the Project

#### Cloning the Repository  
To start, clone the repository by running the following command:

```bash
git clone https://github.com/memerazo/datachallenge
```

#### Creating a Virtual Environment  
Create a virtual environment using the following command:

```bash
python -m venv datachallenge
```

To activate it, navigate to the `venv/Scripts` folder and run:

```bash
activate
```

#### Setting Up Credentials  
To connect to the database, you need a JSON file named `credentials.json` inside the project folder. The file should have the following structure:

```json
{
    "db_host": "DB_HOST",
    "db_name": "DB_NAME",
    "db_user": "DB_USER",
    "db_password": "DB_PASSWORD",
    "db_port": "DB_PORT"    
}
```

#### Installing Dependencies  
The required dependencies are listed in the `requirements.txt` file. Install them using:

```bash
pip install -r requirements.txt
```

#### Running the Notebooks  
Follow this order to execute the notebooks:

1. `code/dataload.ipynb`
2. `code/datachallenge.ipynb`

#### Connecting the Database with Power BI  
1. Open Power BI Desktop and create a new file.  
2. Select "Get Data" and choose "PostgreSQL Database".  
3. Enter the PostgreSQL server and database name, then click "Accept".  
4. Fill in the credentials and confirm.  
5. Once connected, select the table with the cleaned data to start building the dashboard.

### Project Insights  
This project provided valuable insights into hiring trends and helped develop skills in Power BI, data visualization, and database connections. Key lessons included the importance of data cleaning and the need for deeper analysis. Future iterations will focus on improving data quality and expanding the analysis for better decision-making.

