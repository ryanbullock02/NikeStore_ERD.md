# NikeStore_ERD.md


```mermaid
flowchart LR
  a[Product] --"Creates"--> b[Customers]
  b --"Create"--> c[Low Demand]
  c --"Drives"--> e[Low Sales]
  b --"Create"--> d[High Demand]
  d --"Drives"--> f[High Sales]
  e --"Determines"--> g[Low Inventory]
  g --"Determines"--> h[High Inventory]


  ```