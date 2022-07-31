# Ford-Car-Price-Analysis

# About Dataset in kaggle

Attribute Information:

1.model - > Ford Car Brands
2.year - >Production Year
3.price - >Price of car in $
4.transmission - > Automatic,Manual, Semi-Auto
5.mileage -> Number of miles traveled
6.fuel_Type -> Petrol,Diesel,Hybrid,Electric,Other
7.tax -> Annual Tax
8.mpg - > Miles per Gallon
9.engineSize - > Car's Engine Size
In this project, we will analyse the sales price of ford carsç

# Data Details

1. The data was taken in kaggle.com

2. In this project, km and hour will be used. Thus, two new columns will be created from exsiting columns such as "mileage" and "mpg".

To convert miles per gallon to km per liter, we divide the "mpg" by 2.352. In he same way, to convert miles to km, we multiply the "mileage" by 1.609

The aim of this convervation is that km and liter are used a lot more instead of miles and gallon.

Therefore, to reach more people, this convervation will be made.

3. Converting values into two decimal and convert km age from float to int. This because no one looks the decimal point of the km age of a car.

4. Correlation tests were made.

5. We draw a boxplot to identify the outliers and drop them.

# Unexpected Situations and Result

1. We did not get needed correlation between variables execpt "price" and "year"

2. Therefore, we cannot make model that predict the ford car prices.

3. We will continue to analyse this data and collect required data to prepare a prediction model.
