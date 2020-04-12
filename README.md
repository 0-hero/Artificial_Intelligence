# Predicting Stock Prices with twitter Sentimental Analysis

This project uses **RandomForest**, **Linear Regression**, **MLPClassifier** and compares the accuracy of the prediction.

## How it works?
Step 1. Collect historical tweets about companies using twitter API based on hashtag. Ex ***#Apple*** <br>
Step 2. Calculate the scores if its negative or positive using sentimental analysis for each tweet <br>
Step 3. Train the model using the tweets score for the day and stock price on that partcular day. ***Tweets score will be independent variable & Stock price will be dependent***. <br>
Step 4. Predict and test the accuracy of each model. <br>

## What's being done?
### Part 1: 
Step 1. I collect tweets using the API on Reliance Industries based on JIO hashtag for a week.<br>
Step 2. Get stock data for the week.<br>
Step 3. Tain the model and predict <br> <br>
**Result :** As the data is too little to predict anything we couldn't get proper results. We coudn't collect more data due to the limitations of twitter API. <br>
![](Outputs/RandomForest_Reliance_Week_Data.png)

### Part 2: 
Step 1. I found a prepared dataset of Apple stock prices with tweets.<br>
Step 2. Process he dataset.<br>
Step 3. Tain different models and predict using each model and compare accuracy scores.<br><br>
**Result :** RandomForest goves the best accuracy of 91%<br>
![](Outputs/RandomForest_Apple_Historical_Dataset_Final.png)
