# Step 3: Project Setup

**Duration**: 5 minutes  
**Workflow Phase**: Implementation  
**Goal**: Create organized project structure and install dependencies

## Context

You have a clear plan. Now it's time to set up your development environment. This step creates the foundation for your dashboard development.

## The Prompt

Copy this prompt into your AI agent:

```
Set up the dashboard project structure inside the app/ folder.

Context:
- I'm working in a workshop repository with an app/ folder for development
- All dashboard files should be created inside the app/ directory
- The app/ folder already exists and is ready for development

Required Dependencies:
- dash (for web framework)
- plotly (for charting)
- pandas (for data manipulation)
- numpy (for numerical operations)

Tasks:
1. Create a main application file (app.py) inside the app/ folder with basic Dash setup
2. Create a requirements.txt file inside the app/ folder with the specified dependencies
3. Set up any necessary subdirectories inside app/ for organization (components, utils, etc.)
4. Ensure the basic Dash application can run successfully

Focus on creating a clean foundation inside the app/ folder that's ready for dashboard development.

Documentation:
Update the CHANGELOG.md file to track this step. Include:
- What was accomplished (project structure setup)
- Files created or modified (app.py, requirements.txt, etc.)
- Dependencies installed
- Next steps planned

This helps maintain context and progress throughout the workshop.
```

## Expected Result

You should have:
- **app/app.py**: Main Dash application file
- **app/requirements.txt**: With dash, plotly, pandas, numpy dependencies  
- **app/ subdirectories**: For components, utilities, etc.
- **Working application**: Basic Dash app that can run

## Verification

✅ **Check your results:**
- Is there an app/app.py file with basic Dash setup?
- Is there an app/requirements.txt with all required dependencies?
- Are there subdirectories inside app/ for organizing code?
- Can you run `pip install -r app/requirements.txt` successfully?
- Does the basic Dash app start when you run `python app/app.py`?

## Implementation Steps

1. **Create the app structure** as suggested by your AI agent (inside the app/ folder)
2. **Install dependencies**: Run `pip install -r app/requirements.txt`
3. **Test basic setup**: Run `python app/app.py` to ensure Dash starts correctly
4. **Verify**: Check that you can access the basic dashboard in your browser

## Next Step

With your project set up, proceed to **Step 4: Data Loading** to connect your CSV data.

---
*A well-organized project structure makes development smoother and more maintainable.*