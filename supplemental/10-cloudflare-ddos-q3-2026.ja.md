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

[English](10-cloudflare-ddos-q3-2026.md)

## 位置付け・観測境界

| Field | Boundary |
|---|---|
| Publication | 2026-10-29 |
| Observation | Q3 2026, Cloudflare network |
| Population | Mitigated network-layer DDoS attacks; HTTP DDoS requests are a separate unit |
| Method / bias | Publisher mitigation telemetry; not all Internet attacks or victim organizations |
| Verification | 2026-11-07; live page, no contemporaneous archive verified |

## 出典の事実

CloudflareはQ3にネットワーク層DDoS攻撃1,820万件を自動緩和したと報告しています。HTTP DDoSリクエスト14.4兆件は別の単位で、攻撃件数として加算しません。報告は短時間の高頻度攻撃への移行を説明し、1 Tbps超の攻撃はQ2比約69%減としています。ボットネット対策との因果関係は可能性として述べており、確定事実ではありません。

## 設計上の解釈・対応

最大帯域だけでなく、繰り返す短時間攻撃への自動緩和、DNS・UDP経路の可視性、サービス継続試験を重視します。H1ノートは残し、四半期と半期の件数を直接比較しません。

## ATT&CK

可用性への示唆であり、新たな手法対応付けは行いません。 [Existing crosswalk](../frameworks/mitre-attack.md)

## 制約・不明点

ベンダーの観測範囲と検知定義に依存します。攻撃件数は侵害数・被害組織数ではなく、世界全体への一般化はできません。

## 一次資料

- [Official report — 2026-10-29](https://blog.cloudflare.com/ddos-threat-report-2026-q3/)
