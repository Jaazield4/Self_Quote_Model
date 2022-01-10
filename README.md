# Self_Quote_Model

## Goal
Create a self quote model which potential customers will be able to use on either the company site or another site. This model will use current client information including "location (in form of city and zip code), average energy bill before solar, utility provider, and panel model they choose, to determine; the amount of solar panels their home requires, and their monthly payments. 

## Resources Required
- Jupyter Notebook
- SQL
- Python - Libraries (Pandas, numpy, matplotlip, scikit-learn library)
- Flask (test deployment)
- HTML
- Data gathered from CRM

## Current Stage of Project
Beginning Stage, gathering data and testing potential models. Currently the limitations include that the data is compiled of almost all Laredo customers and a single Utility Provider. Created a quick test model. Because the data is currently limited, a simple linear regression model is used. The model provided to be quite accurate assuming that the utility rate is the average of $0.14. The linear regression model takes in the average energy bill and will provide the number of panels needed for that home. After getting the prediction, I then continued to use the outcome to determine total cost, monthly solar payment, new energy bill, and yearly savings, with simple calculations.

Next step would be to gather more data to include customers from San Antonio and The Valley to make the model able to give the most accurate pricing for each individual. Following step would be to input the data into a SQL server to be stored and called from into our machine learning model. Once the data is ready I will perform an exploratory analysis to find any missing data or outliers. From there I will test different models includeing multiple linear regression, and a random forrest model to determine which provides the most accurate predictions.
