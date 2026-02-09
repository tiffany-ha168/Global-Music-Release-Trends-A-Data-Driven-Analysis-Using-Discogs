# Global Music Releases Data Analytics Project

## Overview
This project explores global music release patterns using data collected from the Discogs public API. The analysis focuses on understanding how genres, styles, formats, record labels, and countries interact within music production and distribution. By transforming raw API data into a structured dataset, the project uncovers regional trends and highlights the continued importance of physical music formats.

## Data Source
- Discogs Public API  
- Data collected via authenticated API requests

## Tools & Technologies
- Python (Pandas, NumPy)
- Jupyter Notebook
- MySQL
- Tableau
- Excel

## Project Workflow
1. Data Acquisition
   - Attempted HTML scraping but encountered access restrictions
   - Switched to Discogs API for reliable and structured data collection
2. Data Cleaning & Preparation
   - Handled missing values and empty strings
   - Normalized multi-valued fields (genre, style, format, label) by splitting comma-separated values
   - Preserved duplicates where analytically meaningful
3. Database Storage
   - Stored cleaned data in a MySQL database (Dsci105)
   - Created a structured table (discogs_music) for querying and analysis
4. Exploratory Data Analysis
   - Analyzed genre frequency, style diversity, country contributions, and format distributions
   - Explored relationships between genres, styles, labels, and countries
5. Visualization & Dashboarding
   - Exported cleaned data to Excel for Tableau integration
   - Built interactive dashboards featuring bar charts, stacked bars, heat maps, bubble charts, pie charts, and geographic maps
   - Added filters for country, genre, style, format, and label to support dynamic exploration
     
## Key Analyses & Insights
- Genre and style distribution across countries
- Geographic trends in music releases
- Popular formats (vinyl, CD, digital) by region
- Record label activity and market presence
- Relationships between genres, styles, and physical media formats

## Project Structure
data/       → Cleaned datasets and exports  
scripts/    → Python API collection and data cleaning scripts  
tableau/    → Tableau dashboards and packaged workbooks  
report/     → Final project report and documentation  
