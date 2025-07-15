# Step 5: Basic Dashboard

**Duration**: 10 minutes  
**Workflow Phase**: Implementation  
**Goal**: Create interactive dashboard with stock selection and price visualization

## Context

You have data loading working. Now you'll build the core dashboard functionality: displaying stock price charts with interactive stock selection. This demonstrates the fundamental user interaction pattern.

## The Prompt

Copy this prompt into your AI agent:

```
Build the foundation of the dashboard with core functionality.

Context:
- I'm working in the app/ folder for all dashboard development
- I have a data loading function from Step 4
- All dashboard code should be created inside the app/ folder

Required Features:
- Stock selection dropdown with all 4 tickers (NVDA, AAPL, GOOGL, MSFT)
- Line chart displaying stock price over time
- Interactive filtering when user selects different stocks

Expected User Experience:
- User sees a clean, simple interface
- Dropdown defaults to one of the stocks
- Chart updates immediately when user selects a different stock
- Chart clearly shows price trends over time

Technical Requirements:
- Use Dash for the web interface
- Use Plotly for chart rendering
- Chart displays Date on x-axis and Close price on y-axis
- Data filtering happens reactively based on user selection
- Use the data loading function from Step 4
- Update the app/app.py file with the dashboard functionality

Create a working dashboard that demonstrates the core interaction between user input and data visualization. Keep the interface clean and focused on essential functionality.

Documentation:
Update the CHANGELOG.md file to track this step. Include:
- What was accomplished (basic interactive dashboard)
- Features implemented (dropdown, chart, interactivity)
- Files created or modified
- Current functionality status

This helps maintain context about the dashboard's evolution.
```

## Expected Result

You should have:
- **Interactive dropdown**: Lists all 4 stock tickers
- **Price chart**: Clean line chart showing stock price over time
- **Reactive updates**: Chart changes when user selects different stock
- **Professional appearance**: Clean, readable interface

## Verification

✅ **Check your results:**
- Can you select different stocks from the dropdown?
- Does the chart update when you change the selection?
- Is the price trend clearly visible for each stock?
- Are the axes properly labeled (Date, Price)?
- Does the interface look clean and professional?

## Implementation Steps

1. **Create the basic dashboard** as suggested by your AI agent
2. **Test the dropdown**: Try selecting different stocks
3. **Verify chart updates**: Ensure the visualization changes correctly
4. **Check all tickers**: Test that all 4 stocks display properly

## Next Step

With basic interactivity working, proceed to **Step 6: Moving Average** to add analytical capabilities.

---
*Interactive dashboards come alive when users can explore the data themselves.*