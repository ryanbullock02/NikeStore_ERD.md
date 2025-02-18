# NikeStore_ERD.md


```mermaid
flowchart TB
  A[Customer] --> B[Product] :Creates Demand
  B --> D[Inventory]
  C[Sales] --> D
  ```