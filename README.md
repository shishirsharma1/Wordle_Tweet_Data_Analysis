# Wordle Tweets Analysis
This project analyzes a dataset of Wordle tweets from Kaggle. The goal is to explore user behavior through tweets related to Wordle, including analyzing the number of attempts users take to solve the game and identifying trends in tweet activity.

## Step 1 : Data Preprocessing  

The process_tweets() function was created to perform multiple preprocessing tasks:

Convert the tweet_date to a datetime object for easier date-based analysis.  
Extract the wordle_id from the tweet text.  
Extract the number of attempts (n_attempts) users took to solve the Wordle.  
Assign a unique id based on part of the tweet text.  

## Step 2 : Analysis of Tweets by Date
To analyze how many tweets were posted each day:
![image](https://github.com/user-attachments/assets/bfae9cd7-bd9c-4914-b479-e59aff3ff54a)

## Step 3 : Number of Attempts Analysis

Analyzed the distribution of the number of attempts users took to solve Wordle:  
![image](https://github.com/user-attachments/assets/25d76e87-2a88-4b3d-abb2-90d9d2a4db56)

## Step 4 : Wordle Results by Guess Number
This section analyzes the correctness of letters by guess number: 
![image](https://github.com/user-attachments/assets/38a69426-0c73-4f0f-b570-1d622f7cf850)

## Step 5 : Most Common Correct First Guess Letters
Analyzed the most frequent correct first guess letters in Wordle tweets to understand user tendencies in their first guesses.  
![image](https://github.com/user-attachments/assets/8a05b22b-58b4-43fb-8af2-a8638462afa6)

## Tools Used
**Pandas**: For data manipulation and processing.
**Matplotlib**: For data visualization.
**Kaggle Wordle Tweets Dataset**: Dataset used for analysis.
