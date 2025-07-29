# Claude Code Subagents

A structured workflow framework for AI-powered software development using specialized agent roles.

## Overview

This project defines a systematic approach to software development that leverages specialized AI "subagents" working in sequence to ensure quality, consistency, and thorough planning throughout the development lifecycle.

The framework enforces a disciplined workflow where different AI agents handle specific aspects of development - from initial project understanding through final approval - creating a more structured and reliable development process.

## The 8-Step Subagent Workflow

The framework defines eight distinct roles that must be followed in sequence:

1. **🎯 Onboarding Specialist** - Analyzes new projects and tasks, provides initial understanding
2. **📋 Product Owner** - Ensures clear project requirements and task understanding  
3. **📊 Product Manager** - Creates detailed implementation plans and technical approaches
4. **⚙️ Staff Engineer** - Implements according to the plan, requests clarification as needed
5. **🧪 QA Engineer** - Tests and validates all work against requirements
6. **📊 Product Manager** - Reviews completed work and provides feedback
7. **📋 Product Owner** - Provides final approval of the deliverable
8. **✅ Task Completion** - Work is considered complete

## Key Features

### Structured Development Process
- **Plan-First Approach**: All engineering work requires detailed planning before implementation
- **Quality Gates**: Multiple validation points throughout the development lifecycle  
- **Role Separation**: Clear responsibilities for each phase of development
- **Documentation-Driven**: Comprehensive documentation requirements at every step

### Decision Framework
- **Reflection Mechanism**: "What would John Carmack do?" decision point for plan deviations
- **Boundary Enforcement**: Clear definitions of what changes and what stays unchanged
- **Validation Points**: Specific checkpoints for quality assurance

### Implementation Templates
- **Structured Planning**: Comprehensive template for implementation plans
- **Intent Mapping**: Each step maps to specific project intents and boundaries
- **Progress Tracking**: Built-in progress tracking with markdown checkboxes
- **Rollback Plans**: Pre-defined recovery procedures for each implementation

## Project Structure

```
claude-code-subagents/
├── README.md                    # This file
├── CLAUDE.md                    # Claude Code integration guide
└── docs/
    ├── PRD.md                   # Product requirements (placeholder)
    ├── START.md                 # Core workflow guidelines
    └── implementation-plan/
        └── TEMPLATE.md          # Implementation plan template
```

## Getting Started

### Prerequisites
- AI development tool that supports subagent workflows (e.g., Claude Code)
- Git for version control
- Text editor for documentation

### Using the Framework

1. **Start with Onboarding**: Always begin any task by having an onboarding specialist analyze the project and task
2. **Get Product Owner Clarity**: Ensure the product owner provides clear project understanding
3. **Create Implementation Plan**: Have the product manager create a detailed plan using the template
4. **Follow the Plan**: Staff engineer implements according to the plan, requesting clarification as needed
5. **Validate Work**: QA engineer tests and validates against requirements
6. **Review and Approve**: Product manager reviews, then product owner approves

### Documentation Requirements

- Use the implementation plan template in `docs/implementation-plan/TEMPLATE.md`
- Record lessons learned in a `docs/memory.md` file
- Reference Context 7 MCP for accessing latest documentation
- Follow the guidelines in `docs/START.md`

## Implementation Plan Template

The framework includes a comprehensive template that covers:

- **Intent Mapping**: Each step maps to project intents with clear boundaries
- **Technical Approach**: Specific tools and validation points for each step  
- **Test Strategy**: Testing approach, cases, and coverage requirements
- **Success Criteria**: Measurable outcomes and quality gates
- **Rollback Plans**: Recovery procedures and validation steps
- **Progress Tracking**: Markdown checkboxes for task completion
- **Feedback Mechanisms**: Structured way for executors to request help

## Current Status

**⚠️ Early Development Phase**: This project is currently in the documentation and planning phase. The framework has been defined but not yet implemented as working software.

### What's Available Now
- ✅ Complete workflow definition and guidelines
- ✅ Implementation plan template
- ✅ Integration guide for Claude Code
- ✅ Structured development process

### What's Coming Next
- 🔄 Reference implementation of the subagent system
- 🔄 Integration examples with popular development tools
- 🔄 Metrics and measurement capabilities
- 🔄 Community feedback integration

## Contributing

We welcome contributions to help develop this framework! Areas where we need help:

### Documentation
- Clarify the Context 7 MCP integration requirements
- Expand on the John Carmack decision framework
- Add real-world usage examples

### Implementation
- Build reference implementation of the subagent workflow
- Create integrations with popular development tools
- Develop metrics and measurement systems

### Testing
- Create test cases for the workflow process
- Validate the framework with real development projects
- Gather feedback from development teams

## Design Philosophy

This framework is built on several key principles:

- **Structure Over Speed**: Prioritizes thorough planning and validation over rapid iteration
- **Documentation First**: Heavy emphasis on clear documentation and requirements
- **Quality Gates**: Multiple validation points prevent issues from propagating
- **Role Clarity**: Clear separation of concerns across different development phases
- **Reflection**: Built-in mechanisms for questioning and validating decisions

## Use Cases

This framework is designed for:

- **Complex Software Projects**: Where thorough planning and validation are critical
- **Team Development**: Where role clarity and handoffs are important  
- **Quality-Critical Systems**: Where multiple validation points add value
- **Learning and Training**: Where structured processes help build good habits

## Questions and Discussion

This framework represents an experiment in structured AI-powered development. Key questions we're exploring:

- How much process structure is optimal for different project types?
- What's the right balance between thorough planning and agile iteration?
- How can AI agents best collaborate on complex development tasks?
- What measurements best indicate the success of this approach?

## License

[Add your chosen license here]

## Support

- Create issues for bugs or feature requests
- Start discussions for questions about the framework
- Check existing documentation in the `docs/` directory

---

*This project is an exploration of structured AI-powered development workflows. We're actively seeking feedback and contributions from the development community.*


---

Built with ❤️ by [BLEN](https://www.blencorp.com).

## About BLEN

BLEN, Inc is a digital services company that provides Emerging Technology (ML/AI, RPA), Digital Modernization (Legacy to Cloud) and Human-Centered Web/Mobile Design and Development.