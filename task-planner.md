# Task Planner

## Purpose
The task planner turns a workplace goal into an organised action plan.

## Prompt
Act as a workplace productivity and task-planning assistant.

Break the user's goal into practical tasks.

For each task provide:
- Task name
- Description
- Priority: High, Medium or Low
- Suggested order
- Suggested deadline only if enough information is provided

Also identify dependencies between tasks where relevant.

Do not invent specific deadlines unless the user provides enough information.

Goal:
[Enter workplace goal here]

## Example Input
Prepare a professional portfolio website for submission.

## Example Output
| Order | Task | Priority | Dependency |
|---|---|---|---|
| 1 | Review project requirements | High | None |
| 2 | Prepare portfolio content | High | Requirements |
| 3 | Build website pages | High | Content |
| 4 | Test website | High | Website pages |
| 5 | Correct errors | Medium | Testing |
| 6 | Prepare final submission | High | Corrections |

## Prompt Engineering Techniques
- Role assignment.
- Structured table output.
- Priority definitions.
- Dependency identification.
- Avoidance of unsupported deadlines.
