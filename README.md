## Shoes price prediction

### Objective: 
Predicting shoes price for the customers of Zshoes and deploy with the help of flask.

### Problem Statement:
Zshoes.com is one of the famous shoe manufacturers of India and has business in almost every country in Asia and Europe. They are one of the best choices of all the athletics and they make the best shoes for running. Due to pandemic, they are facing a loss as Zshoes are a bit expensive. They want to know the correct price of all types of shoes that they are manufacturing so that they won’t face any loss and at the same time customers also buy the shoes. As a machine learning engineer, we have to build a shoe-price prediction app that can predict the correct shoe price by taking inputs like freight_value,payment_type, etc.

### Feature Details:

order_item_id: Order id of the shoe.

price:price of the shoe(Target)

freight_value: freight_value of the shoe

payment_sequential: Sequence of payment

payment_type:types of payment

payment_installments: Installments of payments

payment_value:Value of payment

### Libraries Used
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Sklearn
- Pickle

### Results
Sucessfully created a Random Forest model for Shoe Price Prediction.

Below are the metrics we got with Random Forest Model

- r2_score: 0.9984951528902581
- MAE: 0.568529809742358
- MSE: 5.300109924564945
- RMSE: 2.302196760610384
