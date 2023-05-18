
# Task 2 - Classification
We start the process by: Using the Hespress Dataset NLP, particularly the stories, to perform 
exploratory data analysis, gain insights, and comprehend the data properly.

## 1. Text Preprocessing:
* Tokanization
* Remove Non-Arabic words
* Remove Tashkeel
* Remove Punctuations
* Remove Digits
* Remove URLS if found in the text

## 2. Feature Extraction :
This dataset contains text so that we can manipulate this text, we must convert it into numerical values before modeling, we used TF_IDF to get the feature from the text and classify which text belongs to the topic.
TF_IDF deals in a good and direct way with text that can get the unique words and give these words more importance and it is best for Herpress data which in each topic contains different words expressing the topic.

## 3. Split the Data:
Divide the dataset into 80% for training  and 20% for testing sets. The training set is used to train the model, while the testing set is used to evaluate its performance on unseen data.

## 4.Modelling 
At the stage we used classification model Logistic Regression to classify the topics, the accuracy of the LR is 85.45% indicating that it correctly classifies 85% of the instances in the test set, also by displaying confusion matric and classification report.

## 5.Model Evaluation: 
the accuracy of the Logistic Regression is 85.45% indicating that it correctly classifies 85% of the instances in the test set, also by displaying confusion matric and classification report


