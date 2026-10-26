# Listen Notes (listennotes)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
