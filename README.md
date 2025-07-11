# Food Delivery Time Prediction

This project predicts food delivery time based on various factors like distance, weather, and traffic conditions. The analysis is done using a Jupyter Notebook and includes data preprocessing, model training, and evaluation.

## Datasets

The dataset used in this project is Food_Delivery_Time_Prediction.csv. It contains the following columns:
Order_ID: Unique ID for each order.

Customer_Location: Latitude and longitude of the customer.
Restaurant_Location: Latitude and longitude of the restaurant.
Distance: Distance between the restaurant and the customer.
Weather_Conditions: Weather conditions at the time of the order.
Traffic_Conditions: Traffic conditions at the time of the order.
Delivery_Person_Experience: Years of experience of the delivery person.
Order_Priority: Priority of the order.
Order_Time: Time of the day the order was placed.
Vehicle_Type: Type of vehicle used for delivery.
Restaurant_Rating: Rating of the restaurant.
Customer_Rating: Rating given by the customer.
Delivery_Time: Time taken for the delivery.
Order_Cost: Cost of the order.
Tip_Amount: Tip given by the customer.

### Prerequisites

You need to have Python and Jupyter Notebook installed. You can install the required libraries using pip:
pip install -r requirements.txt

## How to run
1.Clone the repo:
git clone [https://github.com/your_username/your_repository_name.git](https://github.com/your_username/your_repository_name.git)

2.Navigate to the project directory:
cd your_repository_name

3.Open the Jupyter Notebook:
jupyter notebook food_deilveryPART2.ipynb

## Models
The following models were used for prediction:

Gaussian Naive Bayes

K-Nearest Neighbors (KNN)

Decision Tree Classifier

## Results
The models were evaluated based on accuracy, precision, recall, and F1-score. The K-Nearest Neighbors model with the best K value performed the best.
