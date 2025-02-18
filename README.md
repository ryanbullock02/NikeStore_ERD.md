# NikeStore_ERD.md


```mermaid
flowchart LR
  a[Product] --"Creates"--> b[Customers]
  b --"Create"--> c[Low Demand]
  c --"Drives"--> e[Low Sales]
  b --"Create"--> d[High Demand]
  d --"Drives"--> f[High Sales]
  e --"Determines"--> g[Low Inventory]
  f --"Determines"--> h[High Inventory]


  ```

This chart is assuming that price is not a driving factor of demand and is also assuming inventory can keep up with demand.


## Descriptions

### Product
A product is an item or SKU that is available to be purchased by a customer

### Customer
A customer is someone with interest and ability to buy the product

### Sale
A sale is a record of a purchase of a product by a customer

### Inventory
Inventory is the amount of available product that a customer can purchase
