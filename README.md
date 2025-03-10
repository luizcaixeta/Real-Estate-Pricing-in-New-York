## 🏠 NYC Real Estate Price Prediction

In this project, we used a database from the website kaggle.com for Airbnb in New York. For a more advanced study, the real estate values ​​are related to data not contained in the database, such as: the crime rate in each neighborhood, the proximity of the properties to tourist attractions, subway stations and bus stops, in addition to extracting the number of bedrooms in each property through the name of the listing.

## 📈 Project Objective

- Perform an exploratory data analysis (EDA), demonstrating the main characteristics between the variables and presenting some related business hypotheses.

- Answer the following questions:
  
a) Assuming that a person is thinking about investing in an apartment to rent on the platform, where would be the best place to buy?
b) Do the minimum number of nights and availability throughout the year affect the price?
c) Is there a pattern in the text of the place name for higher-value places?

- Explain how price prediction can be made from the data. Which variables and/or their transformations were used and why? What type of problem are we solving (regression, classification)? Which model best approximates the data and what are its pros and cons? Which model performance measure was chosen and why?

The answer for this questions is avalliable in the _________

🚀 How to Run the Project

1. Clone the repository

2. Install dependencies:

Make sure Python is installed on your machine. Run the following command to install the required libraries

```pip install -r requirements.txt``` 

3. Ensure the following files are in the project directory:

The files are already included in the repository:

. teste_indicium_precificacao

. MTA_Subway_Entrances_and_Exits__2024_20250129

. Bus_Stop_Shelter_20250201

. crimes_por_PTC

. PTC_por_bairros

Data sources:

. 🚇 [NYC Subway Entrances and Exits (2024)](https://data.ny.gov/Transportation/MTA-Subway-Entrances-and-Exits-2024/i9wp-a4ja/about_data)

. 🚌 [Bus Stop Shelters](https://data.cityofnewyork.us/Transportation/Bus-Stop-Shelters/qafz-7myz)

. 📊 [Crime Statistics](https://www.nyc.gov/site/nypd/stats/crime-statistics/historical.page)

. 🗺️ [Neighborhood Division by PTC](https://www.nyc.gov/site/nypd/bureaus/patrol/precincts-landing.page)

4. Run the analysis and prediction:

   ```python main.py```

## 🛠️ Technologies Used

. Python

. Pandas, NumPy (Data manipulation)

. Scikit-learn (Predictive modeling)

. Matplotlib, Seaborn (Data visualization)

