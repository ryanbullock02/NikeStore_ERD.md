# NikeStore_ERD.md


```mermaid
flowchart LR
  a[Product] --"Creates"--> b[Customers]
  b --"Create"--> c[Low Demand]
  b --"Create"--> d[High Demand]


  ```