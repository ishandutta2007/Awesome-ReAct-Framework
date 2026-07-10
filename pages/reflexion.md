# Reflexion

Adding explicit self-reflection memory buffers.

## Architecture Diagram

`mermaid
flowchart TD
 A[Execution] --> B{Success?}
 B -- No --> C[Self-Reflection] --> A
 B -- Yes --> D[Done]
`

[<-- Back to Home](../README.md)
