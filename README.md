* The project is about predicting whether the Dow Jones Industries (a stock market index) went up or down based on newspaper headlines. This is called sentiment analysis for stock prices.

To implement/make this project, we first collected the top 25 headlines from newspapers of 2000 to 2019.

* Tokenization: break down the headlines into individual words or phrases, split a sentence into component words. A common technique for this is TF-IDF (Term Frequency-Inverse Document Frequency), which tells how often a word appears in a document compared to its overall appearance in the entire dataset. This helps focus on important words and reduce unimportant ones.
Then, we developed a machine learning model. This model was specifically a binary classification model, meaning it could only predict two outcomes: whether the Dow Jones went up or down. By analyzing the patterns in the headlines and their relation to stock movement, the model "learned" to predict if future news would indicate a rise or fall in the market.

* Project Steps:
Data Collection: Gathering the top 25 headlines from newspapers from 2000 to 2019.
Data Preprocessing: Cleaning the data, removing unnecessary information, and preparing it for analysis.
Feature Engineering: using techniques like Tf-Idf.
Model Training: Developing and training the machine learning model using binary binary classification model
Evaluation: Assessing the performance of the model to ensure its accuracy.
Prediction: Using the trained model to predict whether the Dow Jones went up or down based on the headlines.
The project achieved an accuracy of 0.84122, which means it was successful in predicting the movement of the Dow Jones Industrial Average based on newspaper headlines.
