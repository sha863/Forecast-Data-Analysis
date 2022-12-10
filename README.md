# Introduction to data

1.  Data Contains Product, Quantity, Factor, Month and Location Columns with 155 rows where first one is header row.

2. Product Contains 8 distinct categories **(P2,P3,P5,P7,10,P13,P14,P16)**  . 

3. Loctaion Contains 5 distinct categories **(C1,C2,C3,C4,C5)**.

4. factor Column contains values between (0-17) and 75 % Values are less than 2 with mean 1.47.

5. Quantity Column contains values between (1-19982) and 75 % Values are less than 256.5 with mean 1380.

6. Converted Month column into date column.

# Initial Exploratory Data Analysis

1. Tried to split out data yearwise found out that the trends/divisions are similar in both the years.

2. ploted pair plot for each column in the data for further analysis.

3. Sum of quantity is very much for location **C5**.

4. Sum of Quantity is very much for **P3** then **P7** and **P13**.

5. Now we found something intersting in terms of location and product categories and we will further dig down in these locations and Products

6. Now we will do EDA for factor.

# Factor Analysis

1. We created a scatterplot for factor and quantity and further brokedown on locations.

2. **C4** and **C5** Locations have factor 0.

3. Other Locations have mixed factors greater than 1 to range 17.

4. **P13** have factors more in high range.

# Location and Product Analysis

1.   Each Location has **2 distinct** Products.
2.   **(C5,P3)** has very huge mean_quantity.
3.   **(C2,P10)** have factors 0.
4.   **(C5, P7) and (C1, P13)** have high mean_quantity.

# EDA Conclusion
From Above analysis Location C5 seems intersting hence we will create demand forecast model for both the products on same location and will predict quantity for next 15 months.
