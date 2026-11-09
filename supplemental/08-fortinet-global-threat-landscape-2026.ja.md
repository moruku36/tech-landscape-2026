---
publisher: "FortiGuard Labs / Fortinet"
edition: "2026 Global Threat Landscape Report"
publication_date: "2026-04-30"
observation_period: "2025"
language: "ja"
translation_of: "08-fortinet-global-threat-landscape-2026.md"
primary_source: "https://www.fortinet.com/resources/reports/threat-landscape-report"
last_verified: "2026-09-27"
---

# Fortinet 2026 Global Threat Landscape Report — 日本語解説

[English](08-fortinet-global-threat-landscape-2026.md)

## 追加する価値

FortinetはNetwork / Security Infrastructure寄りの視点から、**Exploit Velocity / Automated Attack Volume / Stolen Identity / Legitimate Tool Abuse / Machine-speed Operation**を補います。

## 主要データ

- FortiGuard Labsは2025年に**1,220億回のExploitation Attempt**を観測。
- Vulnerability DisclosureからExploitationまでが「Weeks」ではなく**Hours / Days**単位へ。
- Stolen IdentityとLegitimate Tool Abuseが主要論点。
- AI/AutomationがNetwork / Cloud / Hybrid / Endpoint全体でAttack VolumeとSpeedを拡大。
- Riskを「Attacker Sophistication」より**DefenderとのSpeed Gap**として捉える。

Fortinet Landing Page上でDynamic Renderingされ、Official Textとして数値を確実に取得できない指標は、このRepositoryでは無理に転記していません。

## Architecture上の意味

### Monthly Patchだけでは不足

Hours単位でExploitされるなら、

- Internet-facing Service
- Edge Device
- Remote Access
- Management Plane

にはEmergency Remediation Laneが必要です。

### Legitimate Tool Abuse

Signatureだけでなく、

- Identity
- Privilege
- Context
- Destination
- Sequence
- Command Lineage

を見ます。

### Network Telemetry

EndpointだけでなくFirewall / VPN / DNS / Network FlowをDetection Engineeringへ統合します。

## 優先アクション

- Internet-facing Critical Asset向けExploit Response SLA
- Emergency Isolation / Compensating Control
- Network + Identity + Cloud + Endpoint Correlation
- Legitimate Admin ToolのBehavior Detection
- CVSSだけでなくActive ExploitationをPriorityへ
- High-confidence ScenarioのAutomated Enrichment / Containment

## Primary Source

- https://www.fortinet.com/resources/reports/threat-landscape-report

## 公開日の検証

公開日補足（2026-11-07確認）: 公式発表は2026-04-30。今回の再確認は公開日と公式発表の範囲で、既存本文全体の再検証日を更新したものではありません。

- [Official release](https://investor.fortinet.com/news-releases/news-release-details/fortinet-2026-global-threat-landscape-report-reveals-surge-ai/)
