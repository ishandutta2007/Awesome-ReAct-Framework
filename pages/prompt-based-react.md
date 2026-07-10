# The Prompt-Based Text-Wrapper Era

Vanilla ReAct loops with rigid system prompts.

## Architecture Diagram

`mermaid
flowchart TD
 A[User Query] --> B[Prompt Wrapper] --> C[LLM] --> D[Tool Executor] --> B
`

[<-- Back to Home](../README.md)
