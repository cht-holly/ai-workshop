# Step 4: Data Loading

**Duration**: 5 minutes  
**Workflow Phase**: Implementation  
**Goal**: Load and prepare stock data for dashboard use

## Context

Your project structure is ready. Now you need to load the stock price data and make it available to your dashboard. This step creates the data foundation for all visualizations.

## The Prompt

Copy this prompt into your AI agent:

```
Create data loading functionality for the equity_prices.csv file.

Data Structure:
- CSV contains Date, Ticker, Close columns  
- Tickers are: NVDA, AAPL, GOOGL, MSFT
- Dates should be chronological
- Close prices are positive numbers

Requirements:
- Load CSV data into pandas DataFrame
- Ensure dates are properly formatted for visualization
- Prepare data for dashboard consumption
- Display basic data summary for verification

Implementation Tasks:
1. Create data loading function that reads the CSV file
2. Convert date strings to proper datetime format
3. Ensure data is sorted chronologically
4. Display summary information (data shape, date range, sample rows)

Note: Use the sample data file provided in the workshop: sample-data/equity_prices.csv

The data loading should be robust and provide clear feedback about what was loaded.
```

## Expected Result

You should have:
- **Data loading function**: Reads CSV and returns clean DataFrame
- **Date formatting**: Proper datetime objects for plotting
- **Data summary**: Information about what was loaded
- **Verification output**: Sample rows and basic statistics

## Verification

✅ **Check your results:**
- Does the data loading function successfully read the CSV?
- Are dates converted to datetime format?
- Is the data sorted by date?
- Can you see a sample of the loaded data?
- Do you have all 4 tickers (NVDA, AAPL, GOOGL, MSFT)?

## Implementation Steps

1. **Copy the sample data** to your project directory
2. **Create the data loading function** as suggested by your AI agent
3. **Test the function**: Run it and verify the output
4. **Check the data**: Ensure you have the expected stocks and approximately one month of data (January 3 - February 2, 2023)

## Next Step

With data loading working, proceed to **Step 5: Basic Dashboard** to create your first visualization.

---
*Good data loading is the foundation of reliable dashboards.*