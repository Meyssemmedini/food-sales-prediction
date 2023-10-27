# food-sales-predictions
## Subtitle: Revealing Trends and Future Patterns in Sales Data

Author: Meyssem Medini

### Business Problem
- The project addresses the challenge of predicting future food sales for various items at different stores.

### Data
- The dataset, sourced from Kaggle [https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view], includes 8523 entries, offering insights into sales patterns.

## Methods

Data Preparation
- Addressed missing data for Item_Weight and Outlet_Size.
- Ensured consistency in categorical values and data points.

Data Visualization
- Utilized exploratory visualizations (histograms, boxplots, heatmap) for insights.
- Employed explanatory visualizations (pie chart, bar chart, scatterplot, count plot, treemap) for in-depth analysis.

Machine Learning
- Loaded and preprocessed data, splitting it into training and test sets.
- Built a linear regression model and assessed its performance.
- Trained and evaluated a regression tree model.
- Tuned the regression tree model for optimal performance.

Analysis
- Presented findings, insights, and performance metrics from the machine learning models.

## Results
### Visual 1: Total Sales by Item Type
![Total Sales (Scaled by 1000) by Item Type](https://github.com/Meyssemmedini/food-sales-predictions/assets/145705523/eff8d76d-f96f-429c-b0c7-fbf9d5dd6032)
This visualization displays the total sales, scaled by 1000, categorized by different item types. It provides an overview of the distribution of sales across various product categories, offering insights into the relative performance of each item type in the dataset.

## Model Overview:

The final model is a tuned regression tree, chosen for its enhanced predictive capabilities in sales forecasting.
Key Metrics:
- The most crucial metrics include R2 for overall model fit and RMSE for error assessment.

Performance Assessment:
- The model's high R2 signifies strong explanatory power, capturing a significant portion of the variance in sales.
- Additionally, the low RMSE indicates accurate predictions, aligning well with the business goal of precise sales forecasting.

## Recommendations

Continuous Monitoring:
- Implement a system for ongoing monitoring of model performance. Regularly assess its accuracy against new data to ensure continued reliability.

Explore Ensemble Methods:
- Consider exploring ensemble methods, like bagging or boosting, to potentially further improve predictive accuracy and robustness.

Understand Key Factors:
- Dive into which factors most influence sales for better decision-making.

Consider External Factors:
- Think about including external factors, such as economic indicators or seasonal trends, to adapt the model to changing business conditions.

Make Results Clear:
- Create straightforward visuals to help stakeholders easily understand and use model predictions.

## Limitations & Next Steps

### Limitations:

Data Availability:
- The model's effectiveness heavily relies on the availability and quality of historical sales data. Incomplete or inconsistent data may impact predictions.

External Factors:
- The model may not account for unforeseen external factors influencing sales, such as sudden market changes or economic shifts.

Assumption of Stationarity:
- If the sales data doesn't follow a consistent pattern over time (non-stationary), the model might struggle, leading to potential inaccuracies.

###Next Steps:

Enhanced Data Collection:
- Improve data collection processes to ensure a more comprehensive and accurate dataset for training the model.

Dynamic Model Updating:
- Develop mechanisms for the model to adapt to changing external factors, ensuring it remains relevant in evolving business environments.

Advanced Techniques:
- Explore more advanced modeling techniques that can capture complex patterns and relationships within the data.

Collaboration with Experts:
- Seek input from industry experts to refine the model further and incorporate domain-specific insights.

Regular Model Audits:
- Establish a schedule for regular model audits to identify and address potential limitations proactively.

##For Further Information
For any additional questions or inquiries, please contact [medinimeyssem58@gmail.com].
