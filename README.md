# QuickNode (quicknode)

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

QuickNode is a multi-chain Web3 infrastructure provider supporting 77+ blockchains via JSON-RPC, REST, and gRPC. Core products include high-performance RPC nodes, Streams (real-time event streaming), Webhooks, IPFS, a Key-Value Store, and a Marketplace of add-ons.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/apis.yml)

## Tags

- Web3
- Blockchain
- RPC
- Streams
- IPFS
- Multi-chain

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-29

## APIs

### QuickNode Core RPC API

Multi-chain JSON-RPC, REST, and gRPC endpoints across 77+ blockchains (Ethereum, Solana, Polygon, Arbitrum, Optimism, Base, Bitcoin, Aptos, Avalanche, BNB, etc.).

- **Human URL:** [https://www.quicknode.com/docs](https://www.quicknode.com/docs)
- **Base URL:** `https://{endpoint-name}.{network}.quiknode.pro/{token}`

#### Tags

- JSON-RPC
- WebSocket
- gRPC
- Multi-chain

#### Properties

- [Documentation](https://www.quicknode.com/docs)
- [AsyncAPI](asyncapi/quicknode-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/quicknode-ipfs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quicknode-ipfs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/quicknode-key-value-store.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quicknode-key-value-store.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/quicknode-streams.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quicknode-streams.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### QuickNode Streams

Real-time blockchain data streaming with custom filters and webhook delivery.

- **Human URL:** [https://www.quicknode.com/docs/streams/getting-started](https://www.quicknode.com/docs/streams/getting-started)
- **Base URL:** `https://api.quicknode.com/streams/rest/v1`

#### Tags

- REST
- Streaming

#### Properties

- [Documentation](https://www.quicknode.com/docs/streams/getting-started)
- [OpenAPI](openapi/quicknode-streams-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/quicknode-streams.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quicknode-streams.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### QuickNode Webhooks

Event-driven webhook subscriptions with custom filtering for blockchain events.

- **Human URL:** [https://www.quicknode.com/docs/quicknode-webhooks](https://www.quicknode.com/docs/quicknode-webhooks)
- **Base URL:** `https://api.quicknode.com/webhooks/rest/v1`

#### Tags

- REST
- Webhooks

#### Properties

- [Documentation](https://www.quicknode.com/docs/quicknode-webhooks)
- [Postman Collection](collections/quicknode-ipfs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quicknode-ipfs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/quicknode-key-value-store.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quicknode-key-value-store.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/quicknode-streams.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quicknode-streams.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### QuickNode IPFS API

REST API for uploading, pinning, and retrieving content on IPFS.

- **Human URL:** [https://www.quicknode.com/docs/ipfs/getting-started](https://www.quicknode.com/docs/ipfs/getting-started)
- **Base URL:** `https://api.quicknode.com/ipfs/rest/v1`

#### Tags

- REST
- IPFS

#### Properties

- [Documentation](https://www.quicknode.com/docs/ipfs/getting-started)
- [OpenAPI](openapi/quicknode-ipfs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/quicknode-ipfs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quicknode-ipfs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### QuickNode Key-Value Store

REST API for large-scale dataset storage and retrieval keyed by string identifiers.

- **Human URL:** [https://www.quicknode.com/docs/key-value-store](https://www.quicknode.com/docs/key-value-store)
- **Base URL:** `https://api.quicknode.com/kv/rest/v1`

#### Tags

- REST
- Storage

#### Properties

- [Documentation](https://www.quicknode.com/docs/key-value-store)
- [OpenAPI](openapi/quicknode-key-value-store-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/quicknode-key-value-store.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quicknode-key-value-store.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### QuickNode Marketplace Add-ons

Catalog of opt-in add-on APIs (NFT API, Token API, DeFi API, Functions, etc.) attached to a QuickNode endpoint.

- **Human URL:** [https://marketplace.quicknode.com/](https://marketplace.quicknode.com/)
- **Base URL:** `https://{endpoint}.quiknode.pro/{token}`

#### Tags

- Marketplace
- Add-ons

#### Properties

- [Documentation](https://marketplace.quicknode.com/)
- [Postman Collection](collections/quicknode-ipfs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quicknode-ipfs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/quicknode-key-value-store.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quicknode-key-value-store.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/quicknode-streams.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quicknode-streams.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### QuickNode Functions

Serverless on-chain logic runtime for executing custom code triggered by Streams or HTTP.

- **Human URL:** [https://www.quicknode.com/docs/functions](https://www.quicknode.com/docs/functions)
- **Base URL:** `https://api.quicknode.com/functions/rest/v1`

#### Tags

- REST
- Serverless

#### Properties

- [Documentation](https://www.quicknode.com/docs/functions)
- [Postman Collection](collections/quicknode-ipfs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quicknode-ipfs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/quicknode-key-value-store.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quicknode-key-value-store.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/quicknode-streams.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quicknode-streams.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/quiknode-labs)
- [LinkedIn](https://www.linkedin.com/company/quicknode)
- [Website](https://www.quicknode.com/)
- [Plans](plans/quicknode-plans-pricing.yml)
- [Rate Limits](rate-limits/quicknode-rate-limits.yml)
- [Fin Ops](finops/quicknode-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
