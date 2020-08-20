# Project Summary 
Online Shopper Intention is a classification problem to predict the price range of a phone given its attributes.

# Dataset
The dataset can be found in [Kaggle](https://www.kaggle.com/roshansharma/data).

# Process
1. Data Preprocessing
2. Data Exploration
- General view of the phone market
- Relationship between phone attributes and price
- Attributes of high-priced vs. low-priced phones
3. Model Training using TensorFlow

# Findings
1. RAM has the most effect on phone price. The higher the RAM, the higher the price
2. Other attributes do not have significant effects on phone price. However, high-priced phones do have a slightly better:
- Battery ('battery_power', 'talk_time')
- Camera ('pc', 'px_height','px_width')
- Memory ('int_memory','ram')
