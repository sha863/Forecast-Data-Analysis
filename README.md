# Introduction to data

1. Dataset Contains Product, Quantity, Factor, Month and Location Columns with 155 rows where first one is header row.

2. Product Contains 8 distinct categories **(P2,P3,P5,P7,10,P13,P14,P16)**  . 

3. Loctaion Contains 5 distinct categories **(C1,C2,C3,C4,C5)**.

4. Factor Column contains values between (0-17) and 75 % Values are less than 2 with mean 1.47.

5. Quantity Column contains values between (1-19982) and 75 % Values are less than 256.5 with mean 1380.

6. Converted Month column into date column.

# Initial Exploratory Data Analysis

1. Separated data by year and discovered that the trends/divisions are same for both years.

2. A  pair plot was generated for each column of data for further investigation.

3. Sum of quantity is very larhe for location **C5** compared to others.

4. Sum of Quantity is very large for **P3** then **P7** and **P13** compared to others.

5. We have observed something exciting in terms of location and product categories, we will investigate these locations and products further.

6. We shall now conduct EDA for factor.

# Factor Analysis

1. We generated a scatterplot for factor and quantity and further split on locations/products.

2. **C4** and **C5** Locations have only factor 0.

3. Other Locations have mixed factor from 0 to range 17.

4. **P13** has factor more in high range.

# Location and Product Analysis

1.   Each Location has **2 distinct** Products.
2.   **(C5,P3)** has very large mean_quantity compared to others.
3.   **(C2,P10)** has only factor 0.
4.   **(C5, P7) and (C1, P13)** have large mean_quantity compared to others.

# EDA Conclusion
From Above examination Therefore, we will develop a demand projection model for both items at location C5 and predict their quantity for the next 15 months.
