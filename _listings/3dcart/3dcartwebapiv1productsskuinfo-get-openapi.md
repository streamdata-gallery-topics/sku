---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart Get all products (SKUInfo section only)
  version: 1.0.0
  description: Get all products (skuinfo section only).
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/Products/skuinfo:
    get:
      summary: Get all products (SKUInfo section only)
      description: Get all products (skuinfo section only).
      operationId: Products_GetAllProductsSKUInfo
      x-api-path-slug: 3dcartwebapiv1productsskuinfo-get
      parameters:
      - in: query
        name: catalogid
        description: Catalog ID
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: name
        description: Name of the product
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: query
        name: sku
        description: SKU Code of the product
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Products
      - (SKUInfo
      - Section
      - Only)
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---