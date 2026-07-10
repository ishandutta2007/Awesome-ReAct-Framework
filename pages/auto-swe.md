# Autonomous Software Engineering

Automated developer platforms and closed-loop search.

## Architecture Diagram

`mermaid
flowchart TD
 A[Issue] --> B[Read Files] --> C[Edit Code] --> D[Test]
 D -- Fail --> B
 D -- Pass --> E[Commit]
`

[<-- Back to Home](../README.md)
