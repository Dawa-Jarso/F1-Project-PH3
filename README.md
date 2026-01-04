Project by Dawa Jarso
![F1 image](https://car-images.bauersecure.com/wp-images/177956/1752x1168/front_qtr_lh_v001.jpg?mode=max&quality=90&scale=down)

# Project Title: Formula 1 Race Performance Prediction

## Overview
This project focuses on analyzing and predicting the performance of Formula 1 drivers and teams based on historical race data. By leveraging various machine learning models, the goal is to provide insights that can help F1 teams optimize their strategies and improve race outcomes.

## Business and Data Understanding
### Stakeholder Audience
The primary stakeholders for this project include:
- **Team Managers**: Interested in optimizing race strategies, driver pairings, and pit stop timings based on predicted race outcomes.
- **Sponsors**: Require insights into driver and team performance to make informed sponsorship decisions.
- **Sports Analysts**: Utilize predictive models to provide in-depth analysis and forecasts for upcoming races.
- **F1 Enthusiasts**: Enjoy data-driven insights and predictions about their favorite teams and drivers.

### Dataset Choice
The dataset used in this project includes detailed records from past Formula 1 races, spanning multiple seasons. The data was sourced from [mention source, e.g., Kaggle, official F1 data repository, etc.]. Key features in the dataset include:
- **Grid Position**: The starting position of the driver.
- **Race Results**: The final position of the driver at the end of the race.
- **Driver and Constructor Information**: Nationalities, team names, and historical performance.
- **Race Details**: Such as race name, year, round, and location.
- **Lap Times and Speeds**: Including fastest laps and average speeds.

This dataset was chosen because it provides a comprehensive view of all the factors that influence race outcomes, making it ideal for building predictive models.

## Modeling
### Data Preprocessing
Data preprocessing involved several key steps:
- **Handling Missing Values**: Missing data was addressed by either imputing values or removing records where appropriate.
- **Feature Engineering**: New features were created, such as calculating average speed per lap or the difference between grid position and final position.
- **Data Transformation**: Categorical features like driver names and constructor names were encoded using OneHotEncoder, and numeric features were scaled using StandardScaler.

### Model Selection
Several models were evaluated to determine the best approach for predicting race outcomes:
- **Logistic Regression**: Chosen for its simplicity and interpretability, suitable for binary and multi-class classification.
- **Decision Tree**: Applied for its ability to handle non-linear relationships and provide a visual interpretation of decision rules.
## Evaluation
The performance of the models was evaluated using the following metrics:
- **Initial Model**: 
  - Accuracy: 85%
  - Precision, Recall, F1-Score for each class
- **Optimized Model**:
  - Accuracy: 98%
  - Precision, Recall, F1-Score for each class

The optimized model showed a significant improvement over the initial model, with higher accuracy and better performance metrics across all classes. 

## Conclusion
Decision tree classification model demonstrates a notable enhancement in performance compared to the initial model. Key findings include:
- **Improved Accuracy**: The optimized model achieved a high accuracy of 98%, reflecting its effectiveness in making reliable predictions.
- **Enhanced Metrics**: Precision, recall, and F1-score improved significantly across all classes, especially for Class 2, indicating strong model performance.

**Recommendations:**
1. **Use Decision tree Model**: Given its superior performance, the optimized model should be used for predictions.
3. **Validate and Test Further**: Perform additional validation on new datasets to ensure robustness.
4. **Class 2 (Top Finishers)**: The model perfectly predicts the top finishers, suggesting a strong understanding of the factors leading to success. Continue to focus on the key variables influencing top performance.
