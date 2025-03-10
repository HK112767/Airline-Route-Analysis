# Airline-Route-Analysis

## Objective
The goal of this analysis is to identify the busiest and most profitable round-trip airline routes based on real-world flight data. Additionally, we calculate the break-even point for recommended routes and suggest key performance indicators (KPIs) for future success tracking.

## Steps Taken

### 1. Data Preprocessing
- Loaded datasets: `tickets.csv`, `flights.csv`, and `airportcodes.csv`.
- Converted flight dates to a standardized datetime format.
- Removed all cancelled flights from the dataset.

### 2. Data Quality Checks
- Identified missing values, duplicate entries, and potential outliers.
- Ensured only flights from medium and large airports were included in the analysis.

### 3. Data Merging
- Merged airport code data to classify airport sizes.
- Defined round-trip routes by combining origin and destination airports.

### 4. Busiest Routes Identification
- Grouped flights by round-trip routes and calculated the number of flights per route.
- Selected the top 10 busiest routes based on flight frequency.
- Visualized the busiest routes using a bar plot.

### 5. Profitability Analysis
- Converted necessary columns to numeric format.
- Calculated revenue based on ticket prices, occupancy rates, and baggage fees.
- Determined operational costs, including fuel, maintenance, and airport fees.
- Accounted for additional delay costs for flights delayed beyond 15 minutes.
- Identified the top 10 most profitable routes based on net revenue.
- Visualized profitability insights using bar charts.

### 6. Investment Recommendation
- Selected the 5 most profitable routes for investment.
- Calculated the break-even number of flights required to recover the $90M aircraft cost.
