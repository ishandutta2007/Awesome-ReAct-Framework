# The Standardized Client-Server Tool Era

Integration of Model Context Protocol for decoupling LLM from tool logic.

## Architecture Diagram

`mermaid
flowchart LR
 A[LLM Client] <-->|JSON-RPC| B[MCP Server]
 B <--> C[External Tools]
`

[<-- Back to Home](../README.md)
