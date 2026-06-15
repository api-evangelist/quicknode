# QuickNode (quicknode)

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
