# Copy-on-Write Block Routing

Memory-efficient exploration for branching logic.

## Architecture Diagram

`mermaid
flowchart TD
 A[Parent State] --> B[Branch 1]
 A --> C[Branch 2]
 B --> D[New Memory Page Allocated]
`

[<-- Back to Home](../README.md)
