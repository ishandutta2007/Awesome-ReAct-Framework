# Reinforcement-Learned Verifiable ReAct

Writing code and verifying in sandboxes for positive optimization gradients.

## Architecture Diagram

`mermaid
flowchart LR
 A[Generate Code] --> B[Sandbox Compiler] --> C{Pass?}
 C -- Yes --> D[Positive Reward]
 C -- No --> E[Backprop Error]
`

[<-- Back to Home](../README.md)
