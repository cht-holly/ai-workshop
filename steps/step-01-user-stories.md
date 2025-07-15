# Step 1: Define User Stories

**Duration**: 5 minutes  
**Workflow Phase**: User Stories  
**Goal**: Define clear requirements for our stock dashboard

## Context

You're starting a new project to build a stock price dashboard. Before writing any code, you need to define what the dashboard should do from a user's perspective. This helps ensure you build something valuable and focused.

## The Prompt

Copy this prompt into your AI agent:

```
I need to create user stories for a stock price dashboard application. 

Context:
- I have stock price data for NVDA, AAPL, GOOGL, MSFT in a CSV file
- The data contains Date, Ticker, and Close price columns
- I want to build an interactive web dashboard for visualizing this data

Requirements:
- Users should be able to view stock price trends
- Users should be able to analyze price patterns with moving averages
- Users should be able to filter and compare different time periods
- Users should be able to get summary insights about stock performance

Create 5 user stories in the format: "As a [user type], I want [functionality] so that [benefit]"

Focus on the core value each feature provides to users.
```

## Expected Result

You should receive 5 clear user stories that cover:
1. Basic stock price visualization
2. Moving average analysis
3. Stock selection/comparison
4. Date filtering
5. Summary statistics or insights

Example format:
- "As a stock analyst, I want to view price charts so that I can identify trends"
- "As an investor, I want to see moving averages so that I can spot buy/sell signals"

## Verification

✅ **Check your results:**
- Do you have exactly 5 user stories?
- Does each story follow the "As a..., I want..., so that..." format?
- Do the stories cover visualization, analysis, filtering, and insights?
- Are the benefits clear and valuable?

## Next Step

Once you have clear user stories, proceed to **Step 2: Implementation Plan** to break down how you'll build these features.

---
*Remember: Good user stories drive good software. Take time to get these right!*