# Combatting Flight Delays

A Small Overview

## Milestone 1

We begin with the first milestone, The bulk. We highlight the 
problem we are attempting to resolve, Where we get our data from, and how we will
actually use our data to solve the problem.

### What are we trying to solve?

In the simplest terms, we aim to solve a problem affecting thousands of people
daily. Flight delays. They cause problems for travellers such as schedule disrupts,
money and time wasting, miss connecting flights etc. It also affects the airline.
They are likely to lose customers due to inefficient service causing customer disloyalty.

### Where will we get our data from?

Our data will be taken from pre-made data sets such as Bureau of Transportation Statistics (BTS)
or Kaggle

### How will we solve it?

In order to predict flight delays, we will look at historical flight data.
Here is a summary of the methods we will use: 

- Data Processing & Cleaning
   - Pandas for handling missing data, filtering and transforming columns
     
- Exploratory Data Analysis (EDA)
   - Matplotlib & Seaborn to visualize the flight delay trends
   - Analyze delays using time of day, day of week, airline and airport
   - Identify correlations
    
- Feature Engineering
   - Create new features like traffic congestion, past delay rates and weather

- Modelling & Evaluation
   - We use Scikit-learn for estimating delays
   - Measure performance with precision and recall

- Visualization Of Results
   - Matplotlib & Seaborn again for charting
   - Tableau or Dash for interactive boards that show predictions and trends

## Milestone 2

Milestone 2 primarily involves creating a video in which we provide a detailed walkthrough of our project, explaining its key components and overall objectives.

## Milestone 3

Milestone consists of 2 parts. 3.1=Data and scripts. 3.2=Final presentaion.

### Milestone 3.1

Milestone 3.1 contains our data and scripts used to predict delays
We look at variables such as:
- FlightDate
- Airline
- Origin
- Destination
- Cancelled
- Diverted
- Departure Time
- Departure Delay (Minutes)
- Wheels off and on
- Arrival Delay

### Milestone 3.2

Milestone 3.2 consists of our final presentation, where we thoroughly go over the entire project, providing in-depth explanations, insights, and any additional details necessary to showcase our work.

### Milestone 4

Milestone 4 consisted of us using a Logistic Regression model as our baseline for the classification task. We evaluated its performance using a confusion matrix and a classification report, which gave us a clear view of the model’s accuracy, precision, recall, and F1-score. These results gave us a solid reference point and helped highlight where there’s room to improve as we move forward. We also created a 2-minute video presentation summarizing our baseline model, key evaluation metrics, and the insights we gained from this initial phase. Finally we created a summary report explaining the baseline models we chose and why additionally, how well each model performed and what we learned from them.

### Milestone 5

For this phase of the project, we applied multiple machine learning models, including Random Forest, Ridge Regression, and Lasso Regression, to better understand and solve our classification problem. We built and tested these models using Python and scikit-learn, and evaluated their performance using key metrics like precision, recall, and ROC curves.
To showcase our results, we designed a scoreboard-style poster highlighting the most important findings and model comparisons in a clear and visual way. We also recorded a 5-minute video presentation where we explained the problem we tackled, the models we used, our results, and ideas for future improvement.

### Conclusion

Conclusion & Future Improvements

Our model showed a strong bias toward predicting “on time” flights, likely due to class imbalance in the dataset. Flight delays are influenced by many uncontrollable factors, making them difficult to predict accurately. However, we did find a clear correlation between delays and peak travel times—such as summer, holidays, and weekends—when flight activity is higher.

To improve our model in the future, we plan to:

1.Handle class imbalance more effectively to improve prediction accuracy for delayed flights.
2.Incorporate additional variables, like weather data, by combining multiple datasets.
3.Explore more advanced models, such as XGBoost, to better capture complex patterns in the data.


# Thank You
## By Orpheas, Marco & Adam

