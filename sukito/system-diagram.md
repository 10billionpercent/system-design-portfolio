# System Diagram

```mermaid
graph TD
    A[User] --> B[Frontend UI]
    B --> C[Search / Recommendation Logic]
    C --> D[Kitsu API]
    D --> C
    C --> E[Results Display]
    E --> A
```