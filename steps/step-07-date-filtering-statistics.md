# Step 7: Date Filtering & Statistics

**Duration**: 15 minutes  
**Workflow Phase**: Implementation  
**Goal**: Add date range filtering and summary statistics for comprehensive analysis

## Context

Your dashboard shows stock prices with moving averages effectively. Now you'll add the ability to focus on specific time periods and provide summary insights. This enables users to analyze performance over custom date ranges.

## The Prompt Part 1 - Date Filtering

Copy this prompt into your AI agent:

```
Add date range filtering functionality to the dashboard.

Filtering Requirements:
- Allow users to select a specific date range for analysis
- Both the price chart and moving average should update based on selected date range
- Default should show the full available date range

Expected User Experience:
- User can select start and end dates
- All visualizations update to show only data within the selected range
- Moving average calculation adjusts to the filtered data

Technical Implementation:
- Add date range selector component
- Filter data based on user selection before chart rendering
- Ensure moving average is calculated on filtered data
- Update chart display to show the filtered timeframe

The result should allow users to focus on specific time periods (e.g., just January vs. full month) and see how the stock performed and how the moving average behaved during that period.
```

## The Prompt Part 2 - Summary Statistics

After implementing date filtering, use this prompt:

```
Add a summary statistics panel to provide key insights about the selected stock and time period.

Required Statistics:
- Total return percentage for the selected period
- Average daily price change
- Highest and lowest prices in the period
- Current price vs. moving average comparison

Expected Display:
- Statistics should be clearly organized and easy to read
- Show numerical values with appropriate formatting
- Update automatically when user changes stock or date range

Technical Implementation:
- Calculate statistics using pandas functions
- Display statistics in a clear, organized format
- Update statistics panel whenever chart data changes
- Use percentage formatting for returns

The result should give users quick insights into the stock's performance during the selected time period.
```

## Expected Result

You should have:
- **Date range selector**: Interactive component for selecting time periods
- **Filtered visualizations**: Chart and moving average update based on date selection
- **Summary statistics**: Panel showing key performance metrics
- **Integrated experience**: All components work together seamlessly

## Verification

✅ **Check your results:**
- Can you select different date ranges?
- Do the chart and moving average update when you change the date range?
- Are summary statistics displayed clearly?
- Do statistics update when you change stock or date range?
- Are the statistics meaningful and properly formatted?
- Does the complete dashboard provide a comprehensive analysis experience?

## Implementation Steps

1. **Add date filtering** using the first prompt
2. **Test date range selection**: Verify charts update correctly
3. **Add summary statistics** using the second prompt
4. **Test complete workflow**: Change stock, adjust date range, observe statistics
5. **Verify calculations**: Ensure statistics are accurate and meaningful

## Next Step

With full functionality implemented, proceed to **Step 8: Polish & Documentation** to finalize your dashboard.

---
*Date filtering and statistics transform a simple chart into a powerful analysis tool.*