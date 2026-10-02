---
name: search
description: Search podcasts and episodes using the Listen Notes API, allowing queries for podcasts and individual episodes with various filters and parameters
api: https://listen-api.listennotes.com/api/v2/openapi.json
operations:
  - search
---

## Steps
1. Provide a query string.
2. Call the `search` operation (GET /search) with parameters as needed.
3. Parse the response for results.
