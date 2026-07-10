# Plan-and-Solve / Tree-of-Agents

Macro-architectural planning and parallel sub-agent execution.

## Architecture Diagram

`mermaid
flowchart TD
 A[Root Planner] --> B[Sub-Agent 1]
 A --> C[Sub-Agent 2]
 B --> D[Merge]
 C --> D
`

[<-- Back to Home](../README.md)
