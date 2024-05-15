# YELP

### Overview
Welcome to the Natural Language Processing (NLP) Project for this section of the course! In this project, we aim to classify Yelp Reviews into 1 star or 5 star categories based on the text content in the reviews. We will be utilizing the Yelp Review Data Set from Kaggle for this purpose. Each observation in this dataset represents a review of a particular business by a specific user. The "stars" column indicates the rating given by the reviewer to the business, ranging from 1 to 5.

### Data
We start by reading the Yelp review data from the provided CSV file using pandas. The dataset contains 10,000 entries with 10 columns including business ID, date, review ID, stars, text, type, user ID, cool, useful, and funny votes. We perform exploratory data analysis (EDA) to understand the distribution of star ratings and the relationship between various features such as text length and star ratings.

### NLP Classification Task
To perform the classification task, we preprocess the text data by creating a new feature called "text length" representing the number of words in the review text. We then split the data into training and testing sets. For training the classification model, we utilize the Multinomial Naive Bayes algorithm. We evaluate the model's performance using a confusion matrix and a classification report, achieving a high accuracy for predicting 1-star and 5-star reviews.

### Using Text Processing
In an attempt to enhance our model's performance, we integrate TF-IDF (Term Frequency-Inverse Document Frequency) into our pipeline. However, despite our efforts, the TF-IDF transformation yields unexpected results, leading to a decline in model accuracy. We conclude the project with suggestions for further experimentation, such as modifying the pipeline steps or exploring alternative machine learning models.

### Conclusion
This README provides an overview of the NLP project, outlining the data preprocessing steps, model training, evaluation metrics, and insights gained from the analysis. Feel free to explore and experiment with different approaches to further enhance the classification performance. Great job on completing the project!
