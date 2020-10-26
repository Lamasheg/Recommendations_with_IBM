# Recommendations_with_IBM
 
### Table of Contents

1. [Project Summary and File Description](#summary)
2. [Installation](#installation)
3. [Results](#results)
4. [Acknowledgements](#summary)


    
## Project Summary and File Description<a name="summary"></a>

This Project is part of Data Science Nanodegree Program by Udacity. The project purpuse is to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they will like..
the analysis is done by studying data available on the IBM Watson Studio platform

The project is implimented in steps to achieve the final goal:
1. Exploratory Data Analysis: dive in the dataset provided for analysis

2. Rank Based Recommendations: find the most popular articles simply based on the most interactions

3. User-User Based Collaborative Filtering: find users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users as means to personalize recommendations

4. Matrix Factorization: a machine learning approach to building recommendations to predict articles a user will like

all methods to complete this projects are included in the python notebook (Recommendations_with_IBM.ipynb)


## Installation <a name="installation"></a>
- This project is developed using Python 3

- Libraries used:

    `pandas`

    `numpy`

    `matplotlib for visualizations`
    
    `Pickle`
        
    
## Results<a name="results"></a>

*Multiple recommendations used, including:
- Rank Based Recommendations


- User-User Based Collaborative Filtering


- Matrix Factorization: 

`with the increased number of latent features, we start to experience overfitting, decreasing the accuracy of our recommendations. As means to test the performance of our new recomendation engines, we can:
Offer both the old and new recommendation engines to randomly assigned users
Test performance using the number of interactions to recommended articles as a metric
Insure random assignment of users`


*Link to GitHub repository: https://github.com/Lamasheg/Recommendations_with_IBM.git


## Acknowledgements<a name="licensing"></a>
Credits go to udacity and IBM for providing the opportunity to practice our skills!
