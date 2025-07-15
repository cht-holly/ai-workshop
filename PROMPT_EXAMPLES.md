# Workshop Prompt Examples

## Phase 1: Requirements & Planning

### Prompt 1.1 - Initial Analysis
```
I need to build a data dashboard for visualizing equity prices. I have a CSV file with columns: Date, Ticker, Close for stocks NVDA, AAPL, GOOGL, MSFT.

Requirements for the final dashboard:
- Must display stock price charts with date filtering
- Must calculate and overlay 7-day simple moving average (SMA) using rolling window
- Must show comparison statistics for selected date ranges
- Must handle user interactions for stock selection and date filtering
- Must work with the provided CSV data structure

Technology constraints:
- Use Python with Dash framework for the web interface
- Use Plotly for charting
- Use Pandas for data manipulation

Create a requirements analysis that covers:
1. User stories for the main dashboard features
2. Technical requirements specifying the required functionality
3. Project structure recommendations

The end result should be a clear roadmap for building an interactive dashboard that any developer could follow.
```

### Prompt 1.2 - Technical Planning
```
Based on our dashboard requirements, create a technical implementation plan covering:

Expected final result:
- Interactive web dashboard showing stock price trends
- 7-day SMA overlay calculated using pandas rolling window method
- Date range filtering and stock selection controls
- Statistical summary panel showing key metrics for selected periods

Technical constraints:
- Data source: CSV file with Date, Ticker, Close columns
- SMA calculation: Use pandas rolling(window=7).mean() method
- Chart display: Both original price and SMA lines must be visible simultaneously
- User controls: Date picker and stock dropdown must filter all displayed data

Deliverables needed:
1. System architecture overview showing data flow from CSV to dashboard
2. Component breakdown identifying the main building blocks
3. Development approach with logical implementation phases

Focus on how the components will work together to deliver the required functionality.
```

## Phase 2: Environment Setup

### Prompt 2.1 - Project Initialization
```
Set up the project environment for our equity dashboard.

Required dependencies:
- dash (for web framework)
- plotly (for charting)
- pandas (for data manipulation)
- numpy (for numerical operations)

Expected project outcome:
- Clean, organized project structure suitable for a dashboard application
- All necessary dependencies available for development
- Basic application entry point ready for development

Setup requirements:
1. Create a logical project directory structure
2. Generate requirements.txt with the specified dependencies
3. Create the main application file with basic Dash setup
4. Set up any necessary utility and component directories

The project should be ready for immediate development of the dashboard features.
```

### Prompt 2.2 - Data Loading
```
Create basic data loading functionality for the equity_prices.csv file.

Data structure:
- CSV contains Date, Ticker, Close columns  
- Tickers are: NVDA, AAPL, GOOGL, MSFT

Required functionality:
- Load CSV data into pandas DataFrame
- Basic data preparation for dashboard use

Implementation needs:
1. Create data loading function that reads the CSV file
2. Ensure dates are in proper datetime format
3. Display basic data summary to verify loading worked

This should be straightforward data loading - focus on getting the data ready for the dashboard.
```

## Phase 3: Core Implementation

### Prompt 3.1 - Basic Dashboard
```
Build the foundation of the dashboard with core functionality.

Required dashboard features:
- Stock selection dropdown with all 4 tickers (NVDA, AAPL, GOOGL, MSFT)
- Line chart displaying stock price over time
- Interactive filtering when user selects different stocks

Expected user experience:
- User sees a clean, simple interface
- Dropdown defaults to one of the stocks
- Chart updates immediately when user selects a different stock
- Chart shows clear price trends over time

Technical requirements:
- Use Dash for the web interface
- Use Plotly for chart rendering
- Chart should display Date on x-axis and Close price on y-axis
- Data filtering should happen reactively based on user selection

Create a working dashboard that demonstrates the core interaction between user input and data visualization. Keep the interface clean and focused on the essential functionality.
```

### Prompt 3.2 - Moving Average Feature
```
Add 7-day simple moving average functionality to the dashboard.

Moving average requirements:
- Calculate 7-day SMA using pandas rolling(window=7).mean() method
- Display both original price and SMA on the same chart
- SMA should be visually distinct from the original price line

Expected visual result:
- Chart shows two lines: original stock price and 7-day moving average
- Both lines should be clearly distinguishable (different colors/styles)
- Legend indicates which line is which
- Moving average should smooth out the price fluctuations

Technical implementation:
- Use pandas rolling window calculation
- Both lines share the same x-axis (Date) and y-axis (Price)
- Update existing chart to show both datasets
- Handle the moving average calculation for the selected stock

The result should clearly demonstrate how the moving average smooths the price data and makes trends more visible.
```

### Prompt 3.3 - Date Range Filtering
```
Add date range filtering functionality to the dashboard.

Filtering requirements:
- Allow users to select a specific date range for analysis
- Both the price chart and moving average should update based on selected date range
- Default should show the full available date range

Expected user experience:
- User can select start and end dates
- All visualizations update to show only data within the selected range
- Moving average calculation adjusts to the filtered data

Technical implementation:
- Add date range selector component
- Filter data based on user selection before chart rendering
- Ensure moving average is calculated on filtered data
- Update chart display to show the filtered timeframe

The result should allow users to focus on specific time periods and see how the stock performed and how the moving average behaved during that period.
```

## Phase 4: Enhancement & Polish

### Prompt 4.1 - Summary Statistics
```
Add a summary statistics panel to provide key insights about the selected stock and time period.

Required statistics:
- Total return percentage for the selected period
- Average daily price change
- Highest and lowest prices in the period
- Current price vs. moving average comparison

Expected display:
- Statistics should be clearly organized and easy to read
- Show numerical values with appropriate formatting
- Update automatically when user changes stock or date range

Technical implementation:
- Calculate statistics using pandas functions
- Display statistics in a clear, organized format
- Update statistics panel whenever chart data changes
- Use percentage formatting for returns

The result should give users quick insights into the stock's performance during the selected time period.
```

### Prompt 4.2 - Final Polish
```
Add final touches to make the dashboard more professional and user-friendly.

Visual improvements needed:
- Clean, professional styling and layout
- Proper titles and labels for all components
- Consistent color scheme and spacing
- Responsive design that works well in browser

User experience enhancements:
- Clear instructions or tooltips for user interactions
- Smooth transitions when switching between stocks or date ranges
- Professional-looking presentation suitable for demonstrating to others

Technical polish:
- Clean up any console errors or warnings
- Ensure all functionality works smoothly
- Test the complete workflow from start to finish

The final result should be a polished, professional-looking dashboard that effectively demonstrates stock price analysis with moving averages.
```

## Phase 5: Documentation & Final Steps

### Prompt 5.1 - Documentation
```
Create basic documentation to help others understand and run the dashboard.

Documentation needs:
- Clear README with setup and running instructions
- Brief explanation of what the dashboard does
- Instructions for local development

Required information:
1. How to install dependencies
2. How to run the dashboard locally
3. What features are available
4. Brief explanation of the moving average methodology

Keep documentation practical and focused on getting the dashboard running. The goal is to help someone else quickly understand and use the project.
```

## Troubleshooting Prompts

### When Things Go Wrong
```
I'm getting an error: [paste error message here]

Help me understand and fix this error. Focus on:
1. What's causing this specific error
2. The exact steps to resolve it
3. How to verify the fix worked

Provide a clear solution I can implement immediately.
```

### For Code Review
```
Please review this dashboard code:
[paste code here]

Check for:
- Functionality correctness
- Code clarity and organization  
- Potential improvements

Suggest specific changes to make the code better.
```

## Prompt Tips for Participants

### Effective Prompt Structure:
1. **Context**: What you're working on
2. **Goal**: What you want to achieve  
3. **Constraints**: Technology and methodology requirements
4. **Expected Result**: What the end result should look like

### Good Example:
```
Context: I'm building a Dash dashboard for stock price analysis
Goal: Add 7-day moving average to the existing price chart
Constraints: Use pandas rolling(window=7).mean() method
Expected Result: Chart showing both price line and moving average line with clear visual distinction
```

### Less Effective:
```
Add moving average to my chart
```

### Progressive Approach:
Build functionality step by step:
1. "Create basic price chart"
2. "Add moving average calculation"  
3. "Add date filtering"
4. "Polish the interface"