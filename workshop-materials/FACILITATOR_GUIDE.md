# Facilitator Guide: AI-Powered Development Workshop

## Workshop Overview

**Duration**: 60 minutes  
**Goal**: Teach the AI Development Workflow through hands-on dashboard building  
**Key Learning**: User Stories → Implementation Plan → Implementation → Verification

### What Participants Will Build
Interactive stock price dashboard with:
- Stock selection (NVDA, AAPL, GOOGL, MSFT)
- Price visualization with 7-day moving averages (one month of data)
- Date range filtering (focus on different time periods)
- Summary statistics and performance metrics

## Pre-Workshop Setup (15 minutes before)

### Technical Requirements Check
- [ ] All participants have GitHub Copilot Agent Mode enabled
- [ ] VS Code with latest extensions installed
- [ ] Python 3.8+ available
- [ ] Sample data file (equity_prices.csv) distributed

### Workshop Materials
- [ ] `README.md` - Workshop overview and instructions
- [ ] `steps/step-01-*.md` through `steps/step-08-*.md` - Step-by-step guides
- [ ] `sample-data/equity_prices.csv` - Sample dataset
- [ ] This facilitator guide

## Step-by-Step Guidance

### Steps 1-2: Planning Phase (15 minutes)

**Step 1: User Stories (5 min)**
- **Objective**: Define clear requirements before coding
- **Key Teaching**: Start with user value, not technical features
- **Watch For**: Vague requirements, skipping user perspective
- **Facilitator Action**: Emphasize the "so that [benefit]" part of user stories

**Step 2: Implementation Plan (10 min)**
- **Objective**: Transform requirements into technical roadmap
- **Key Teaching**: Break complex tasks into manageable phases
- **Watch For**: Overly detailed plans, missing key components
- **Facilitator Action**: Highlight how planning saves time later

### Steps 3-4: Foundation (15 minutes)

**Step 3: Project Setup (5 min)**
- **Objective**: Create organized development environment
- **Key Teaching**: Good structure supports better development
- **Watch For**: Skipping organization, missing dependencies
- **Facilitator Action**: Show how to verify setup works

**Step 4: Data Loading (10 min)**
- **Objective**: Connect to data source reliably
- **Key Teaching**: Data foundation is crucial for dashboards
- **Watch For**: Not verifying data loaded correctly
- **Facilitator Action**: Emphasize checking data shape and content

### Steps 5-6: Core Features (20 minutes)

**Step 5: Basic Dashboard (10 min)**
- **Objective**: Create interactive user interface
- **Key Teaching**: Start simple, build incrementally
- **Watch For**: Trying to build everything at once
- **Facilitator Action**: Demonstrate testing each interaction

**Step 6: Moving Average (10 min)**
- **Objective**: Add analytical capability with specific methodology
- **Key Teaching**: Technical requirements drive implementation choices
- **Watch For**: Using different calculation methods, not verifying results
- **Facilitator Action**: Highlight how MA smooths trends (now more visible with longer data)

### Steps 7-8: Enhancement (10 minutes)

**Step 7: Date Filtering & Statistics (7 min)**
- **Objective**: Add comprehensive analysis capabilities
- **Key Teaching**: Integration of multiple features
- **Watch For**: Features not working together
- **Facilitator Action**: Show complete user workflow (e.g., comparing January vs. full month performance)

**Step 8: Polish & Documentation (3 min)**
- **Objective**: Professional finish and knowledge sharing
- **Key Teaching**: Documentation enables others to use your work
- **Watch For**: Skipping documentation, leaving rough edges
- **Facilitator Action**: Emphasize professional presentation

## The AI Development Workflow

### Teaching the 4-Phase Pattern

**1. User Stories**
- Define value and purpose
- Use "As a..., I want..., so that..." format
- Focus on user benefits, not technical features

**2. Implementation Plan**
- Break down into technical approach
- Identify key components and phases
- Specify critical methodologies (like SMA calculation)

**3. Implementation**
- Build incrementally
- Test each addition
- Iterate based on results

**4. Verification**
- Test functionality thoroughly
- Compare results with requirements
- Refine based on testing

## Facilitation Best Practices

### Encouraging Good AI Collaboration
- **Celebrate structured prompts**: When someone provides clear context and requirements
- **Share effective interactions**: Have participants share prompts that worked well
- **Demonstrate iteration**: Show how to refine prompts based on AI responses

### Managing the Workshop Flow
- **Keep planning phases moving**: Don't get stuck in analysis
- **Focus on core implementation**: Steps 5-6 are the heart of the workshop
- **Use time flexibly**: Adjust pace based on participant progress

### Common Issues and Solutions
- **AI gives unexpected results**: Use as teaching moment about prompt clarity
- **Participant falls behind**: Pair with someone who's ahead
- **Technical problems**: Have backup data and environments ready

## Key Messages to Reinforce

1. **Structure leads to better results**: Clear prompts get better AI responses
2. **Iteration is normal**: Expect to refine and improve with AI
3. **Verification is crucial**: Always test what AI produces
4. **Context matters**: Build understanding progressively
5. **Documentation enables sharing**: Others can build on your work
6. **Maintain development context**: CHANGELOG.md helps track progress and decisions

## The CHANGELOG.md Strategy

### Why It Matters
Each step includes instructions for the AI to update a CHANGELOG.md file. This serves multiple purposes:

**For the AI Agent:**
- Maintains context across conversation sessions
- Tracks what's been accomplished and what's next
- Provides reference for decision-making
- Helps avoid repeating work or missing steps

**For the Developer:**
- Creates a development log of progress
- Documents technical decisions and approaches
- Provides easy reference for troubleshooting
- Enables others to understand the development process

**For the Workshop:**
- Demonstrates good development practices
- Shows how to maintain context with AI
- Creates a sharable record of the learning process

### Teaching Points
- **Emphasize consistency**: Every step updates the changelog
- **Show the value**: Reference previous changelog entries when troubleshooting
- **Demonstrate context building**: Show how AI uses changelog for better responses
- **Highlight documentation**: Good developers document their work

## Workshop Wrap-Up (5 minutes)

### Reflection Questions
- Which step in the workflow was most valuable?
- When did the AI partnership work best?
- What will you try in your next project?
- How does this change your approach to development?

### Success Indicators
Participants successfully demonstrate:
- ✅ Breaking complex tasks into clear steps
- ✅ Providing structured prompts to AI
- ✅ Building incrementally with verification
- ✅ Treating AI as a collaborative partner

### Follow-Up Resources
- Advanced prompt engineering techniques
- AI-assisted development best practices
- Community resources for continued learning

## Troubleshooting

### If Participants Struggle With:
- **Prompt clarity**: Refer back to step examples
- **Technical issues**: Use pair programming
- **AI responses**: Demonstrate prompt refinement
- **Time pressure**: Focus on core workflow pattern

---

*The goal is mastering the AI collaboration workflow, not building the perfect dashboard.*