# NikeStore_ERD.md


```mermaid
flowchart TB
  A[Customer] --> B[Demand]
  B --> C[Product]
  C --> D[Inventory]
  B --> D
  D --> E[Sales]

  ```