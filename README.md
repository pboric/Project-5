# Podcast Reviews Dataset Analysis Notebook

This Jupyter notebook provides an analysis of a Podcast Reviews Dataset. The analysis is divided into several sections:

1. **Import Libraries**: Necessary libraries such as pandas, numpy, sqlite3, textblob,  matplotlib, , wordcloud, scipy, scikit-learn and statsmodels

2. **Explore the Database**: The SQLite database is explored to understand the schema of the tables. The database is then queried to join the podcasts, categories, and reviews tables into a single DataFrame.

3. **Data Cleaning**: The ‘category’ column is cleaned by applying a mapping to consolidate similar categories. Rows with missing values and duplicates are dropped.

4. **Exploratory Data Analysis (EDA)**: The cleaned data is analyzed. This includes checking for missing values and duplicates, visualizing the distribution of ratings, exploring the number of podcasts per category, analyzing the average rating by category, creating a word cloud for common words used in reviews, and performing sentiment analysis on the review content.

5. **Statistical Inference**: Three hypotheses tests are performed. The first test suggests that podcasts that receive reviews more frequently might be more popular or engaging, leading to a more positive sentiment in the reviews. The second test proposes that newer podcasts might receive a ‘honeymoon’ effect where initial listeners are more enthusiastic and likely to give higher ratings, which could change as the audience grows. The third test assumes that the popularity of a category, as measured by the number of reviews, is positively correlated with the sentiment of the reviews, indicating overall satisfaction within popular categories.

## About the dataset

The data is from [Podcast Reviews Dataset](https://www.kaggle.com/datasets/thoughtvector/podcastreviews/versions/28).

Dataset built with PointScrape.

Photo credit: Kati at xilophotography.com; Instagram @xilophotography. The creator featured can be found on Twitter @csallen. Full story: convertkit.com/courtland

Licensing
For commercial applications and use of full dataset, please contact stuart@thoughtvector.io.

License
CC BY-NC-SA 4.0
