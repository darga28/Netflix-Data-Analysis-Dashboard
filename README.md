# Netflix Movies and TV Shows Data Analysis

## Overview

This project involves the analysis of a Netflix dataset to explore trends, insights, and patterns in movies and TV shows available on the platform. The project was carried out in several stages, including data cleaning, relational database design, and data visualization.

## Project Workflow

### 1. **Data Cleaning and Preparation**
- **Tools Used**: Excel
- **Tasks Performed**:
  - Splitting text fields, trimming data, and handling missing values.
  - Applied Excel functions such as `VLOOKUP` and `IF` for data lookup and conditional operations.
  - Calculated key statistics like sum, average, and max/min values.
  - Utilized Pivot Tables for summarizing data.
- **Output**: The cleaned dataset, saved in six separate CSV files.

### 2. **Database Design**
- **Tools Used**: MySQL Workbench
- **Tasks Performed**:
  - Set up a new MySQL connection and schema named `netflix_data`.
  - Imported the cleaned CSV files (`Cast.csv`, `Countries.csv`, `Description.csv`, `Directors.csv`, `Listed In.csv`, and `netflix_titles.csv`) into MySQL.
  - Established relationships between tables by pivoting key data columns.
  - Cleaned up the database by dropping unnecessary tables, leaving a refined, relational database ready for analysis.

### 3. **Data Visualization**
- **Tools Used**: Power BI
- **Tasks Performed**:
  - Connected the MySQL database to Power BI.
  - Created a comprehensive dashboard (`Netflix Dashboard.pbix`) featuring various visualizations:

    **Page 1: Overview**
    - **Shows Added by Date**: An area chart displaying the number of movies and TV shows added to Netflix each year, with separate areas for Movies and TV Shows, showcasing growth trends over time.
    - **Shows by Rating**: A bar chart illustrating the distribution of Netflix shows by rating, with separate bars for Movies and TV Shows.
    - **Top 10 Genres**: A bar chart highlighting the top 10 most common genres on Netflix, showing the number of titles in each genre.
    - **Available Countries**: A world map visual representing the availability of Netflix content in different countries, with bubble sizes indicating the volume of content.

    **Page 2: Single Title View**
    - **Movies/TV Shows**: A dropdown menu that allows users to select a specific title.
    - **Release Year and Rating**: Displays the release year and content rating of the selected title.
    - **Description**: Provides a brief description of the selected movie or TV show.
    - **Listed In**: Shows the genres under which the selected title is categorized.
    - **Director and Cast**: Lists the director and cast members of the selected title.
    - **Available Countries**: A map visual showing where the selected title is available globally.

- **Output**: A Power BI dashboard providing actionable insights into the Netflix dataset.

## Files Included

- **rawdata.csv**: The original, unprocessed dataset.
- **Cleaned Netflix Data and Dashboard Folder**: Contains the six cleaned CSV files and the Power BI dashboard (`Netflix Dashboard.pbix`).

## Conclusion

This project provides a detailed examination of Netflix content, offering insights into genre trends, content distribution, and more. By following the outlined steps, you can replicate or extend the analysis using the provided datasets and tools.
