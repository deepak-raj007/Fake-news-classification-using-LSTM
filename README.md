# Fake-news-classification-using-LSTM

This project aims to classify news articles as either real or fake using an LSTM-based sequential model. The dataset used for this project contains 72,134 news articles, with 35,028 real and 37,106 fake news articles. The dataset is a combination of four popular news datasets, namely Kaggle, McIntire, Reuters, and BuzzFeed Political, to prevent over-fitting of classifiers and to provide more text data for better machine learning training.

Data Cleaning
The first step in the process is data cleaning. This involves removing NaN values, punctuations, and other special characters from the news articles. After the cleaning process, the data is then stemmed to reduce the dimensionality of the dataset.

Preprocessing
After cleaning the data, one-hot representation is used to transform the text data into numerical vectors. The next step is word embedding, which is a technique used to represent words in a dense vector space, where words with similar meanings are close to each other.

LSTM-based Sequential Model
The LSTM-based sequential model is used to train the dataset. The model is trained using the preprocessed data, and the weights of the model are updated iteratively to minimize the loss function. The LSTM-based model is chosen for this project because of its ability to model long-term dependencies in sequential data.

Model Performance Evaluation
To evaluate the performance of the LSTM-based sequential model, metrics such as the confusion matrix and accuracy are used. The confusion matrix is a table used to evaluate the performance of a classifier by comparing the predicted values with the actual values. The accuracy of the model is found to be 87%.

Conclusion
In conclusion, this project aims to classify news articles as either real or fake using an LSTM-based sequential model. The dataset used in this project contains 72,134 news articles, and the model's accuracy is found to be 87%. The cleaning, preprocessing, and training of the model are essential steps in building an accurate and robust model for fake news classification.
