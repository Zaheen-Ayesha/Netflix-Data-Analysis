# Netflix Movies & TV Shows Analysis Using SQL and Power BI

### Objective:
The objective of this project was to analyze Netflix's content library to uncover insights into movies and TV shows, including trends in genres, ratings, and geographical distribution. The project involved data cleaning, solving 20 business problems using SQL, and creating an interactive Power BI dashboard to visualize key metrics.

### Steps Taken:

### 1. Data Cleaning:

- Obtained the dataset from Kaggle and imported it into SQL Server.
  
- Removed duplicates and handled missing values in the dataset.

- Standardized data formats, particularly for the date_added column.

- Created separate tables for directors, countries, genres, and cast members to normalize the data.

### 2. SQL Analysis:

- Conducted exploratory data analysis (EDA) by solving 20 business problems, including:

  - Counting the number of movies vs. TV shows.

  - Identifying the most common ratings for movies and TV shows.

  - Listing movies released in specific years.

  - Finding the top 5 countries with the most content.

  - Identifying the longest movie and TV shows with more than 5 seasons.

  - Analyzing content by genre, director, and actor.

### 3. Power BI Dashboard Development:

- Imported cleaned data from SQL Server into Power BI

- Established a many-to-one relationship between the fact table and dimension tables based on show_id

- Calculated key performance indicators (KPIs) such as Total Contents, Total Movies, Total TV Shows, Most Common Rating, and Total Genres.

- Created an visualizations with dynamic filters including bar charts, maps, and pie charts to demonstrate:
  
  - Top 5 Countries Producing Content
  - Top 10 Genres by Content Volume
  - Top 10 Content Ratings
  - Movies & TV Show Trends Over the Years
  - Global Content Distribution via Heat Maps

### 4. Results & Key Insights:
#### - Netflix’s catalog contains 8,807 titles,
with a majority being movies (~69%).
- TV-MA (Mature Audience) is the most common rating, indicating a focus on adult-oriented content.
- Top 3 genres: International Movies, Dramas, and Comedies.
- The U.S., India, and Canada lead in content production.
- Significant content growth was observed in the last decade, especially after 2015.

#### 5. Executive Summary:
This project showcases my ability to clean and analyze complex datasets, derive actionable insights using SQL, and present findings through an interactive Power BI dashboard. By addressing 20 business problems, I demonstrated a comprehensive understanding of data analysis techniques and visualization best practices. The final dashboard provides a clear and engaging overview of Netflix's content library, highlighting key trends and metrics that can inform strategic decisions.
