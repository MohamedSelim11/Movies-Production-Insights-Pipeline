**Abstract**

The Movies Production Insights Pipeline Project aimed to design and implement an efficient data pipeline for the movie industry. The primary objectives included:

- Data Integration: Consolidate diverse data sources related to persons, movies, genres, production, and more into a centralized data warehouse.

- Automation: Utilize Apache Airflow for automated orchestration of data pipelines, ensuring timely and accurate data processing.

- Transformation: Employ Pyspark for effective data extraction and transformation, enabling the conversion of raw data into a structured format suitable for analysis.

- Staging Area: Implement MongoDB as a NoSQL staging area for interim data storage, providing flexibility and scalability.

- ETL Process: Utilize Talend for Extract, Transform, Load (ETL) processes, facilitating the seamless transfer of data from the staging area to the PostgreSQL data warehouse.

- Change Data Capture (CDC): Implement a CDC strategy using the Meta_Data table to capture and track changes and use logic to archive all old files and receive only the latest files, ensuring the data warehouse reflects the latest information.

- Visualization: Integrate Power BI for insightful visualization, allowing users to explore trends, patterns, and relationships within the movie industry.
This documentation provides a high-level overview of the project's objectives, methodologies, and implementation strategies.

**Meet OurTeam**

* Omar Mahmoud
* Osama Tarek
* Abdullah Mahmoud
* Ataa Mohamed
* Mohamed Selem
* Youssef Ashraf
  
    ![team](https://github.com/3amory99/Movies-Production-Insights-Pipeline/blob/master/03_Screenshots/Team.png)

**Project Overview**

The Movies Production Insights Pipeline – a revolutionary project poised to transform the way we navigate the dynamic realm of filmmaking. Leveraging data sourced from the Movie Production Database

* Descriptive Analysis on Movies Dataset using BI-Dashboard.
* Our mission: to empower and provide your business team with a streamlined solution and data pipeline.
* Our pipeline: encapsulates production details, movie insights, personnel data, crew information, and critical performance measures. This succinct integration allows for swift and informed decision-making in an industry where timing and precision are paramount.

**Data Sources**

* JSON Files
  * [JSON Files Dataset](https://github.com/3amory99/Movies-Production-Insights-Pipeline/tree/master/Reference_data/Archive)
  * Country (88)
  * Department (12)
* XML Files
  * [XML Files Dataset](https://github.com/3amory99/Movies-Production-Insights-Pipeline/tree/master/Reference_data/Archive)
  * Gender (3)
  * Genere (20)
* CSV Files
  * [CSV Files Dataset](https://github.com/3amory99/Movies-Production-Insights-Pipeline/tree/master/Reference_data/Archive)
  * Language (88)
  * Language Role (2)
* Relational Database
  * Postgres
  * movie (4803)
  * movie_genre (12160)
  * movie_cast (106257)
  * movie_company (13677)
  * movie_crew (129581)
  * movie_languages (11740)
  * person (104842)
  * production_company (5047)
  * production_country (250)
  [Relationa_Database_Schema](https://github.com/3amory99/Movies-Production-Insights-Pipeline/blob/master/03_Screenshots/01.png)
 
  
