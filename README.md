# NikeStore_ERD.md


```mermaid
flowchart TB
  A[Customer] --> B[Demand]
  B --> C[Product]
  C --> D[Inventory]
  B -"if"-> D
  D --> E[Sales]

  ```