# Car-Market-Data-Analysis

## Project Overview
This project analyzes the car market in Australia using detailed data such as car brand, model, price, mileage, engine capacity, and more. The goal is to explore trends, identify popular brands and car types, analyze price trends over time, and compare different car attributes like gearbox, fuel type, and engine capacity. This analysis provides insights into the car market's structure, helping to understand key market dynamics like brand popularity and price distribution.

## Data Source
The dataset used for this analysis was extracted from Kaggle. It contains detailed information on various attributes of cars in Australia, including car price, brand, year, mileage, fuel type, and engine capacity.

## Tools Used
1. Excel: For data cleaning, analysis, and dashboard creation. The pivot tables and visualizations (bar charts, scatter plots, and pie charts) were created in Excel.

## Data Cleaning/Preparation
The following steps were undertaken to prepare the dataset for analysis:

1. Handling Missing Values: Checked for missing values in critical columns (price, brand, kilometers, etc.) and removed any incomplete rows.
2. Creating New Columns: Created the Price Range column to categorize cars into "Budget," "Mid-range," or "Luxury" based on their price, using the formula; =IF(C3<=10000,"Budget",IF(C3<=40000,"Mid-range","Luxury"))
3. Data Inspection and Formatting: Formatted columns (e.g., currency for price, numeric formatting for kilometers, engine capacity) and ensured consistency in categorical variables (e.g., gearbox type).

## Exploratory Data Analysis (EDA)
The exploratory analysis was aimed at answering key questions such as:

1. What are the top brands by average price?
2. What is the relationship between car age and price?
3. What car types are most common in the dataset?
4. How are cars distributed by fuel type and gearbox?
5. Which brands tend to have the highest/lowest mileage?

## Data Analysis
Several pivot tables and charts were created to answer key business questions:

1. Average Price per Brand: Used pivot tables to calculate the average price per brand and created a horizontal bar chart. Incorporated two option buttons (form control) to switch between the top 10 and bottom 10 brands by price.
2. Price Trend over Time (Car Age vs. Price): Created a scatter plot of car age vs. average price to visualize the trend.
3. Engine Capacity by Car Type: Analyzed the top and bottom 5 car types by engine capacity and created a column chart. Utilized the two option buttons to switch between top and bottom 5 car types by engine capacity.
4. Distribution by Price Range: Created a pie chart to show how cars are distributed across "Budget," "Mid-range," and "Luxury" categories.
5. Price by Fuel Type & Gearbox: Analyzed the average price for cars based on their fuel type and gearbox configuration.

Additionally, macros were utilized to automate the process of clearing slicers and filters, making the dashboard more interactive and user-friendly.

## Results

### *1. Price Range: Budget*

  a) Popular Brand: Holden dominates the budget price range, indicating its appeal as an affordable option.
  
  b) Lowest Mileage: Citroen cars tend to have the lowest mileage among budget cars, suggesting relatively newer or well-maintained models.
  
  c) Popular Gearbox: Automatic transmission is the most common among budget cars, indicating ease of driving is a key factor.
  
  d) Popular Car Type: Wagons are the most popular type in the budget segment, showing demand for spacious, versatile vehicles.
  
  e) Fuel Types: Budget vehicles primarily utilize Diesel, Premium Unleaded Petrol, Unleaded Petrol, Liquid Petroleum Gas, and Unleaded Petrol/Electric.
  
  f) Notable Brands in Budget Range: Suzuki, Opel, Proton, Saab, Dodge, Foton, and Mahindra are common budget brands.
  
### *2. Price Range: Luxury*
 
  a) Popular Brand: Toyota is surprisingly popular even in the luxury price range, likely due to high-end models like the Land Cruiser.
  
  b) Lowest Mileage: Cupra offers luxury cars with the lowest mileage, indicating newer cars in this segment.
  
  c) Popular Gearbox: Automatic transmission is overwhelmingly popular among luxury cars.
  
  d) Popular Car Type: Wagons continue to dominate in the luxury segment.
  
  e) Fuel Types: Luxury vehicles utilize a variety of fuel types, including Unleaded Petrol, Premium Unleaded Petrol, Diesel, Unleaded Petrol/Electric, Premium Unleaded/Electric, and Diesel/Electric.
  
  f) Top Brands by Average Price: Aston Martin, Porsche, Land Rover, Mercedes-Benz, and Bentley lead the luxury market.

### *3. Price Range: Mid-range*
 
  a) Popular Brand: Toyota continues to dominate in the mid-range segment, further reflecting its versatility across price categories.
  
  b) Lowest Mileage: GWM cars have the lowest mileage in the mid-range, suggesting newer models or limited use.
  
  c) Popular Gearbox: Automatic transmission is the most common among mid-range cars.
  
  d) Popular Car Type: Wagons are also popular in this category, catering to families and those needing space.
  
  e) Fuel Types: Mid-range vehicles use Unleaded Petrol, Premium Unleaded Petrol, Diesel, Unleaded Petrol/Electric, and Liquid Petroleum Gas.
  
  f) Top Brands by Average Price: Land Rover, BMW, and Porsche are some of the higher-end mid-range brands.

### *4. Gearbox Analysis*

a) All-Wheel Drive (AWD): Audi is the most popular brand, with sedans being the most common car type in this category, largely in the luxury price range.

b) Front-Wheel Drive (FWD): Mini (likely Mini Cooper) is the leading brand, with wagons being the most popular car type.

c) Manual Gearbox: Toyota is the top brand, and hatchbacks are the most common car type.

d) Rear-Wheel Drive (RWD): Mercedes-Benz leads the rear-drive category, with wagons being the most common vehicle type.

### *5. General Observations*
 
Price vs. Car Age: For budget and mid-range cars, prices generally decrease as the cars get older. However, luxury vehicles show a different pattern, with prices consolidating in the first few years before starting to increase as the cars age, possibly reflecting the collector's market for certain high-end models.

## Recommendations

### 1. For Car Buyers:

a) Budget Buyers: Look for brands like Holden and Suzuki for affordable yet reliable options. Consider fuel types like Diesel or Unleaded Petrol for cost savings.

b) Mid-range Buyers: Toyota offers excellent value in the mid-range category, with versatile car types like wagons that suit families and professionals. Land Rover and BMW also offer strong options for buyers looking for a blend of performance and luxury.

c) Luxury Buyers: High-end brands like Aston Martin, Porsche, and Mercedes-Benz offer premium performance and status. Keep in mind that luxury cars may increase in value over time, making them both a lifestyle choice and a potential investment.

### 2. For Dealerships:

a) Stocking Recommendations: Focus on mid-range cars, as they dominate the market and are likely to move quickly. Brands like Toyota are popular across all price categories, making them a safe bet.

b) Marketing Insights: Highlight the low mileage and automatic gearbox features when selling to a broader audience, as these are popular preferences across all price ranges.

### 3. For Sellers:

a) Luxury Sellers: Emphasize unique features like AWD or premium fuel options to differentiate from mid-range options.

b) Budget Sellers: Highlight reliability and fuel efficiency to appeal to cost-conscious buyers.

### 4. For Car Manufacturers:

a) Consider offering more automatic gearbox options, as they dominate in all price ranges, making them highly sought after. Focusing on wagon models might also cater to a large audience. 

## Limitations

1. Data Representation: The dataset might not represent the full Australian car market as it could have gaps or missing brands and models. This could skew the analysis toward certain popular brands.

2. Mileage Data: Mileage data is often inconsistent due to different usage conditions and reporting standards, which could affect the accuracy of brand comparisons based on mileage.

3. Price Trends: The analysis is based on listed prices, which may not represent actual transaction prices. Therefore, price trends might not reflect real-world fluctuations due to factors like negotiations or seasonal discounts

## References

Dataset sourced from Kaggle:(https://www.kaggle.com/datasets/lainguyn123/australia-car-market-data)
