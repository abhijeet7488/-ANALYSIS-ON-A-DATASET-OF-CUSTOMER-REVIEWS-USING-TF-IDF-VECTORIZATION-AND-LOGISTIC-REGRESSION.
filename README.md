# -ANALYSIS-ON-A-DATASET-OF-CUSTOMER-REVIEWS-USING-TF-IDF-VECTORIZATION-AND-LOGISTIC-REGRESSION.
COMPANY: CODTECH IT SOLUTIONS
NAME: ABHIJEET KUMAR
INTERN ID: CTO4DG2125
DOMAIN: MACHINE LEARNING
DURATION: 4 WEEKS
MENTOR: NEELA SANTOSH
DESCRIPTION : 
In this project, My aim to analyze customer reviews from Amazon and determine whether each review is positive or negative. 
This is a classification task, and I solve it using Logistic Regression, a popular machine learning algorithm. 
To convert text into numbers that a machine can understand, I use TF-IDF vectorization.
Here, I use a real-world dataset called the Amazon Product Reviews dataset, which contains thousands of reviews, ratings, and metadata.

Step 1: Load the Dataset
First, I start by loading the dataset using Pandas. The dataset typically contains many columns, but I focus on:
reviews.text: The actual review written by the user
reviews.rating: A numeric value (1 to 5) indicating how satisfied the user was

Step 2: Clean the Data
Then, I check for missing values using df.isnull().sum() and drop any rows where reviews or ratings are missing. 
This ensures our model gets clean input.
I also convert the rating into a binary sentiment label:
1 for positive sentiment (ratings 4 or 5)
0 for negative sentiment (ratings 1, 2, or 3)

Step 3: Text Preprocessing
Before feeding text to the model, I clean it by removing symbols, numbers, and converting everything to lowercase. 
Then, I also use stopwords removal and lemmatization.

Step 4: TF-IDF Vectorization
I cannot feed raw text to a machine learning model, so I use TF-IDF (Term Frequency-Inverse Document Frequency) to convert text into numerical features. 
This technique helps highlight words that are important in each review, while reducing the weight of common words like “the”, “and”, etc.

 Step 5: Train-Test Split
Then, I divide data into training and testing sets (e.g., 80% for training and 20% for testing).
so, that I can train the model and evaluate how well it performs on new, unseen data.

Step 6:  Train Logistic Regression Model
Logistic Regression is a simple and effective model for binary classification tasks.
I Use to train it on our TF-IDF features.

Step 7: Evaluate the Model
Then, I make predictions on the test set and evaluate performance using:
Accuracy Score
Classification Report (includes precision, recall, and F1-score)
Confusion Matrix (shows actual vs predicted classes)

#OUTPUT :
<img width="920" height="679" alt="Image" src="https://github.com/user-attachments/assets/32460096-acf4-4d9e-9d51-e8072aa7ef0a" />

