This directory contains all of our analysis files.

Eda.ipynb: This notebook first preprocesses the raw data, including santizing text reviews and summaries, converting them to lowercase, and adding polarity scores the reviews and summaries using the VADER lexicon for sentiment analysis. Then we combine multiple datasets from different product categories into a single DataFrame and analyze the distrbution of overall scores in the Dataframe. Lastly we create multiple visualizations to view information on the overall scores, polarity scores, and the number fo reviews per year.

Preprocesing and Model 1: Some of these pre-processing steps are repeated. Then, Model 1 is define where X is the year and Y is the proportion of negative or positive reviews. A similar linear model equation is used: proportion = t0 + t1*(year). Then we evaluate the model usings a residuals plot.

Model 2: First we use a Heatmap Visualization to groups the combined dataset by product identifier and calculates the mean values for various features such as overall rating, vote count, polarity of reviews, etc. Then Model 2 is created to predict polarity values based on these features: year, length of review, verified, and number of votes.

Model 3: Data Preparation includes making seven dataframes (df, df2, ..., df7) each representing a different category of products (e.g., Lawn, Sports, Tools, Toys, Video Games, Movies, Kindle). Then the data is split into train and validation with an 80-20 ratio. Methods such as one-Hot encoding, and Lasso Regression are used to improve Model 2. Then the model's performance is measured using RMSE error and a residual plot.
