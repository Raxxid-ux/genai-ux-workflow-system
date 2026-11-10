# GenAI UX Workflow System

A structured AI-assisted workflow for UX and product design, built around specialized skills, task-based selection, and instruction orchestration.

The goal is simple: make AI-assisted design work more consistent, focused, and useful without activating unnecessary skills or creating conflicting instructions.

## Overview

The GenAI UX Workflow System organizes specialized AI skills into a practical process for UX and product design tasks.

Instead of applying every available skill to every request, the system identifies the user's intended outcome, selects the most relevant skill, applies supporting capabilities when necessary, and evaluates the result against the original requirements.

## How It Works

The workflow follows six stages:

1. **Understand intent:** Identify the design problem, expected outcome, constraints, and deliverables.
2. **Classify the task:** Determine whether the work involves UX research, strategy, interaction design, UI design, UX writing, visual design, or prototyping.
3. **Select skills:** Choose one primary skill and only add supporting skills when they provide distinct value.
4. **Orchestrate instructions:** Apply global rules to manage priorities, conflicts, and project constraints.
5. **Execute:** Complete the task using the selected skills and available project context.
6. **Evaluate:** Review the output against the original goal, usability, quality, and constraints.

**Core principle:** Use the smallest effective combination of skills. More skills do not automatically produce better results.

## Repository Structure

```text
genai-ux-workflow-system/
├── docs/
│   ├── attribution.md
│   └── workflow-architecture.md
├── evaluations/
│   └── evaluation-plan.md
├── orchestration/
│   ├── global-skill-orchestration.md
│   └── skill-selection-rules.md
├── research/
│   └── skills-inventory.csv
├── skills/
│   ├── ai-ui-ux-motion-engine/
│   ├── ui-ux-designer-rmyndharis/
│   └── ux-strategy/
└── README.md
```

The public `skills/` directory currently contains three third-party skills with attribution and licence files. The research inventory tracks additional skills, including those whose source or redistribution status is still being verified.

## Orchestration Principles

The system follows these rules:

- One primary skill whenever possible.
- A maximum of two supporting skills when genuinely necessary.
- Prefer focused skills over broad, overlapping ones.
- Review the `SKILL.md` instructions before applying a selected skill.
- Preserve project-specific decisions and constraints.
- Treat accessibility, usability, responsiveness, and performance as baseline requirements.
- Do not silently combine conflicting instructions.
- Use human review and design judgment to evaluate the final output.

## Evaluation

The system includes an evaluation plan with three practical scenarios:

- Improving an existing UI.
- Designing an onboarding flow.
- Creating an immersive landing page.

Each scenario is assessed on skill relevance, instruction consistency, UX quality, visual quality, constraint adherence, and practicality.

The project does not claim improved quality or efficiency without comparative testing.

## Third-Party Skills and Attribution

This project includes and references skills created by other authors.

Original authorship, copyright notices, and licence conditions must be respected. Local differences are not automatically assumed to be original contributions by this repository's maintainer.

See:

- [`docs/attribution.md`](docs/attribution.md)
- [`research/skills-inventory.csv`](research/skills-inventory.csv)

Only skills with sufficiently established redistribution permissions should be included in the public collection.

## Project Goals

- Organize specialized AI skills into a coherent workflow.
- Reduce conflicting instructions and inconsistent outputs.
- Improve task-based skill selection.
- Preserve design intent and project constraints.
- Evaluate the system through practical UX design tasks.
- Document decisions, limitations, and improvements.

## Project Status

<em>Active development.</em>

The initial architecture, orchestration rules, research inventory, evaluation plan, and first three public skills are in place. Further source verification, testing, and refinement are ongoing.

## Contributions

Contributions should improve the workflow's clarity, reliability, or practical usefulness.

Before adding a skill:

1. Identify its original source and author.
2. Verify its licence and redistribution permissions.
3. Preserve required copyright and attribution notices.
4. Document modifications and version differences.
5. Explain when the skill should be selected and what distinct capability it provides.

Do not add skills with unknown redistribution permissions to the public collection.

---

Built as an ongoing exploration of structured AI workflows for UX and product design.
