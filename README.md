# Anduril Industries (anduril)

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

Anduril Industries builds AI-defined defense products that pair purpose-built
hardware with the Lattice software platform to give operators a unified,
machine-speed view of the battlespace. The company's portfolio spans autonomous
air, ground, and maritime systems (Ghost, Anvil, Bolt, ALTIUS, Dive-LD,
Roadrunner) along with command-and-control software and counter-UAS systems.
Lattice OS is the connective tissue: it ingests sensor and effector data across
vendors and exposes it as a common data fabric for both Anduril operators and
partner developers. A public Lattice Developer Portal and multi-language SDKs
(Python, Go, Java, JavaScript) document the Entities, Tasks, and Objects APIs
for partners integrating sensors, effectors, and mission applications. Access to
live Lattice environments is partner-gated and subject to U.S. export controls
(ITAR/EAR).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/anduril/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/anduril/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Defense
- Autonomy
- Lattice
- Command and Control
- C2
- Sensors
- Effectors
- Counter-UAS
- Unmanned Systems
- Mission Software
- Edge AI
- ITAR

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Anduril Lattice SDK

The Lattice SDK provides programmatic access to Anduril's Lattice platform
so partners can publish entities, issue tasks to connected agents, and
exchange binary objects across a shared mission data fabric. The SDK
supports both REST/JSON and gRPC/Protobuf transports, with OAuth client
credentials or bearer-token authentication. Live API access is gated to
qualified defense partners under export-control restrictions.

- **Human URL:** [https://developer.anduril.com/](https://developer.anduril.com/)
- **Base URL:** `https://developer.anduril.com`

#### Tags

- Lattice
- Entities
- Tasks
- Objects
- gRPC
- REST
- Defense SDK
- Mission Autonomy

#### Properties

- [Documentation](https://developer.anduril.com/)
- [API Reference](https://developer.anduril.com/reference/overview/overview)
- [Concepts](https://developer.anduril.com/guides/concepts/overview)
- [Product Page](https://www.anduril.com/lattice/lattice-sdk/)
- [S D K Python](https://github.com/anduril/lattice-sdk-python)
- [S D K Go](https://github.com/anduril/lattice-sdk-go)
- [S D K Java](https://github.com/anduril/lattice-sdk-java)
- [S D K Java Script](https://github.com/anduril/lattice-sdk-javascript)
- [Py P I](https://pypi.org/project/anduril-lattice-sdk/)
- [Schema Registry](https://buf.build/anduril/lattice-sdk)
- [GitHub Organization](https://github.com/anduril)
- [Postman Collection](collections/anduril.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/anduril.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.anduril.com/)
- [Developer Portal](https://developer.anduril.com/)
- [Lattice](https://www.anduril.com/lattice/)
- [Lattice S D K](https://www.anduril.com/lattice/lattice-sdk/)
- [Products](https://www.anduril.com/hardware/)
- [Careers](https://www.anduril.com/careers/)
- [Git Hub](https://github.com/anduril)
- [Schema Registry](https://buf.build/anduril/lattice-sdk)
- [LinkedIn](https://www.linkedin.com/company/anduril-industries/)
- [News](https://www.anduril.com/article/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
