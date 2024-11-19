# MBTI Personality Prediction Model

**Project Overview:**

The MBTI Personality Prediction Model is a machine learning-based system designed to predict the Myers-Briggs Type Indicator (MBTI) personality type from text data. The system leverages social media posts, utilizing natural language processing (NLP) techniques to analyze text features such as word frequency, stopwords, and tokenized words to predict one of the 16 MBTI personality types.

**Key Features:**

* Data Preprocessing: The dataset was cleaned by removing stopwords, punctuation, and irrelevant information, making the text suitable for analysis.
* Machine Learning Model: Utilized Logistic Regression, trained on text features extracted using the TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer.
* Real-World Dataset: The model is trained on a dataset of over 106067 social media posts with 500 words each labeled with MBTI personality types, providing realistic predictions based on real-world text.

**Technologies Used:**

* Python: For data manipulation, machine learning, and text processing.
* Natural Language Processing (NLP): Techniques such as tokenization, stopword removal, and TF-IDF vectorization.
* Machine Learning: Logistic Regression algorithm for classification.
* Scikit-learn: For model implementation and text vectorization.

**How It Works:**

* Input: Users provide a social media post or text (e.g., a status update or comment).
* Prediction: The system uses the trained Logistic Regression model to predict the MBTI personality type based on the provided text.
* Output: The web interface displays the predicted MBTI personality type, which can be one of the 16 types (e.g., INTJ, ENFP).

**Conclusion:**
This project demonstrates the power of machine learning and natural language processing to predict a person's MBTI personality type from text. It shows how text-based features can be used to classify personality types, offering an interesting use case for psychological analysis or content recommendations.
