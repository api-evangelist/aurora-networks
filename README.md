# Aurora Networks

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
