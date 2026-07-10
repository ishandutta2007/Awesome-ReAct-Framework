# PagedAttention Prefix Cache Locking

Efficient virtual memory management for LLM serving.

## Architecture Diagram

`mermaid
flowchart LR
 A[Prefix Tokens] --> B[Shared KV Pages]
 C[User 1] --> B
 D[User 2] --> B
`

[<-- Back to Home](../README.md)
