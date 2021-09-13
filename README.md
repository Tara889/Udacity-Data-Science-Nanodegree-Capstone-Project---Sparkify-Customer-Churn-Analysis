# Udacity-Data-Science-Nanodegree-Capstone-Project---Sparkify-Customer-Churn-Analysis

## Libraries

Following are the moduels which have been used in the notebook and are necessary for running the notebook.

Python 3.6

NumPy

Pandas

scikit-learn

matplotlib

Pyspark


## Project Summary:
The Project is part of Udacity's Data Science Nano Degree. The project primarily uses Spark for Python called pyspark to do the analysis.

Imagine you are working for music streaming company like Spotify or Pandora called Sparkify. Millions of users stream their favorite songs everyday. Each user uses either the Free-tier with advertisement between the songs or the premium Subscription Plan. Users can upgrade, downgrade or cancel their service at any time. Hence it's crucial to make sure that users love the service provided by Sparkify. Every time a users interacts with the Sparkify, app data is generated. Events such as playing a song, logging out, like a song etc. are all recorded. All this data contains key insights that can help the business thrive. The goal of this project is then to analyze this data and predict which group of users are expected to churn - either downgrading from premium to free or cancel thier subscriptions altogether.

The most important factor in predicting a user churn is actually the total amount of time a user has been with the app. The lesser this time the more possibility for the user to churn. Which is clearly seen in many organizations that they focus heavily on the users which are new so that they are satisfied with the service and do not churn.
There are other factors in case of Sparkify which affect the Churn which are more amount of Thumbs Down given , Less Friends added and songs added to playlist, more advertisments being shown to users are some of the important ones.
Random Forest Classifer is best able to predict the churn.


The project contains the following tasks:

1. Data Exploration

Learn about the data, Load and clean the dataset, checking for invalid or missing data - for example, records without userids or sessionids.

2. Define Churn and label data based on churn definition

Determine the feature's which can be considered as churn to use as the label for your model (Example Cancell confirmation)

3. Feature Engineering

Once you've familiarized yourself with the data, build out the features you find promising to train your model on. To work with the full dataset, you can follow the following steps.

Write a script to extract the necessary features from the smaller subset of data
Ensure that your script is scalable, using the best practices discussed in your lessons.
Try your script on the full data set, debugging your script if necessary.


4. Data transformation, data splitting and model training  

Transform feature engineered data.
Split data into training, validation and test data.
Build a machine learning model to train using training data

5. Evaluating on Test Set

Try tesing using different Modules which helps in deciding on the best Model to be used.


## Files and Data descriptions:

Sparkify.html/ipynb - notebook used in Udacity Workspace

mini_sparkify_event_data.json - Data file containing the streaming music provider's user logs


## Results:

1. The most important factor in predicting a user churn is actually the total amount of time a user has been with the app. The lesser this time the more possibility for the user to churn. Which is clearly seen in many organizations that they focus heavily on the users which are new so that they are satisfied with the service and do not churn.
2. There are other factors in case of Sparkify which affect the Churn which are more amount of Thumbs Down given , Less Friends added and songs added to playlist, more advertisments being shown to users are some of the important ones.
3. Random Forest Classifer is best model to predict the churn.

## References:

https://medium.com/@nakshatra1988/sparkify-customer-churn-analysis-423a5c401a8f

