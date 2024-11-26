# Earthquake-Damage-Prediction
Python, Machine Learning, Pandas,  numpy,  Seaborn , Matplotlib ,  Scikitlearn,  Jupyter Notebook


**Overview**

This project focuses on predicting the level of damage to buildings caused by earthquakes in Nepal. Using a dataset collected through surveys conducted by Kathmandu Living Labs and the Central Bureau of Statistics, the project aims to uncover patterns and build predictive models to assist in post-disaster response and planning.


**Features**

**1. Data cleaning and preprocessing:** Handle missing values and prepare data for analysis.

**2. Exploratory data analysis (EDA):** Understand data distribution and relationships through visualizations.

**3. Feature engineering:** Create new variables and process existing ones for better model performance.

**4.Predictive modeling:** Build classification models to predict the damage level of buildings.


**Dataset**

**Details about the dataset used:**

**1. Source:** Survey data from Kathmandu Living Labs and the Central Bureau of Statistics.

**2. Description:** Includes information about building characteristics, construction materials, socio-economic factors, and earthquake impact data.

**3.Target Variable:** damage_grade - a classification of damage levels to buildings.


**Project Workflow**

**1. Data Collection:** Load the dataset from the provided file.

**2. Data Preprocessing:** Handle missing values, encode categorical variables, and normalize features.

**3. Exploratory Data Analysis (EDA):** Generate statistical summaries and visualizations.

**4. Feature Engineering:** Identify and create features relevant to predictive modeling.

**5. Model Training:** Train classification models to predict the building damage grade.

**6.Evaluation:** Evaluate models using metrics such as accuracy, precision, recall, and F1 score.


**EDA:**

![image](https://github.com/user-attachments/assets/453ac5ca-ba7b-489c-971e-61a05172aa4c)


**Comparison for F1 score:** 


![image](https://github.com/user-attachments/assets/6df8b065-3ed0-4c03-b96a-3a96d0467023)



**Top 10 Features:**


![image](https://github.com/user-attachments/assets/bde12e63-d5ef-4e0c-87dd-26456aff3ea1)


**Conclusion**:

**Damage Overview:**
The 2015 Nepal earthquake caused significant damage to buildings, with the majority (56.89%) experiencing medium damage, followed by high damage (33.47%) and low damage (9.64%). The severity of damage tends to become more uniform with an increase in geographical levels, suggesting that location plays a substantial role in determining damage patterns.

**Building Characteristics for Reduced Damage: Specific building features help minimize earthquake impact:**

-Use of reinforced concrete or cement mortar brick superstructures.

-Buildings with either 1 or 3 floors.

-Structures with a height below 3 meters or above 9 meters.

Buildings with a footprint area smaller than 4 square meters or larger than 10 square meters. These characteristics are recommended for enhancing resilience against earthquakes.
Predictive Model Performance: Machine learning techniques, particularly the Extreme Gradient Boosting model, proved effective in predicting building damage. This model, configured with an F1 Score of 74%, identified the top contributing features as geographical location identifiers, building area and height, and other structural factors such as age and family count. These findings reinforce that geographical location (proximity to the epicenter) and structural specifications are pivotal in assessing earthquake risk and potential damage.




