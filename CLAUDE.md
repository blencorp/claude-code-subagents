# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a software development methodology framework that defines a structured workflow for AI-powered development using specialized "subagents." The project is currently in the documentation/planning phase with no actual implementation code yet.

## Core Architecture: 8-Step Subagent Workflow

This project enforces a specific development process with distinct AI roles:

1. **Onboarding Specialist** - Analyzes new projects and tasks
2. **Product Owner** - Provides project understanding and requirements
3. **Product Manager** - Creates detailed implementation plans
4. **Staff Engineer** - Implements according to the plan
5. **QA Engineer** - Tests and validates the work
6. **Product Manager** - Reviews and provides feedback
7. **Product Owner** - Final approval
8. **Task Completion**

## Key Development Guidelines

### Mandatory Process Flow
- Always start tasks by using the onboarding specialist subagent
- Product owner must provide clear project understanding
- Product manager must create detailed plans before any engineering work
- Staff engineer must follow the plan exactly, requesting clarification as needed
- QA engineer must validate all work before completion
- Product manager and product owner must approve work sequentially

### Critical Decision Framework
When deviating from plans, always stop and ask: "What would John Carmack do?" before proceeding.

### Documentation Requirements
- Use Context 7 MCP to access latest documentation
- Record lessons learned in `docs/memory.md`
- Follow the implementation plan template in `docs/implementation-plan/TEMPLATE.md`

## Project Structure

```
docs/
├── PRD.md                    # Product requirements (placeholder)
├── START.md                  # Core project guidelines
└── implementation-plan/
    └── TEMPLATE.md          # Comprehensive implementation template
```

## Implementation Template Features

The project uses a structured template that includes:
- Intent mapping and boundary definitions
- Technical approach with specific tool usage
- Test strategy and success criteria
- Rollback plans and validation points
- Progress tracking with markdown checkboxes
- Executor feedback mechanisms

## Current State

- **Phase:** Documentation/planning only
- **Code:** No implementation exists yet
- **Dependencies:** None defined
- **Build/Test Commands:** Not applicable (no code exists)

## Working with this Project

When implementing features in this repository:
1. Follow the 8-step subagent workflow strictly
2. Use the implementation plan template for all work
3. Maintain detailed documentation throughout
4. Implement the subagent system itself when moving to the development phase