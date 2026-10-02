---
name: listennotes-manage-podcast
description: Create, refresh, and delete a podcast using the ListenNotes Podcaster API.
api: openapi/listennotes-podcaster-api-api-openapi.yml
operations:
- submitPodcast
- refreshPodcastRss
- deletePodcastById
generated: '2026-10-02'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/listennotes-podcaster-api-api-openapi.yml ; every operationId checked against the contract
---

# listennotes-manage-podcast

Create, refresh, and delete a podcast using the ListenNotes Podcaster API.

## Steps

1. 1. Call `submitPodcast` with the required request body fields for a new podcast.
2. 2. Call `refreshPodcastRss` with the `id` path parameter returned from the submit step to refresh its RSS feed.
3. 3. Call `deletePodcastById` with the same `id` path parameter to remove the podcast.

## Rules

- Include the API key in the `X-ListenAPI-Key` header for all requests.
