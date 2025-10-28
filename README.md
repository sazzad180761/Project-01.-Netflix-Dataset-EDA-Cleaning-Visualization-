Netflix Movies & TV Shows — Exploratory Data Analysis (EDA)

Project Overview :
This project aims to perform Exploratory Data Analysis (EDA) on the Netflix dataset, which contains detailed information about movies and TV shows available on the platform.
Through this analysis, we explore patterns, trends, and insights related to content type, release year, directors, countries, and more.

Dataset Information :

Dataset Name: Netflix Dataset
Source: Netflix Titles on Kaggle
Total Records: 8,808
Main Columns:

  01. show_id — Unique ID
  02. type — Movie or TV Show
  03. title — Name of the content
  04. director — Director’s name
  05. cast — Main actors
  06. country — Production country
  07. date_added — Released date
  08. release_year — Year released
  09. rating — Age rating
  10. duration — Duration or number of seasons
  11. listed_in — Genre category
  12. description — Short summary


Tools & Libraries Used :

  import pandas as pd
  import numpy as np
  import matplotlib.pyplot as plt
  import seaborn as sns
  from wordcloud import WordCloud

EDA Steps Performed :

  01. Data Loading & Cleaning
  02. Handling Missing Values
  03. Data Type Correction (e.g. Date formatting)
  04. Feature Exploration & Summary Statistics
  05. Country-wise, Year-wise, and Genre-wise Analysis
  06. Visualization (Bar, Pie, WordCloud, Heatmap, etc.)
  07. Observation & Insights Documentation

Key Visualizations :
 01. Ratio (%) pie chart of movies and tv shows.
 02. Finding the released country of content by bar plot.
 03. Finding the released year of content by bar plot.
 04. Year-wise trend plot of movie vs tv show.
 05. Finding the rating of the content by bar plot.
 06. Creating a wordcloud from listed entry into dataset.

Observations :
  The founded 15 key observation of the netflix dataset that below into the  EDA code.

Conclusion :

  Through this analysis, we identified trends in Netflix’s content distribution, genres, and growth pattern.
This EDA helps understand how Netflix has evolved globally and how its catalog varies across countries and content types.

Author : 
  Md. Sazzad Hossen Patwary
  EEE Student | Aspiring AI Engineer | Data Enthusiast
  Email : sazzad180761@gmail.com
  Bangladesh
    


