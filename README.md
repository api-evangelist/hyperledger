# Hyperledger (hyperledger)

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

Hyperledger is an open source collaborative effort created to advance cross-industry blockchain technologies, originally hosted under the Linux Foundation and now stewarded by LF Decentralized Trust. It hosts enterprise-grade blockchain frameworks including Fabric, Besu, Indy, Iroha, and Cacti, along with tools like Firefly and Caliper for blockchain development, identity, and operations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hyperledger/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hyperledger/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Blockchain
- Distributed Ledger
- Enterprise
- Linux Foundation
- Smart Contracts

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Hyperledger Besu API

Hyperledger Besu is an Ethereum client written in Java exposing JSON-RPC APIs for blockchain interaction including admin, debug, eth, net, web3, txpool, miner, and trace namespaces.

- **Human URL:** [https://besu.hyperledger.org/](https://besu.hyperledger.org/)
- **Base URL:** `https://besu.example.com`

#### Tags

- Blockchain
- Ethereum
- Json-Rpc
- Smart Contracts

#### Properties

- [Documentation](https://besu.hyperledger.org/public-networks/reference/api)
- [Git Hub](https://github.com/hyperledger/besu)
- [OpenAPI](openapi/hyperledger-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperledger.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperledger.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hyperledger Fabric API

Hyperledger Fabric is a permissioned distributed ledger platform. Programmatic access is provided via the Fabric Gateway, peer gRPC APIs, and SDKs for chaincode invocation, ledger queries, and channel administration.

- **Human URL:** [https://hyperledger-fabric.readthedocs.io/](https://hyperledger-fabric.readthedocs.io/)

#### Tags

- Blockchain
- Distributed Ledger
- Permissioned
- Smart Contracts

#### Properties

- [Documentation](https://hyperledger-fabric.readthedocs.io/en/latest/)
- [Gateway Docs](https://hyperledger.github.io/fabric-gateway/)
- [Git Hub](https://github.com/hyperledger/fabric)
- [Postman Collection](collections/hyperledger.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperledger.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hyperledger FireFly API

Hyperledger FireFly is a multiparty system orchestration framework providing REST APIs for tokens, messages, identities, contracts, and events across multiple blockchain protocols.

- **Human URL:** [https://hyperledger.github.io/firefly/](https://hyperledger.github.io/firefly/)

#### Tags

- Blockchain
- Multiparty
- Tokens
- Web3

#### Properties

- [Documentation](https://hyperledger.github.io/firefly/latest/reference/api/)
- [Git Hub](https://github.com/hyperledger/firefly)
- [Postman Collection](collections/hyperledger.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperledger.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hyperledger Indy API

Hyperledger Indy provides tools, libraries, and reusable components for decentralized identities rooted on blockchains. APIs are exposed via the Indy SDK and Indy Node REST endpoints.

- **Human URL:** [https://www.hyperledger.org/projects/hyperledger-indy](https://www.hyperledger.org/projects/hyperledger-indy)

#### Tags

- Decentralized Identity
- Did
- Identity
- Self-Sovereign Identity

#### Properties

- [Documentation](https://hyperledger-indy.readthedocs.io/)
- [Git Hub](https://github.com/hyperledger/indy-node)
- [Postman Collection](collections/hyperledger.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperledger.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hyperledger Cacti API

Hyperledger Cacti (formerly Cactus) is a pluggable enterprise-grade framework for cross-chain transactions, providing connector plugins and REST APIs for interoperability across DLTs.

- **Human URL:** [https://hyperledger-cacti.github.io/cacti/](https://hyperledger-cacti.github.io/cacti/)

#### Tags

- Blockchain
- Interoperability
- Cross-Chain

#### Properties

- [Documentation](https://hyperledger-cacti.github.io/cacti/)
- [Git Hub](https://github.com/hyperledger/cacti)
- [Postman Collection](collections/hyperledger.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperledger.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/hyperledger-project)
- [Documentation](https://www.hyperledger.org/use)
- [L F Decentralized Trust](https://lfdecentralizedtrust.org/)
- [Git Hub Org](https://github.com/hyperledger)
- [L F D T Git Hub](https://github.com/LF-Decentralized-Trust)
- [Wiki](https://wiki.lfdecentralizedtrust.org/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
