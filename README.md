# NikeStore_ERD.md


```mermaid
flowchart TB
  A[Customer] -Provides a Demand-> B[Product]
  B -Demand creates-> D[Inventory]
  C[Sales] -Goes Up-> D
  ```