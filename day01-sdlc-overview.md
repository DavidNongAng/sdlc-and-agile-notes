# What is SDLC? 

SDLC (Software Development Life Cycle) is a step-by-step process that defines how software is developed, deployed, and maintained.
It ensures software is delivered systematically, on time, within budget, and meets user requirements.

# The 7 Core Phases of SDLC

## 1. Planning
- Define project scope, goals, and constraints
- Identify stakeholders and risks
- Estimate time, budget, and resources
- Output: Project Plan

## 2. Requirements Analysis
- Gather functional & non-functional requirements
- Methods: interviews, user stores, surverys and use cases.
- Output: Requirements Specification Document (or user stores/backlog in Agile)

*Functional Requirments: What the system should do
*Non-Functional Requirements: How well the system performs (performance, security)

## 3. Design
- Define the system architecture, data models, UI layout
- Tools: UML, ER diagrams, wireframes
- Output: System Design Document, wireframes

*High-level design: Architecture overview
*Low-level design: Detailed logic, database schema

## 4. Development
- Actual coding based on design specs
- Use version control (Git), coding standards
- Work in sprints or phases (based on methodology)
- Output: Working software modules/features

## 5. Testing
- Validate the software against requirements
- Types of testing:
    - Unit Testing (single functions)
    - Integration Testing (Combined components)
    - System Testing (entire system)
    - User Acceptance Testing (real user feedback)
- Output: Bug reports, test cases, test results

## 6. Deployment
- Release software to production or client environment
- Set up hosting, DNS, environment variables, CI/CD if applicable
- Output: Live application or product

## 7. Maintenance
- Post-launch support: bug fixes, feature updates, performance monitoring
- May involve user feedback loops
- Output: Updated versions, change logs

# SDLC Models (Methodologies)

| Model | Description | Best For |
|:-----------|:------------:|:------------:|
| Waterfall | Linear, one phase at a time | Projects with fixed requirements| 
| Agile | Iterative, incremental, feedback-driven | Projects with evolving needs | 
| Spiral | Risk-driven, multiple rounds of planning/testing | Large, high-risk systems |
| V-model | Each dev phase has a matching test phase | Safety-critical systems |
| Big Bang | No structure - Build as you go | Very small or experimental projects |

# Key Benefits of Using SDLC
- Clear structure and process
- Easier to manage large projects
- Better estimation of time and resources
- Improved quality control
- Facilitates documentation and maintenance 

# SDLC in Real Life
Ex.) Let's say you're building a Collaborative Task Manager App: 
- Planning: Decide the app will support teams, tasks, due dates, and real-time updates.
- Requirements: Users need to create/edit/delete tasks, assign them, get rela0time async.
- Design: You sketch wireframes, plan MongoDB schema, and system architecture.
- Development: Build using MERN stack.
- Testing: You write unit tests for task CRUD and integration tests for collaboration logic.
- Deployment: Use AWS Amplify for frontend, Lambda for backend.
- Maintenance: User request notifications -> you add and release that feature later.

