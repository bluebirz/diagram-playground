# Mermaid diagram - Sankey

doc: [sankey Syntax | Mermaid](https://mermaid.js.org/syntax/sankey.html)

```mermaid
sankey
    title Sankey Diagram Example
    A[Start] -->|10| B[Process 1]
    A -->|20| C[Process 2]
    B -->|5| D[End 1]
    B -->|5| E[End 2]
    C -->|15| F[End 3]
    C -->|5| G[End 4]
```
