---
name: global-skill-orchestration
description: Governs selection, priority hierarchy, and conflict resolution across UI/UX, motion, 3D, and content skills.
trigger: always_on
---

# Global Skill Orchestration Rules

You have access to multiple specialized design, research, visual, motion, and writing skills. Do not activate or apply every available skill to every task.

## 1. Skill Selection Principles

- **Skill Selection is Optional:** Use no skill when the task does not benefit from one, such as standard code edits, direct factual queries, or simple bug fixes.
- **Single Primary Focus:** When skills are useful, select exactly one primary skill that leads the task.
- **Supporting Boundary:** Add a maximum of two supporting skills only when cross-disciplinary synthesis is genuinely required.
- **Prefer Specificity:** Prefer a focused domain skill over a broad or generic one.
- **Mandatory Instruction Review:** Read the `SKILL.md` of every selected skill before applying its instructions.

## 2. Conditional Execution Hierarchy

Apply only the stages relevant to the scope of the request. Do not force an end-to-end strategy-to-visual workflow for small tasks, localized fixes, or focused questions.

For multi-stage initiatives, follow this sequence:

1. **Strategy and Research:** Define user intent, product value, and outcome metrics first (`ux-strategy`, `ux-skills`).
2. **Structure and Interaction:** Establish user journeys, page inventory, ergonomics, and system states before styling (`ux-design`, `ui-ux-designer-rmyndharis`).
3. **Visual Design:** Implement design systems, typography, color palettes, and accessible components (`ui-ux-pro-max`, `top-design`, `antigravity-design-expert`).
4. **Motion and 3D:** Introduce motion curves, scroll transitions, or 3D elements only when they enhance spatial comprehension or feedback, never for pure decoration (`ai-ui-ux-motion-engine`, `3d-web-experience`).
5. **Microcopy and Clarity:** Craft concise, accessible, contextual interface copy, labels, and error states (`ux-writing`, `ux-writing-microcopy`, `articulate`, `copywriting`).

## 3. Skill Routing Matrix

| Intent / Primary Need | Primary Skill | Supporting Skills |
|---|---|---|
| Product Strategy and User Research | `ux-strategy` | `ux-skills`, `ux-design` |
| User Flows, States and IA | `ux-design` | `ui-ux-designer-rmyndharis`, `ux-strategy` |
| Comprehensive Design System / Theming | `ui-ux-pro-max` | `top-design`, `ux-design` |
| High-Fidelity Visual Design and Layout | `top-design` | `ui-ux-pro-max`, `antigravity-design-expert` |
| Cinematic Motion and Exploded Views | `ai-ui-ux-motion-engine` | `antigravity-design-expert`, `top-design` |
| 3D Canvas / Spline / Three.js | `3d-web-experience` | `antigravity-design-expert`, `ai-ui-ux-motion-engine` |
| UI Microcopy, Errors and Empty States | `ux-writing` | `ux-writing-microcopy`, `ux-design` |
| Conversion, Headlines and Marketing Copy | `copywriting` | `articulate`, `top-design` |
| Developer / Creative Portfolio | `interactive-portfolio` | `top-design`, `ai-ui-ux-motion-engine` |

## 4. Conflict Resolution and Guardrails

- **Baseline Requirements:** Accessibility, responsive behavior, usability, and runtime performance are non-negotiable baselines.
- **No Conflicting Paradigms:** Never merge incompatible design systems, style paradigms, or conflicting tokens without explicitly discussing trade-offs.
- **Preserve Existing Decisions:** Do not override existing architecture, color systems, or user choices without explicit approval.
- **Project Boundary Protection:** Do not modify unrelated projects or files unless the active task explicitly authorizes that work. Always respect the project's own instructions and established decisions.
- **Substance Over Trends:** Prioritize real user needs, functional clarity, and ergonomics over visual novelties.

