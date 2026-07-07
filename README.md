# SENTIMENT-ANALYSIS

# TASK 4: SENTIMENT ANALYSIS USING NATURAL LANGUAGE PROCESSING (NLP)

COMPANY: CODTECH IT SOLUTIONS PRIVATE LIMITED

NAME: N THEJESH KUMAR

INTERN ID: CITS575

DOMAIN: DATA ANALYTICS

DURATION: 8 WEEKS

MENTOR: NEELA SANTHOSH KUMAR

# DESCRIPTION

This project was completed as part of the Data Analytics Internship at CODTECH IT Solutions Private Limited. The objective of this task was to perform sentiment analysis on textual data using Natural Language Processing (NLP) and Machine Learning techniques. Sentiment analysis is one of the most popular applications of NLP and is widely used to identify whether a piece of text expresses a positive or negative opinion. It has practical applications in customer feedback analysis, product reviews, social media monitoring, market research, and business intelligence.

The project was implemented using Python in Google Colab. Several libraries were used, including Pandas for data handling, Scikit-learn for machine learning and text feature extraction, and Matplotlib for visualization. The dataset used in this project was the IMDb Movie Reviews Dataset, which contains thousands of movie reviews labeled as either positive or negative. This dataset is widely used for learning and evaluating sentiment analysis models.

The project began by loading the dataset into a Pandas DataFrame and exploring its structure. The sentiment labels were converted from text values ("positive" and "negative") into numerical values (1 and 0) so that they could be processed by machine learning algorithms. The review text was selected as the input feature, while the sentiment label served as the target variable.

The dataset was divided into training and testing sets using the train_test_split() function. Eighty percent of the data was used for training the model, while the remaining twenty percent was reserved for testing. This approach allows the model to be evaluated on unseen data and provides a reliable estimate of its performance.

Since machine learning algorithms cannot process raw text directly, the review text was transformed into numerical feature vectors using the TF-IDF (Term Frequency–Inverse Document Frequency) Vectorizer. TF-IDF is an effective text representation technique that assigns higher importance to meaningful words while reducing the influence of very common words. The vocabulary size was limited to 5,000 features to improve computational efficiency while preserving important information from the reviews.

A Multinomial Naive Bayes classifier was selected as the machine learning algorithm because it is simple, efficient, and performs well on text classification problems. The model was trained using the transformed training data and then used to predict the sentiment of unseen movie reviews in the testing dataset.

The model's performance was evaluated using several standard classification metrics, including Accuracy, Precision, Recall, F1-Score, and a Confusion Matrix. The model achieved an overall accuracy of 85.08%, demonstrating its ability to classify movie reviews with good performance. Both Precision and Recall were approximately 85%, indicating that the classifier effectively identified both positive and negative sentiments. The F1-Score also reached 85%, showing a balanced trade-off between precision and recall.

A Confusion Matrix was generated to visualize the model's predictions and classification performance. This graphical representation helped identify correctly classified reviews as well as misclassified examples, providing a better understanding of the model's strengths and limitations.

Overall, this project successfully demonstrated the complete Natural Language Processing pipeline, including data loading, text preprocessing, feature extraction using TF-IDF, machine learning model training, prediction, evaluation, and visualization. The project provided valuable practical experience in NLP and sentiment analysis while highlighting how machine learning techniques can be used to extract meaningful insights from textual data. The knowledge gained through this project can be extended to real-world applications such as customer feedback analysis, review classification, opinion mining, and social media sentiment monitoring.
