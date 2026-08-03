# Aurora Networks

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Aurora Networks is the broadband and access networks brand of **Vistance Networks, Inc.** (Nasdaq: VISN) — the company CommScope renamed itself to in January 2026 after divesting its Connectivity and Cable Solutions segment to Amphenol. Aurora Networks builds end-to-end access network infrastructure for global cable and broadband service providers: HFC and PON access systems, cable headend optics platforms, CMTS/CCAP, Distributed Access Architecture (DAA) devices, optical hubs, nodes and passives, RF and RFoG equipment, and video processing, security and delivery systems. Its ServAssure NXT family adds network performance management, alarm handling and service assurance software.

## Lineage

- **1999** — Aurora Networks, Inc. founded in Santa Clara, CA as a pure-play optical transport supplier to cable operators. Backed by Battery Ventures among ten investors, ~$60M raised.
- **2013** — Acquired by Pace plc for $323M.
- **2016** — Pace merged into ARRIS.
- **2019** — ARRIS acquired by CommScope.
- **Jan 2026** — CommScope divests Connectivity and Cable Solutions to Amphenol, renames itself Vistance Networks, and rebrands its Access Networks Solutions business as **Aurora Networks**.

Backed by: battery-ventures

## API surface

**Aurora Networks is a network equipment vendor, not an API provider.** As of the 2026-07-19 enrichment pass it publishes:

- No public developer portal, API reference, or machine-readable API specification (OpenAPI/AsyncAPI/GraphQL/Protobuf).
- No first-party SDKs or CLI on npm, PyPI, or other public registries.
- No `/.well-known/` discovery documents (all probes 404).
- No status page, trust center, or vulnerability disclosure program.

Product and integration documentation — including the ServAssure NXT web service API and message bus referenced in product literature — sits behind authenticated customer portals (`mysupport.auroranetworks.com`, `docs.vistancenetworks.com`).

## Artifacts

| Path | Type | Method |
|---|---|---|
| `llms/aurora-networks-llms.txt` | LLMsTxt | searched (verbatim from vistancenetworks.com/llms.txt) |
| `well-known/aurora-networks-well-known.yml` | well-known probe record | probed (all 404) |
| `security/aurora-networks-domain-security.yml` | DomainSecurity | probed |
