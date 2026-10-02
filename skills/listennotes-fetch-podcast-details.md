---
name: listennotes-fetch-podcast-details
description: Retrieve a podcast's details and a specific episode from it.
api: openapi/listennotes-directory-api-api-openapi.yml
operations:
- getPodcastById
- getEpisodeById
generated: '2026-10-02'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/listennotes-directory-api-api-openapi.yml ; every operationId checked against the contract
---

# listennotes-fetch-podcast-details

Retrieve a podcast's details and a specific episode from it.

## Steps

1. 1. Call `getPodcastById` with the podcast `id` path parameter and include the `X-ListenAPI-Key` header.
2. 2. Call `getEpisodeById` with the episode `id` path parameter and include the `X-ListenAPI-Key` header.

## Rules

- Auth: Provide the API key in the `X-ListenAPI-Key` header (apiKeyHeader scheme).
- No rate‑limit information is provided; handle HTTP errors as generic failures.
