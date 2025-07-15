# Step 6: Moving Average

**Duration**: 10 minutes  
**Workflow Phase**: Implementation  
**Goal**: Add 7-day simple moving average to enhance analysis capabilities

## Context

Your basic dashboard shows stock prices effectively. Now you'll add analytical depth by overlaying a 7-day simple moving average. This is a crucial feature that helps users identify trends and patterns in the price data.

## The Prompt

Copy this prompt into your AI agent:

```
Add 7-day simple moving average functionality to the dashboard.

Context:
- I'm working on my stock dashboard in the app/ folder
- I have a basic dashboard with stock selection and price charts
- Now I want to add moving average analysis

Moving Average Requirements:
- Calculate 7-day SMA using pandas rolling(window=7).mean() method
- Display both original price and SMA on the same chart
- SMA should be visually distinct from the original price line
- Moving average should update when user changes stock selection

Expected Visual Result:
- Chart shows two lines: original stock price and 7-day moving average
- Both lines should be clearly distinguishable (different colors/styles)
- Legend indicates which line is which
- Moving average should smooth out price fluctuations and make trends more visible

Technical Implementation:
- Use pandas rolling window calculation for SMA
- Both lines share the same x-axis (Date) and y-axis (Price)
- Update existing chart to display both datasets
- Handle the moving average calculation for the selected stock
- Ensure proper handling of initial 6 days where full window isn't available

The result should clearly demonstrate how the moving average smooths the price data and makes underlying trends more visible.

Documentation:
Update the CHANGELOG.md file to track this step. Include:
- What was accomplished (7-day moving average implementation)
- Technical approach used (pandas rolling window)
- Visual improvements (dual-line chart with legend)
- Files modified

This helps track the analytical capabilities being added.
```

## Expected Result

You should have:
- **Dual-line chart**: Original price + 7-day moving average
- **Visual distinction**: Different colors/styles for each line
- **Clear legend**: Shows which line is which
- **Trend smoothing**: Moving average shows underlying patterns

## Verification

✅ **Check your results:**
- Are both price and moving average lines visible on the chart?
- Are the lines visually distinct (different colors/styles)?
- Is there a legend identifying each line?
- Does the moving average appear smoother than the original price?
- Do both lines update when you change stock selection?
- Can you see how the moving average helps identify trends?

## Implementation Steps

1. **Add moving average calculation** as suggested by your AI agent
2. **Update the chart**: Ensure both lines display properly
3. **Test with different stocks**: Verify calculations work for all tickers
4. **Examine the trend smoothing**: Notice how MA reveals underlying patterns

## Next Step

With analytical capabilities added, proceed to **Step 7: Date Filtering & Statistics** to add time-based analysis.

---
*Moving averages reveal the signal within the noise of daily price movements.*