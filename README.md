# OneAPI-Hakhathon-Project
# EPL match prediction

## Overview

Welcome to the English Premier League (EPL) Match Result Prediction Project! This project was created as part of my application for the Intel Student Ambassador position. In this project, I have implemented three different classification algorithms -Random Forest, Naive Bayes, and Decision Trees - to predict the outcomes of EPL matches.

## Project Goals

The main objective of this project is to explore the effectiveness of these machine learning classifiers in predicting EPL match results. The analysis aims to accomplish this by comparing the team's success under various captains and tracking the captaincy over many matches. Important performance metrics like possession, shots on goal, and distance traveled will be critical in determining how well a player leads the team. Players may be identified as possible weak leaders if they consistently perform below expectations or show negative trends in certain indicator.

## Why EPL Match Prediction?

Predicting the outcomes of EPL matches is not only an exciting application of machine learning but also has practical implications in sports analytics and betting. It involves a blend of data analysis, feature engineering, and model evaluation, making it an ideal project to showcase my skills and passion for machine learning.

## Project Structure

* Data collection: The data provides information on games from seasons 21/22 and 22/23. The features include ['date', 'time', 'comp', 'round', 'day', 'venue', 'result', 'gf', 'ga','opponent', 'xg', 'xga', 'poss', 'attendance', 'captain', 'formation','referee', 'sh', 'sot', 'dist', 'fk', 'pk', 'pkatt', 'season', 'team'] where 'result' is the target label. 
  
* Preprocessing: Data preprocessing includes cleaning, finding missing values, replacing missing numerical values with median values, categorizing, label encoding, normalizing, and target label balancing using SMOTE for model training.

<img width="437" alt="pic1" src="https://github.com/ShrutiChrist/OneAPI-Hakhathon-Project/assets/136952379/2f6839b2-138b-4585-9d89-69ca2adc06e9">
<img width="355" alt="pic2" src="https://github.com/ShrutiChrist/OneAPI-Hakhathon-Project/assets/136952379/486d2f7e-82e8-4383-81a0-8e312ac652eb">


* Model Implementation: We implement Random Forest, Naive Bayes, and Decision Tree classifiers.

* Evaluation: Each model's performance is evaluated using accuracy.

* Comparison: We compare the models to determine which one performs the best in predicting EPL match results.

Perform statistical tests to determine significant differences in performance metrics among different captains:
The output indicates that there is a significant difference in possession among different captains with a p-value less than 0.05, it suggests that the average possession values of matches led by different captains are statistically different from each other.
![image](https://github.com/ShrutiChrist/OneAPI-Hakhathon-Project/assets/136952379/cfc1a2f7-59f1-4fcb-9a89-f83bbeea9e70)


In practical terms, this means that the choice of captain may have a discernible impact on the team's possession performance during matches. This information can be valuable for team management and coaching staff in decision-making processes related to captaincy and tactical strategies.

* Documentation: The project is well-documented, including code comments and explanations to help others understand and replicate the work.

## Intel oneAPI

With Intel(R) Extension for Scikit-learn you can accelerate your Scikit-learn applications and still have full conformance with all Scikit-Learn APIs and algorithms. This is a free software AI accelerator that brings over 10-100X acceleration across a variety of applications. And you do not even need to change the existing code!

## Result

![image](https://github.com/ShrutiChrist/OneAPI-Hakhathon-Project/assets/136952379/5947b19d-c4f7-4973-a079-3cf7baf23b2c)


## Dependencies

* Python
* Scikit-lean
* Intelex
* Pandas
* Matplotlib
* Seaborn

## How to use?

Download the notebook and run it in your favorite IDE for ML. 

## Conclusion

I hope you find this project insightful and informative. Feel free to explore the code, dataset, and documentation to better understand the process and results of predicting EPL match outcomes using machine learning.

If you have any questions, suggestions, or feedback, please don't hesitate to reach out.

Thank you for visiting this repository!
