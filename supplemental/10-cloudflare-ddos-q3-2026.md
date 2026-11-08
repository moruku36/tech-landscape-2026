---
publisher: "Cloudflare / Cloudforce One"
edition: "DDoS Threat Report 2026 Q3"
publication_date: "2026-10-29"
observation_period: "Q3 2026"
dataset_or_scope: "Cloudflare network DDoS mitigation telemetry"
geography: "Global network visibility; customer and network selection bias"
primary_source: "https://blog.cloudflare.com/ddos-threat-report-2026-q3/"
evidence_cutoff: "2026-10-31"
last_verified: "2026-11-07"
---

# Cloudflare DDoS Threat Report 2026 Q3

[日本語版](10-cloudflare-ddos-q3-2026.ja.md)

## Positioning and evidence profile

| Field | Boundary |
|---|---|
| Publication | 2026-10-29 |
| Observation | Q3 2026, Cloudflare network |
| Population | Mitigated network-layer DDoS attacks; HTTP DDoS requests are a separate unit |
| Method / bias | Publisher mitigation telemetry; not all Internet attacks or victim organizations |
| Verification | 2026-11-07; live page, no contemporaneous archive verified |

## Source facts

Cloudflare reports autonomously mitigating 18.2 million network-layer DDoS attacks in Q3. Its 14.4 trillion HTTP DDoS requests are a separate unit and must not be added to attack counts. It describes shorter, frequent attacks and nearly 69% fewer attacks exceeding 1 Tbps than Q2. Botnet disruption is a possible explanation, not proven causality.

## Architecture interpretation and actions

Test automatic mitigation of repeated short bursts, DNS/UDP visibility, and service continuity alongside peak-bandwidth capacity. Preserve the H1 note; do not directly compare quarterly and half-year counts.

## ATT&CK

This is an availability signal; no new technique mapping is asserted. [Existing crosswalk](../frameworks/mitre-attack.md)

## Limitations and unknowns

Counts depend on vendor coverage and detection definitions. They are not breaches or unique victim organizations and cannot be generalized to the whole Internet.

## Sources

- [Official report — 2026-10-29](https://blog.cloudflare.com/ddos-threat-report-2026-q3/)
