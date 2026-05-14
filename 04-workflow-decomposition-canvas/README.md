# 04 — Workflow Decomposition Canvas
## Objective
Help builders understand workflows before building AI-native systems.
One of the most common failure modes in AI-assisted development is starting from features instead of workflows.
Teams often:
- jump directly into coding,
- automate unclear processes,
- overuse AI where human judgment is needed,
- or create systems without operational visibility.
This module introduces workflow-first system design.
---
# Core Principle
Before building an AI-native application, builders should understand:
```text
Who does what
↓
Why they do it
↓
What decisions are made
↓
What data is involved
↓
What risks exist
↓
What should or should not be automated

AI-native systems should emerge from workflows — not from isolated prompts.

⸻

Workflow-First Thinking

Traditional development often starts with:

Features
↓
Screens
↓
Code

AI-native system design should start with:

Workflow
↓
Actors
↓
Decisions
↓
Risks
↓
Architecture
↓
Orchestration
↓
Code

This shift is critical for scalable AI adoption.

⸻

Core Workflow Components

A workflow should map:

Actors
Inputs
Actions
Decisions
Outputs
Systems
Risks
Oversight points
Automation opportunities

⸻

Workflow Decomposition Structure

Recommended decomposition format:

Step:
Actor:
Input:
Action:
Decision:
Output:
Tool/System:
AI Assistance:
Risk Level:
Human Approval Required:

This structure helps teams identify where AI can safely assist and where human judgment remains essential.

⸻

Human–AI Coordination

AI-native workflows should distinguish between:

AI can automate
AI can assist
AI can recommend
Humans must approve
Humans must decide
Humans must intervene

Not every workflow should be fully automated.

⸻

Workflow Risk Mapping

Workflows should identify:

Data sensitivity
Hallucination risk
Bias risk
Operational dependency
Human oversight gaps
Security risks
Failure escalation paths

Most operational AI risks emerge at workflow level — not only at model level.

⸻

Automation Opportunity Mapping

Categorize workflow components into:

Fully automatable
AI-assisted
Human-led
Do not automate

This prevents organizations from automating processes that require contextual or ethical judgment.

⸻

Common Workflow Failure Modes

Typical workflow failures include:

unclear responsibilities
over-automation
hidden human labor
fragmented approvals
missing escalation paths
workflow duplication
AI dependency loops
lack of visibility

These failures often become operational bottlenecks later.

⸻

Minimum Viable Workflow Design

Before coding, teams should define:

Primary workflow
Primary user
Main decision points
Critical risks
Minimum oversight
Required integrations
Success criteria

This creates a stable operational foundation for architecture and orchestration.

⸻

Workflow Analysis Prompt

You are my workflow decomposition expert.
Review this project from a workflow-first perspective.
Do not start coding immediately.
First assess:
1. Main workflows
2. Actors and responsibilities
3. Decision points
4. Human oversight requirements
5. AI assistance opportunities
6. Automation risks
7. Operational bottlenecks
8. Escalation paths
9. Workflow visibility
10. Missing workflow structures
Then produce:
A. Workflow map
B. Main actors
C. Critical workflow dependencies
D. Human–AI coordination map
E. Automation opportunities
F. Workflow risks
G. Operational bottlenecks
H. Recommended workflow architecture
I. Prioritized workflow roadmap
J. Checklist of completed and missing workflow components
Only after that, ask me which workflow area I want to improve first.

⸻

Final Principle

AI-native systems should not begin with code.

They should begin with understanding how work actually happens.

Then commit with:
```text
Add Workflow Decomposition Canvas module
