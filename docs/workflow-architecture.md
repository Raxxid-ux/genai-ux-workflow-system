# Workflow Architecture

## Purpose

The GenAI UX Workflow System organizes specialized AI skills into a structured process for UX and product design tasks.

## Core Layers

### 1. User Intent
Understand the design problem, expected outcome, constraints, and deliverables.

### 2. Task Classification
Identify the primary discipline involved, such as:
- UX research
- UX strategy
- Interaction design
- UI design
- UX writing
- Visual design
- Prototyping and motion

### 3. Skill Selection
Select the most relevant primary skill. Add supporting skills only when they provide a distinct capability.

### 4. Orchestration
Apply the global orchestration rules to manage skill selection, instruction hierarchy, and conflicts.

### 5. Execution
Complete the task using the selected skills and the project context.

### 6. Evaluation
Review the output against the original goal, constraints, usability, and quality expectations.

## Design Principle

Use the smallest effective combination of skills. More skills do not automatically produce better results.
