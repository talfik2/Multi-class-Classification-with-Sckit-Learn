# Multi-class-Classification-with-Sckit-Learn
In this repository, I tried to predict time signature of the spotify songs in our dataset. 
**Time Signature** (also known as meter signature, metre signature, or measure signature) is a notational convention used in Western musical notation to specify how many beats (pulses) are to be contained in each bar and which note value is to be given one beat. 
In this dataset, we have 4 kinds of time signatures : 1,3,4,5. As we will classify our dataset according to these 4 time signatures, we'll have multiclass classification problem. 
We'll do this by Scikit-Learn 
To do that, first, we need to import the necessary libraries & our dataset ,and then fit our dataset for our ML models.

Source of the dataset is : https://www.kaggle.com/mrmorj/dataset-of-songs-in-spotify

In this repository, I used train_test_split to split dataset into training and test sets.

SimpleImputer to clean the data.

SVC, KNN, and TPOT to classify data for each unique case.

TO tell how much the model is capable of distinguishing between classes, I implemented TPOT's roc_auc_score and roc_auc_score_multiclass from this adress : https://stackoverflow.com/questions/39685740/calculate-sklearn-roc-auc-score-for-multi-class/52750599#52750599

Best pipeline steps with TPOT to spot how to move on best.

KNN's .score() method to measure model's success.
