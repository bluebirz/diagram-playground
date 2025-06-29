# Mermaid diagram - Quadrant

doc: [Quadrant Syntax | Mermaid](https://mermaid.js.org/syntax/quadrant.html)

```mermaid
quadrant
    title Quadrant Chart Example
    x-axis: "Low" --> "High"
    y-axis: "Low" --> "High"
    
    A[Category A] : 10, 20
    B[Category B] : 30, 40
    C[Category C] : 50, 60
    D[Category D] : 70, 80
    
    A --> B
    B --> C
    C --> D
```
