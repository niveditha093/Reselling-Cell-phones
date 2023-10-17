# Reselling-Cell-phones
Building Linear Regression Model and Elaborate Data Analysis using Python


**Business Context:**
The market for used and refurbished mobile devices has undergone significant growth in recent years, projected to reach a value of $52.7 billion by 2023, driven by a compound annual growth rate (CAGR) of 13.6% from 2018 to 2023. This expansion is attributed to heightened demand for cost-effective alternatives to new models. Used devices not only offer substantial savings to consumers and businesses but also come with additional benefits, such as warranties and insurance options. Third-party vendors, like Verizon and Amazon, further enhance the appeal of refurbished devices by providing enticing offers. Moreover, the environmental impact is minimized as device longevity is maximized through the second-hand trade. The COVID-19 pandemic has also accelerated this trend, as consumers prioritize essential purchases over discretionary spending.

**Objective:**
To harness the burgeoning potential of this thriving market, ReCell, a forward-thinking startup, has enlisted the expertise of a data scientist. The primary goal is to leverage machine learning to devise a dynamic pricing strategy for used and refurbished mobile devices. This entails analyzing the available data and constructing a linear regression model capable of accurately predicting the pricing of these devices. Furthermore, the model aims to pinpoint the key factors that exert a substantial influence on pricing within this dynamic market.

**Data Description:**
The data contains the different attributes of used/refurbished phones and tablets. The data was collected in the year 2021. The detailed data dictionary is given below.

brand_name: Name of manufacturing brand
os: OS on which the device runs
screen_size: Size of the screen in cm
4g: Whether 4G is available or not
5g: Whether 5G is available or not
main_camera_mp: Resolution of the rear camera in megapixels
selfie_camera_mp: Resolution of the front camera in megapixels
int_memory: Amount of internal memory (ROM) in GB
ram: Amount of RAM in GB
battery: Energy capacity of the device battery in mAh
weight: Weight of the device in grams
release_year: Year when the device model was released
days_used: Number of days the used/refurbished device has been used
normalized_new_price: Normalized price of a new device of the same model in euros
normalized_used_price: Normalized price of the used/refurbished device in euros

**Data Insights:**
* Market Diversity:

>* The refurbished phone market is highly diverse, with 34 brands available. This diversity caters to a wide range of consumer preferences.

* Operating System Dominance:

>* Android OS is the most prevalent, accounting for 93% of the refurbished phones. This indicates a strong preference for the Android platform in the refurbished market.

*  Usage Duration:

> * On average, people tend to use their refurbished phones for approximately 2 years, equivalent to around 675 days. This insight is valuable for understanding the product life cycle and consumer behavior.

*  Price Trends:

> * The mean normalized used price is lower than the mean normalized new price, affirming the expected price reduction for used phones compared to new ones.

*  Device Specifications Impact Pricing:

> * Several device specifications, such as screen size, camera megapixels, battery capacity, RAM, and release year, exhibit strong positive correlations with phone prices. This underscores the significance of these specifications in determining pricing strategies.

**Linear Model Insights:**

*  Model Performance:

>* Our linear regression model is a powerful tool for predicting the prices of refurbished phones. It explains approximately 83.6% of the price variance.

>* The model performs well on both the training and test datasets, indicating robust predictive capabilities without overfitting.

*  Predictive Factors:

>* Several device characteristics significantly influence phone prices. Notably, screen size, camera megapixels, battery capacity, RAM, and release year exhibit strong positive correlations with price.

>* We can use these factors to estimate phone prices more accurately, enhancing decision-making for pricing strategies.

*  Data Quality Matters:

>* Data preprocessing and handling missing values have positively impacted the model's performance. It's crucial to invest in data quality for accurate predictions.

*  Actionable Recommendations:

>* Leverage the model to optimize pricing strategies: Utilize the model's predictive power to set competitive and dynamic prices for refurbished phones.

>* Continuously monitor device specifications: Keep an eye on key features like screen size, camera quality, battery capacity, and RAM, as they significantly impact pricing.

>* Consider data quality improvements: Ensure data is clean, with outliers treated appropriately, to maintain the model's accuracy and reliability.

In summary, our linear regression model is a valuable asset for predicting refurbished phone prices accurately. By focusing on the key predictors and maintaining data quality, we can make more informed pricing decisions in a dynamic and competitive market.
