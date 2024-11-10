# Maximizing Revenue for Taxi Cab Drivers through Payment Type Analysis

## Project Overview
In the competitive taxi booking sector, optimizing revenue is essential for drivers' sustainability and satisfaction. This project leverages data-driven insights to explore whether payment methods impact fare pricing. By analyzing the relationship between payment type and fare amount, we aim to identify strategies to enhance revenue for taxi drivers.

## Problem Statement
This project seeks to answer the following question:
> **Is there a relationship between total fare amount and payment type, and can we encourage customers to use payment methods that generate higher revenue for drivers without compromising customer experience?**

## Objective
The primary goal is to run an A/B test to analyze the relationship between fare amounts and payment methods, using Python hypothesis testing and descriptive statistics. We focus on comparing fares paid by credit card versus cash, to determine if payment type influences fare amount.

## Dataset
- **Source**: 2023 Yellow Taxi Trip Data
- **Features**:
  - `tpep_pickup_datetime` and `tpep_dropoff_datetime`: Pickup and drop-off timestamps.
  - `payment_type`: Payment method used for the trip.
  - `fare_amount`: Fare amount of the trip.
  - `trip_distance`: Distance covered during the trip.
  - `duration`: Trip duration (calculated from pickup and drop-off times).
  - And more.

## Exploratory Data Analysis (EDA)
Key data preprocessing and exploratory analysis steps:
- Removed duplicates and null values.
- Filtered out invalid or irrelevant data points.
- Generated distributions for `fare_amount`, `trip_distance`, and `duration`.
- Analyzed the distribution of payment types and trip details based on fare and distance.

## Key Insights
1. **Fare Amount vs. Payment Type**:
   - Mean fare for card payments: `13.61` (±5.95)
   - Mean fare for cash payments: `12.96` (±6.12)
   - Card payments generally have higher fares than cash payments.

2. **Trip Distance vs. Payment Type**:
   - Mean trip distance for card payments: `2.16` miles
   - Mean trip distance for cash payments: `2.02` miles

3. **Customer Payment Preference**:
   - Payment type distribution: Majority of customers prefer to pay by card.

## Methodology
- **Hypothesis Testing**: Conducted statistical tests to evaluate if there's a significant difference in fare amounts based on payment type.
- **Visualization**: Used Matplotlib and Seaborn to plot distributions of fare amounts and trip distances across payment types.

## Results
Based on the analysis:
- **Higher Revenue Potential**: Card payments correlate with slightly higher fare amounts on average.
- **Actionable Insight**: Drivers may benefit from encouraging card payments, as these tend to correlate with longer trips and higher fares.


