# Star Rating Prediction for Customer Reviews on Smartphones

# Introduction
Huge abundance e-commerce websites and online
reviews have become crucial these days. These reviews help
customers in making decisions but one must go through huge pile
of reviews in many sites. We have summarized the reviews into
STARS on a scale of 1-5 which are easy to perceive. So, for a
given customer review, we predict the star rating of the review. 
 
# Methodology

// methodology image

# Algorithms Used

* Term frequency-Inverse Document Frequency(TF-IDF)
* Multinomial Naive Bayes
* Bigram Multinomial Naive Bayes
* Random Forest

# Dataset

The [Dataset](https://www.kaggle.com/datasets/PromptCloudHQ/amazon-reviews-unlocked-mobile-phones) has been collected from Kaggle. It is a corpus of  4,13,840 reviews. It has 6 attributes as shown below:

// Data image
 
# Libraries Used

* **pandas**:  load and manipulate the dataset
* **numpy**:  linear algebra and arrays
* **matplotlib** and **seaborn**: to plotting the distribution
* **NLTK, spaCy, textblob, wordcloud**: process the data
* **symspellpy**: spelling correction
* **re**: regular expression
* **contractions**: expanding contractions
* **sklearn, joblib**: feature vector generation and model building
