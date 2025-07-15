# AI-Powered Development Workshop: Building with Agentic AI

## Workshop Goal
Teach developers how to leverage agentic AI (GitHub Copilot Agent Mode) to build a complete application through structured, iterative prompting that mirrors professional software development practices.

## What Participants Will Build
A Python data dashboard using Dash that visualizes equity price data for NVDA, AAPL, GOOGL, and MSFT. The dashboard will include interactive charts, filtering capabilities, and performance metrics.

## Required Tools
- **GitHub Copilot Agent Mode** (VS Code extension)
- **VS Code** (latest version)
- **Python 3.8+** with pip
- **Git** for version control
- **Sample dataset**: equity_prices.csv (provided)

## Workshop Flow: The 5-Phase Approach

### Phase 1: Requirements & Planning (10 minutes)
**Learning Goal**: How to articulate clear requirements and let AI help with planning
- Participants prompt the agent to analyze requirements
- Generate user stories and acceptance criteria
- Create technical architecture outline

### Phase 2: Environment Setup (10 minutes)
**Learning Goal**: Systematic environment preparation with AI assistance
- Project structure creation
- Dependency management
- Configuration setup
- Data validation

### Phase 3: Core Implementation (25 minutes)
**Learning Goal**: Iterative development with context building
- Data loading and transformation
- Basic dashboard creation
- Interactive components
- Styling and layout

### Phase 4: Enhancement & Testing (10 minutes)
**Learning Goal**: Refinement and quality assurance
- Feature enhancements
- Error handling
- Basic testing
- Performance optimization

### Phase 5: Deployment & Documentation (5 minutes)
**Learning Goal**: Production readiness
- Deployment preparation
- Documentation generation
- Final review

## Key Learning Outcomes
1. **Structured Prompting**: Break complex tasks into logical phases
2. **Context Building**: Provide relevant information progressively
3. **Iterative Refinement**: Use feedback loops for improvement
4. **Domain-Specific Communication**: Tailor prompts to development tasks
5. **Quality Assurance**: Integrate testing and review into AI workflows

## Prompt Philosophy & Structure

### The STAR Method for AI Prompts
- **S**ituation: Provide context and current state
- **T**ask: Define specific, actionable objectives
- **A**ction: Specify desired approach or constraints
- **R**esult: Describe expected outcomes or success criteria

### Example Prompts

**Phase 1 - Requirements Analysis:**
```
Situation: I need to build a data dashboard for equity price visualization
Task: Analyze the attached CSV data and create comprehensive requirements
Action: Generate user stories, technical requirements, and architecture plan
Result: Clear roadmap for building a Python Dash application
```

**Phase 3 - Implementation:**
```
Situation: I have a Python project set up with Dash and sample equity data
Task: Create an interactive dashboard with price charts and filtering
Action: Build incrementally, starting with basic charts then adding interactivity
Result: Working dashboard that displays OHLC data with date/ticker filtering
```

## Guidelines for Effective AI Collaboration

### Do's:
- ✅ Provide specific, measurable objectives
- ✅ Share relevant files and context
- ✅ Ask for explanations of design decisions
- ✅ Request code reviews and improvements
- ✅ Break large tasks into smaller steps

### Don'ts:
- ❌ Give vague or overly broad requests
- ❌ Skip context or assume AI knows your setup
- ❌ Accept first solution without iteration
- ❌ Ignore error messages or warnings
- ❌ Rush through without understanding

## Suggested Project Structure
```
equity-dashboard/
├── data/
│   └── equity_prices.csv
├── src/
│   ├── dashboard/
│   ├── data_processing/
│   └── utils/
├── tests/
├── requirements.txt
├── README.md
└── app.py
```

## Success Metrics
By the end of this workshop, participants should be able to:
- Structure AI prompts for complex development tasks
- Guide an AI agent through a complete development lifecycle
- Iterate effectively with AI feedback
- Build confidence in AI-assisted development

## Facilitator Notes
- Encourage experimentation with prompt variations
- Emphasize the importance of clear communication with AI
- Highlight when participants use effective prompting techniques
- Show how small prompt changes can significantly impact results
- Keep the pace interactive and hands-on

---
*This workshop demonstrates that AI is most powerful when treated as a collaborative partner, not just a code generator.*