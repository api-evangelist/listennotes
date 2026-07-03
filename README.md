# Listen Notes (listennotes)

Listen Notes runs the largest podcast search engine and database, and exposes it as the Listen API - a simple, no-nonsense podcast search, directory, and insights REST API. It lets developers full-text search millions of podcasts and episodes by people, places, and topics; fetch podcast and episode metadata; browse best-podcasts charts, curated lists, and genres; retrieve podcast/episode recommendations; power typeahead autocomplete; and pull audience demographics and publisher-domain insights. The API is served at `https://listen-api.listennotes.com/api/v2` and authenticated with an `X-ListenAPI-Key` header, with FREE, PRO, and ENTERPRISE plans billed on a request basis.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/listennotes/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/listennotes/refs/heads/main/apis.yml)

## Tags

- Podcasts
- Podcast Search
- Podcast Directory
- Search
- Audio
- Media
- Podcast Insights

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## APIs

### Listen Notes Search API

Full-text search across episodes, podcasts, and curated lists by people, places, or topics, with rich filters (genre, language, region, length, publish date, episode count, update frequency). Includes searching individual episodes by title and spell-checking a search term.

- **Human URL:** [https://www.listennotes.com/api/docs/](https://www.listennotes.com/api/docs/)
- **Base URL:** `https://listen-api.listennotes.com/api/v2`

#### Tags

- Search
- Full Text Search
- Podcasts
- Episodes

#### Properties

- [Documentation](https://www.listennotes.com/api/docs/)
- [API Reference](https://www.listennotes.com/api/docs/)
- [OpenAPI](openapi/listennotes-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/listennotes.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/listennotes.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Listen Notes Typeahead API

Typeahead search that suggests search terms, podcasts, and genres as a user types - ideal for building autocomplete boxes for podcast search interfaces.

- **Human URL:** [https://www.listennotes.com/api/docs/](https://www.listennotes.com/api/docs/)
- **Base URL:** `https://listen-api.listennotes.com/api/v2`

#### Tags

- Typeahead
- Autocomplete
- Search

### Listen Notes Trending & Related Searches API

Fetch trending search terms across the platform and related search terms for a given query, useful for surfacing popular topics and expanding discovery.

- **Human URL:** [https://www.listennotes.com/api/docs/](https://www.listennotes.com/api/docs/)
- **Base URL:** `https://listen-api.listennotes.com/api/v2`

#### Tags

- Trending
- Related Searches
- Search

### Listen Notes Podcasts API

Fetch detailed metadata and paginated episodes for a podcast by id, batch fetch basic metadata for multiple podcasts by id, and pull a random podcast episode (Just Listen) for serendipitous discovery.

- **Human URL:** [https://www.listennotes.com/api/docs/](https://www.listennotes.com/api/docs/)
- **Base URL:** `https://listen-api.listennotes.com/api/v2`

#### Tags

- Podcasts
- Metadata
- Directory

### Listen Notes Episodes API

Fetch detailed metadata for a single episode by id, and batch fetch basic metadata for multiple episodes by id in one request.

- **Human URL:** [https://www.listennotes.com/api/docs/](https://www.listennotes.com/api/docs/)
- **Base URL:** `https://listen-api.listennotes.com/api/v2`

#### Tags

- Episodes
- Metadata
- Directory

### Listen Notes Best Podcasts API

Fetch curated best-podcasts charts by genre, region, publisher region, and language - the editorial and popularity-ranked lists that power podcast discovery experiences.

- **Human URL:** [https://www.listennotes.com/api/docs/](https://www.listennotes.com/api/docs/)
- **Base URL:** `https://listen-api.listennotes.com/api/v2`

#### Tags

- Best Podcasts
- Charts
- Directory

### Listen Notes Curated Lists API

Fetch paginated curated lists of podcasts hand-assembled around themes and topics from around the web, and retrieve the podcasts inside a specific curated list by id.

- **Human URL:** [https://www.listennotes.com/api/docs/](https://www.listennotes.com/api/docs/)
- **Base URL:** `https://listen-api.listennotes.com/api/v2`

#### Tags

- Curated Lists
- Recommendations
- Directory

### Listen Notes Playlists API

Fetch your Listen Later playlists and the items (episodes or podcasts) inside a specific playlist by id, letting apps read the playlists a user builds on Listen Notes.

- **Human URL:** [https://www.listennotes.com/api/docs/](https://www.listennotes.com/api/docs/)
- **Base URL:** `https://listen-api.listennotes.com/api/v2`

#### Tags

- Playlists
- Listen Later
- Directory

### Listen Notes Genres, Regions & Languages API

Fetch the reference vocabularies used across the API - the full podcast genre taxonomy, the supported countries/regions for best-podcasts charts, and the supported podcast languages.

- **Human URL:** [https://www.listennotes.com/api/docs/](https://www.listennotes.com/api/docs/)
- **Base URL:** `https://listen-api.listennotes.com/api/v2`

#### Tags

- Genres
- Regions
- Languages

### Listen Notes Recommendations API

Fetch similar-content recommendations for a given podcast or a given episode, powering "you might also like" discovery surfaces.

- **Human URL:** [https://www.listennotes.com/api/docs/](https://www.listennotes.com/api/docs/)
- **Base URL:** `https://listen-api.listennotes.com/api/v2`

#### Tags

- Recommendations
- Discovery
- Directory

### Listen Notes Podcast Audience Insights API

Fetch audience demographics and insights for a podcast by id, and list the podcasts associated with a publisher's domain name - the analytics surface for understanding a show's reach and a publisher's catalog.

- **Human URL:** [https://www.listennotes.com/api/docs/](https://www.listennotes.com/api/docs/)
- **Base URL:** `https://listen-api.listennotes.com/api/v2`

#### Tags

- Insights
- Audience
- Demographics

### Listen Notes Podcaster API

Endpoints for podcasters to improve the Listen Notes database - submit a podcast by RSS URL, force a refresh of a podcast's RSS feed, and request removal of a podcast.

- **Human URL:** [https://www.listennotes.com/api/docs/](https://www.listennotes.com/api/docs/)
- **Base URL:** `https://listen-api.listennotes.com/api/v2`

#### Tags

- Podcaster
- Submit
- RSS

## Common Properties

- [GitHub Organization](https://github.com/ListenNotes)
- [LinkedIn](https://www.linkedin.com/company/listen-notes)
- [Website](https://www.listennotes.com/api/)
- [Documentation](https://www.listennotes.com/api/docs/)
- [Plans](plans/listennotes-plans-pricing.yml)
- [Rate Limits](rate-limits/listennotes-rate-limits.yml)
- [Fin Ops](finops/listennotes-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
