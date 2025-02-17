# Car Crash Analysis


## **Project Overview**
The goal of this project was to identify key factors contributing to severe car crashes and provide insights to improve road safety and reduce fatalities. We focused on analyzing a dataset of traffic accidents with variables such as accident severity, crash type, violations, weather, and time-related factors.

## **Business Understanding**
We aimed to answer the following key questions:
- Which variables are most strongly linked to severe crashes?
- How can emergency responders prioritize cases more effectively?
- How can law enforcement and policymakers improve road safety based on violations and crash data?

Our analysis is intended to help improve safety on the roads, enhance emergency response strategies, and inform law enforcement and policy decisions.

## **Data Understanding**
The dataset includes several key variables:
- **Severity**: Whether the accident was fatal or nonfatal (binary target variable)
- **ViolCat**: Category of violation (e.g., DUI, speeding)
- **Crash Type**: Type of crash (e.g., rear-end, head-on)
- **Weather and Daylight**: Weather conditions and whether it was daylight or not
- **Time Factors**: Weekday, Month

We conducted exploratory data analysis and visualizations to identify trends and correlations in the data.

## **Data Preparation**
Data preparation included the following steps:
- Transforming categorical variables (e.g., violations, crash type) into dummy variables for modeling
- Ensuring all variables were in the proper format for modeling (e.g., numeric and binary variables)
- Handling missing data where applicable

## **Modeling**
We employed several machine learning models to predict accident severity:
- **Logistic Regression**: Identified significant predictors of severe crashes, such as violations like DUI and speeding, especially on highways.
- **Naive Bayes**: Provided a simple probabilistic approach with 83% accuracy.
- **Classification Tree**: Highlighted important features like violations and daylight conditions.
- **Random Forest**: Improved classification accuracy to 72% by handling unbalanced data better.
- **K-Nearest Neighbors (KNN)**: Achieved 87% accuracy, though it struggled with the rare positive class due to data imbalance.

## **Evaluation**
Our models helped us identify the most important factors influencing severe car crashes. The key findings were:
- Violations such as DUI and speeding are strong predictors of severe crashes.
- The conditions of the road (e.g., highways) and weather (e.g., clear weather) also significantly impact the severity of accidents.
  
These insights can help in improving traffic safety, prioritizing emergency responses, and developing better enforcement strategies.

## **Deployment**
- **Final Report**: We provided a non-technical summary with visualizations to communicate the results effectively.
- **Recommendations**: Focus on high-risk violations (DUI, speeding) and road conditions (e.g., highways) to improve traffic safety.

## **Tools and Technologies**
- R (for data analysis, visualization, and modeling)
- Logistic Regression, Naive Bayes, Decision Trees, Random Forest, KNN

## **Key Insights and Recommendations**
- Focus law enforcement on high-risk behaviors such as DUI and speeding, particularly on highways.
- Improve road safety by monitoring weather conditions and promoting safety measures for driving in non-daylight conditions.
