# tuntun-vs-pyaare
ML model predicting laddoo sales at Tuntun Aunty’s shop using inputs like day, weather, festival, shop status, offers, visitor counts, shakes sold, and rumors. Helps forecast daily sales to optimize inventory and marketing in Dholakpur’s local market scenario.

# Laddoo Sales Prediction Model

## Project Overview
This machine learning model predicts daily laddoo sales at Tuntun Aunty’s shop in the fictional town of Dholakpur. It uses various input features such as day of the week, weather, festival occurrence, shop open status, competitor offers, visitor counts, shakes sold at competitor shops, and local rumors to generate accurate sales forecasts.

## Motivation
In small-town retail settings, sales are heavily influenced by external factors like weather, festivals, competitor activity, and local events. This model helps Tuntun Aunty optimize inventory and plan marketing strategies by providing reliable daily sales predictions.

## Features Used
- Day of the week (e.g., Monday, Wednesday)
- Weather conditions (e.g., Sunny, Rainy)
- Festival today? (Yes/No)
- Is Pyaare's shop open? (Yes/No)
- Is Tuntun Aunty's shop open? (Yes/No)
- Is Pyaare giving free offer? (Yes/No)
- Total visitors in Dholakpur
- Visitors at Pyaare's shop
- Visitors at Tuntun Aunty's shop
- Shakes sold at Pyaare's shop
- Presence of kidnap rumor (Yes/No)

## Model Details
The model is built using supervised regression techniques, incorporating feature engineering and encoding for categorical data. It captures complex relationships between local market conditions and laddoo sales, enabling actionable business insights.

## Usage
Provide daily inputs about market conditions and shop status to get predicted laddoo sales for Tuntun Aunty’s shop. This helps in inventory management and promotional planning.

## Example
Input:
- Day: Wednesday
- Weather: Sunny
- Festival today: No
- Pyaare's shop open: Yes
- Tuntun Aunty's shop open: Yes
- Pyaare giving free offer: No
- Total visitors: 535
- Visitors at Pyaare's shop: 445
- Visitors at Tuntun Aunty's shop: 115
- Shakes sold at Pyaare's shop: 854
- Kidnap rumor: No

Output:
- Predicted laddoo sales: 791

## Installation
Clone the repo and install dependencies:
