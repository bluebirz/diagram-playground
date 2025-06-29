# Mermaid diagram - ER Diagram

doc: [ER Diagrams Syntax \| Mermaid](https://mermaid.js.org/syntax/entityRelationshipDiagram.html)

```mermaid
erDiagram
    title ER Diagram Example
    entity "User" {
        +id: int
        +name: string
        +email: string
    }
    entity "Order" {
        +id: int
        +date: date
        +amount: float
    }
    entity "Product" {
        +id: int
        +name: string
        +price: float
    }
    
    User ||--o{ Order : places
    Order ||--|{ Product : contains
```
