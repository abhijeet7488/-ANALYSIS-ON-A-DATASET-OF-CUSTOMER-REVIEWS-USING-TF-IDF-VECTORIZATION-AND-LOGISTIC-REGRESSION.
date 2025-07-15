# -ANALYSIS-ON-A-DATASET-OF-CUSTOMER-REVIEWS-USING-TF-IDF-VECTORIZATION-AND-LOGISTIC-REGRESSION.
COMPANY: CODTECH IT SOLUTIONS
NAME: ABHIJEET KUMAR
INTERN ID: CTO4DG2125
DOMAIN: MACHINE LEARNING
DURATION: 4 WEEKS
MENTOR: NEELA SANTOSH
DESCRIPTION : 
The goal of this task is to analyze the sentiment (positive or negative) from a dataset containing customer reviews, using two popular techniques:
TF-IDF Vectorization to convert text into numbers.
Logistic Regression to build a classification model.
This type of analysis is used widely in real-world apps like Amazon product reviews, movie ratings, and customer feedback forms.
Step 1: Load the Dataset
I use pandas to load a .csv file containing two columns:
review: the customer text.
sentiment: either "positive" or "negative".
Step 2: Preprocess the Text
To clean the text and prepare it for modeling, remove punctuation, lowercase all text.
Step 3: Split the Data
Divide the data into training and testing sets.
Step 4: Convert Text to Numbers (TF-IDF)
TF-IDF stands for Term Frequency - Inverse Document Frequency. It measures how important a word is in a document relative to all other documents.
 Step 5: Train the Logistic Regression Model
 Use the logistic regression model to classify reviews.
Step 6: Make Predictions and Evaluate
 Predict on the test set and measure how accurate the model is.
Step 7: Visualize the Results
Plot a confusion matrix which showing the number of correct vs incorrect predictions.
