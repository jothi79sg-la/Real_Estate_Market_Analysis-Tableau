# Real Estate Market Analysis-Tableau
##  Project Overview

This project analyzes real estate market data using **Tableau** to understand property pricing, sales performance, market trends, property types, and differences across 
cities.

A single-page interactive dashboard was developed to give real estate stakeholders a consolidated view of key market performance indicators and analytical insights.


##  Business Problem

Real estate stakeholders need to understand how property prices, location, property type, and market time vary across the market.

The objective of this project is to analyze property listing and sales data and develop an interactive Tableau dashboard that can support:

- Property pricing analysis
- City-level market comparison
- Sales performance monitoring
- Property-type analysis
- Market-time analysis
- Data-driven pricing and marketing decisions


##  Project Objectives

- Analyze average listing and sales prices.
- Monitor the number of properties sold.
- Evaluate average days on market.
- Compare sales prices across cities.
- Identify differences in market time by property type.
- Analyze property status distribution.
- Compare price per square foot across cities.
- Identify monthly listing-price trends.
- Translate analytical findings into business insights.

## Dataset

**Dataset:** Real Estate Market Analysis  
**Format:** CSV  
**Records:** 300 properties  
**Fields:** 15

##  Tools & Technologies

- **Tableau** – Data visualization and dashboard development
- **CSV** – Source dataset
- **Tableau Calculated Fields** – KPI and analytical calculations
- **Interactive Filters / Actions** – Dashboard exploration


##  Tableau Calculated Fields

### Sales-to-List Ratio

**[Sale Price] / [Listing Price]**

This measures how closely the final sale price compares with the original listing price.

### Price Per Square Foot

**[Listing Price] / [Square Feet]**

This provides a property-level price-per-square-foot measure for comparison across cities.

##  Dashboard

### Real Estate Market Analysis Dashboard

The dashboard combines **5 KPI cards and 6 analytical visualizations** into a single-page view.

<img width="591" height="391" alt="image" src="https://github.com/user-attachments/assets/6f09d810-475c-4785-8a9e-a77f91a60539" />

### Key Performance Indicators

| KPI | Dashboard Value |
|---|---:|
| Average Listing Price | **$560,061** |
| Average Sales Price | **$568,209** |
| Total Properties Sold | **168** |
| Average Days on Market – Sold Properties | **54.90 days** |
| Sales-to-List Ratio | **99.95%** |

### Dashboard Visualizations

The dashboard contains:

1. **Price Trend** – Monthly average listing-price trend.
2. **Average Sales by City** – Comparison of average sale prices across cities.
3. **Days on Market by Property Type** – Comparison of average market time for sold properties by property type.
4. **Distribution of Status** – Breakdown of Sold, Available, and Pending properties.
5. **Price Per Square Foot** – City-level comparison of the calculated price-per-square-foot measure.
6. **Property Type Distribution** – Distribution of properties across property types.

## Key Insights

### 1. Properties sold close to their listing prices

The dashboard shows a **99.95% Sales-to-List Ratio**, indicating that sold properties in this dataset generally achieved prices very close to their original listing prices.

### 2. Sold properties represent more than half of the dataset

Out of **300 properties**, **168 were sold**, representing approximately **56%** of the dataset.

The remaining properties were:

- **87 Available**
- **45 Pending**

### 3. Average sales prices differ substantially by city

The dataset shows clear variation in average sales prices across cities.

- **Austin** has the highest average sale price at approximately **$620K**.
- **Chicago** has the lowest average sale price at approximately **$417K**.

This indicates that location is an important factor when comparing property market values within this dataset.

### 4. Market time varies by property type

For sold properties, the dashboard shows that:

- **Townhouses** have the highest average days on market at approximately **59 days**.
- **Duplexes** follow at approximately **59 days**.
- **Apartments** average approximately **57 days**.
- **Condos** average approximately **56 days**.
- **Single Family** properties have the lowest average at approximately **42 days**.

This suggests differences in selling time across property types.

### 5. Listing prices fluctuate over time

The monthly price trend shows noticeable variation in average listing prices throughout the analysis period, indicating that the market does not remain at a constant price level.


##  Business Recommendations

Based on the analysis:

### Pricing Strategy
Real estate agents can use city-level sales-price patterns and the sales-to-list ratio to support more competitive listing-price decisions.

### Location-Based Strategy
The substantial difference in average sale prices across cities suggests that location should be considered when developing pricing and marketing strategies.

### Property-Type Strategy
Differences in days on market indicate that marketing strategies may need to be tailored to individual property types.

### Market Monitoring
The dashboard can be updated periodically to monitor changes in listing prices, sales performance, and market time.


## Interactive Tableau Dashboard

**Tableau Public:**  

👉 **[View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/nagajothi/viz/Real_Estate_Market_Analysis_Dashboard/RealEstateDashboard?showOnboarding=true)**

##  Project Outcome

This project demonstrates how Tableau can be used to transform raw real estate data into an interactive analytical dashboard that supports 
**pricing analysis, market comparison, sales monitoring, and business decision-making**.

The project focuses not only on visualization, but also on connecting analytical findings with practical real estate business questions.
