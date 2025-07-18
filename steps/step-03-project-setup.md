# Step 3: Project Setup

**Duration**: 5 minutes  
**Workflow Phase**: Implementation  
**Goal**: Create organized project structure and install dependencies

## Context

You have a clear plan. Now it's time to set up your development environment. This step creates the foundation for your dashboard development.

## The Prompt

Copy this prompt into your AI agent:

```
Set up the dashboard project structure inside the app/ folder and get the app running NOW.

Context:
- I'm working in a workshop repository with an app/ folder for development
- All dashboard files should be created inside the app/ directory
- I MUST have a working Dash app running in my browser by the end of this step

Required Dependencies:
- dash (for web framework)
- plotly (for charting)
- pandas (for data manipulation)
- numpy (for numerical operations)

CRITICAL REQUIREMENTS - YOU MUST COMPLETE ALL OF THESE:
1. Create a Python virtual environment and activate it
2. Create app/requirements.txt with the specified dependencies
3. Install all dependencies using pip
4. Create app/app.py with a basic Dash application that includes debug=True
5. ACTUALLY RUN the application using python app/app.py
6. VERIFY the app is accessible at localhost:8050 in the browser
7. CONFIRM the app shows a basic "Hello World" or dashboard title
8. ENSURE the app stays running for future development steps

MANDATORY: The app MUST be running and accessible before you mark this step complete. Test it in your browser. Do not proceed to any other step until you can successfully view the running Dash application.

Documentation:
Update CHANGELOG.md to confirm the app is running and accessible at localhost:8050.
```

## Expected Result

You should have:
- **Virtual environment**: Activated Python environment
- **app/app.py**: Main Dash application file with debug=True
- **app/requirements.txt**: With dash, plotly, pandas, numpy dependencies  
- **Running application**: Basic Dash app at localhost:8050 with auto-reload

## Verification

✅ **Check your results:**
- Is the virtual environment activated?
- Is there an app/app.py file with basic Dash setup and debug=True?
- Is there an app/requirements.txt with all required dependencies?
- Can you run `pip install -r app/requirements.txt` successfully?
- Does the app start and show "Hello World" at localhost:8050?
- Does the app auto-reload when you make changes to app/app.py?

## Implementation Steps

1. **Set up virtual environment** as suggested by your AI agent
2. **Activate the environment** and install dependencies with `pip install -r app/requirements.txt`
3. **Start the app**: Run `python app/app.py` 
4. **Verify auto-reload**: Open localhost:8050, then modify app/app.py and save to see if it refreshes
5. **Keep it running**: Leave the app running for the remaining steps

## Next Step

With your project set up, proceed to **Step 4: Data Loading** to connect your CSV data.

---
*A well-organized project structure makes development smoother and more maintainable.*