# zomato-food-order-demand-prediction
Zomato Food Order Demand Prediction Using Predictive Analytics
# Zomato Food Order Demand Prediction Using Predictive Analytics

## Project Overview

This project applies predictive analytics to historical Zomato
food-order data to understand demand patterns and support better
delivery and restaurant resource planning.

Food-order demand can vary by date, city, locality, restaurant type, and
other order-related conditions. Forecasting demand can help identify
high- and low-demand periods, plan delivery-partner availability, manage
restaurant capacity, and reduce delivery delays.

## Objectives

-   Analyze historical food-order data and identify demand patterns.
-   Prepare data for predictive modelling.
-   Predict daily food-order demand using a Random Forest Regression
    approach.
-   Compare actual and predicted demand.
-   Visualize demand-related insights using Power BI.
-   Explore how predicted demand can support delivery-resource planning.

## Project Files

``` text
zomato-food-order-demand-prediction/
│
├
├── Zomato food prediction.ipynb
├── zomato.zip
└──zomato food prediction dashboard.pbix        
```



## Dataset

The project presentation describes a structured historical order dataset
containing **12,079 order records**. The listed fields include:

-   Order Date
-   Order Amount
-   Number of Items
-   Delivery Time
-   Order Status
-   Payment Method
-   Delivery Distance
-   Restaurant Type
-   City and Locality
-   Ratings and other restaurant-related attributes

The dataset is supplied separately as `zomato.zip`. Extract it before
running the notebook if the notebook expects the uncompressed data file.

> Dataset note: The exact extracted filename and column names should be
> checked against the contents of `zomato.zip` and the notebook before
> running the project.

## Tools and Technologies

-   Python
-   Jupyter Notebook
-   Pandas and NumPy for data handling
-   Matplotlib / Seaborn for visual analysis (where used in the
    notebook)
-   Scikit-learn for machine learning (where used in the notebook)
-   Random Forest Regression
-   Microsoft Power BI for dashboard visualization

## Methodology

1.  **Data loading:** Load the historical order dataset into the
    notebook.
2.  **Data preparation:** Inspect and prepare the data for analysis and
    modelling.
3.  **Exploratory analysis:** Examine order and demand patterns across
    available dates and locations.
4.  **Feature preparation:** Prepare the input variables used by the
    predictive model.
5.  **Model training:** Use a Random Forest Regression model to predict
    daily food-order demand.
6.  **Evaluation:** Compare predicted demand with actual demand using
    the evaluation steps included in the notebook.
7.  **Visualization:** Present demand insights and
    actual-versus-predicted comparisons in Power BI.

Refer to the notebook for the exact implementation, preprocessing steps,
features, train/test split, and evaluation metrics.

## How to Run the Project

1.  Clone or download this repository.

2.  Extract `zomato.zip` into the location expected by the notebook.

3.  Open the notebook:

    ``` bash
    jupyter notebook "Zomato food prediction.ipynb"
    ```

4.  Run the notebook cells in order.

5.  If a Python package is missing, install the package named in the
    error. Common project libraries include:

    ``` bash
    pip install pandas numpy matplotlib seaborn scikit-learn jupyter
    ```

6.  To view the Power BI dashboard, open the `.pbix` file in Microsoft
    Power BI Desktop.

## Business Impact

Demand forecasts can help a food-delivery platform:

-   Anticipate periods and locations with higher or lower demand.
-   Plan delivery-partner allocation.
-   Manage restaurant capacity.
-   Reduce the likelihood of delivery delays.
-   Improve operational efficiency and customer satisfaction.

The project presentation also describes converting predicted demand into
an estimated rider requirement for delivery-resource planning.

## Results

The project presentation describes the use of a Random Forest Regression
model and Power BI visualizations, including:

-   Actual vs. Predicted Demand
-   Predicted Demand by City

For numerical model scores and exact result values, refer to the
executed notebook outputs. 

## Future Enhancements

-   Evaluate additional regression models and compare their performance.
-   Improve forecasting with more historical data and location-level
    features.
-   Build an automated demand forecasting pipeline.
-   Refresh dashboard insights as new order data becomes available.



