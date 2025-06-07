# Project background
This project analyzes a car dataset to explore factors influencing car prices, including data cleaning, exploratory analysis, and building a regression model to predict prices based on features like brand, mileage, and year.

The dataset used in this project is included in the repository itself under the <code>data</code> folder.
It can also be accessed directly at: [kaggle.com/datasets/smritisingh1997/car-salescsv](https://www.kaggle.com/datasets/smritisingh1997/car-salescsv)  
Please note that a Kaggle account may be required to download it from the source.

A <code>requirements.txt</code> file is included to list all necessary Python packages used in the project.

# Methodology
The dataset contains information on various cars, including their price, brand, model, mileage, year of manufacture, engine type, and body type. After cleaning the data, I focused on the most relevant features for the analysis.

In the price distribution, I observed that cheaper cars are more common, and as the price increases, the number of available cars decreases. There was also a peak in the histogram of years, with 2008-manufactured cars having the highest number of cars for sale. In terms of body types, sedans were nearly twice as common as crossovers.

I also found some key correlations. As expected, price has a positive correlation with the year and a negative correlation with mileage. Year and mileage also share a negative correlation. Interestingly, engine volume had little impact on price.

In terms of specific brands and categories, despite being a higher-end brand, Renault had the lowest average price among all the brands in this dataset, while BMW and Mercedes-Benz topped the list with the highest prices. Crossovers and petrol engines were associated with higher average prices, and low-mileage cars were typically more expensive than those with moderate mileage. However, an unexpected trend was that cars with very high mileage also showed a noticeable uptick in price.

Next, I built a linear regression model to predict car prices based on the selected features. The model performed reasonably well, explaining 76% of the variance in the training data and 69% on the test data. This indicates that the model is quite effective but could benefit from further refinement, such as additional features or more advanced techniques.

This analysis is useful for predicting car prices, which could be valuable for car dealerships, helping them estimate the value of cars for sale or resale. It could also assist buyers and sellers in making informed decisions based on the features of a car.

# About the Author
I am Daniel Stefanian, a physics graduate transitioning into data science. I have experience with Python for data analysis, basic machine learning, SQL, advanced Excel, and Tableau. I am a critical thinker with a natural curiosity for uncovering patterns in data. As an autodidact, I am passionate about learning and continuously expanding my skills in the data science field.

You can reach me at: danielstefanian@gmail.com
