# Data Mining
Data Cleaning, Querying and Visualization with Pandas DataFrame.

### Description
This project is intended to prepare six months of Airbnb Athens data for queries. Pandas DataFrames are incredibly versatile and are appropriate for a wide range of tasks involving data. They provide a rich set of tools to perform data cleaning and preprocessing and also make it easy to calculate descriptive statistics. They work seamlessly with most machine-learning and visualization Python libraries. The project is divided into two Jupyter(.ipynb) notebooks containing both the code and explanations of each step.
- *mining_2019*
    - First the data are cleaned(e.g dropping undesirable columns), then queries are performed and the results are visualized. Α Recommendation System with TF-IDF and Cosine Similarity is then implemented to find and recommend rooms that are similar to each other and common to the user's preferences.
- *sentiment_19_23*
    - A new DataFrame with a column sentiment is created using NLP models from Hugging Face. The sentiment is extracted(annotation process) from the comments of the given data. Sentiment Analysis with TF-IDF and Word-Embedding. Three different classifiers are tained and tested on the data: SVM, Random Forest and KNN.
