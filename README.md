# Automotive Industry Trends Analysis

This project analyzes trends in the automotive industry using SQL queries on a comprehensive car sales dataset. The analysis explores various aspects of the automotive market including pricing, features, fuel efficiency, and ownership patterns.

## Dataset

The dataset (`Exploring Trends in the Automotive Industry.csv`) contains detailed information about cars including:
- Car name and model
- Manufacturing year
- Selling price
- Kilometers driven
- Fuel type
- Seller type
- Transmission type
- Ownership history
- Mileage
- Engine specifications
- Power and torque details
- Seating capacity

## Analysis Areas

The SQL queries (`trends.sql`) explore several key aspects of the automotive market:

1. Price Analysis by Transmission and Ownership
   - Average selling prices for manual transmission cars with first ownership across different fuel types

2. Mileage Performance
   - Top 3 car models with highest average mileage (for cars with more than 5 seats)

3. Price Variation Analysis
   - Models with significant price variations (difference > $10,000 between min and max prices)

4. Performance vs Price Analysis
   - Cars with above-average prices and below-average mileage
   - Price-performance ratio analysis

5. Time-based Analysis
   - Cumulative price trends over years by model
   - Price variations within 10% of market average
   - Year-over-year price changes

6. Market Segmentation
   - Analysis by transmission types
   - Fuel type distribution
   - Ownership patterns

## Key Queries

The analysis includes various SQL techniques:
- Aggregation functions
- Window functions
- Common Table Expressions (CTEs)
- Subqueries
- Joins
- Advanced filtering
- Time-series analysis

## Usage

1. Import the dataset into your SQL database
2. Execute the queries in `trends.sql`
3. Analyze the results to understand various market trends

## Tools Used

- SQL Database
- SQL queries for data analysis
- Data visualization (can be connected to tools like Tableau or Power BI)

## Further Analysis

The queries can be extended to explore:
- Regional price variations
- Fuel efficiency trends
- Market share analysis
- Brand-wise performance comparison
- Customer preferences by segment
