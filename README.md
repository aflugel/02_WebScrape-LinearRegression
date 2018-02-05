# 02_WebScrape-LinearRegression: Scraping [MobyGames.com](http://www.mobygames.com/) and predicting critic scores
I worked on this project for two weeks as part of the Metis Chicago 2018 Winter Cohort. This was **Project 2**.  
  
We were given free reign to pick our problem and data sources, with two requirements:
1. Procure our data via web scraping, and
2. Use linear regression to predict a target variable.  
  
----
  
This project is broken into 3 Jupyter Notebooks.  
* **[Notebook 1](aflugel02-Notebook1.ipynb) - Covers the web-scraping step. Results in:**
  1. **[allgames.pk1](allgames.pk1)**: DataFrame with scraped data for all current console games.
  2. **[score_df.pk1](score_df.pk1)**: DataFrame pared down to only the rows that contain the target: critic score.  
  
* **[Notebook 2](aflugel02-Notebook2.ipynb) - Data cleaning and transformation. Results in:**
  1. **[df_mod.pk1](df_mod.pk1)**: The cleaned DataFrame for use in the EDA and modeling steps.
  
* **[Notebook 3](aflugel02-Notebook3.ipynb) - Covers the EDA and linear regression.**
