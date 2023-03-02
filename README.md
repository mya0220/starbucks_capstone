# Starbucks Offer Capstone Project
Link for this repo in github: https://github.com/mya0220/starbucks_capstone

0. Motivation: Starbucks offers various types of promotions and incentives to encourage customers to purchase their products. However, it is difficult to determine which type of offer is the most effective in encouraging customers to make purchases. The project will help Starbucks to better understand their customers’ behavior and preferences, allowing them to optimize their offers and increase customer loyalty and revenue.

1. Goal: The data contains starbucks customer info, offer info and transaction data. The goal for this project is to make a classification model that can tell us whether or not a customer will respond to certain 'offer event'.

2. Deliverable: A post on 'Medium'. 
	Link: https://medium.com/@mya0220.cheng/how-likely-do-people-respond-to-starbucks-offer-2ac779930692

3. Files: 
        - /data contains 3 json files that contains offer info (portfolio.json), customer data (profile.json) and transaction data (transcript.json) 
        - Starbucks_Capstone_notebok.ipynb contains the ETL process and model development, testing process.
	-/Figure contains data visualization used for Medium Post.

4. library used:
matplotlib==3.5.2
matplotlib-inline==0.1.3
numpy==1.23.0
pandas==1.4.3
scikit-learn==1.1.1
scipy==1.8.1
seaborn==0.12.1

5. Summary of result:
The notebook contains necessary EDA to include factors that seem significant.
A random forest classification model with accuracy of 72% was built.

6. Acknowledgement
Data source -> Udacity DS Nano degree program



