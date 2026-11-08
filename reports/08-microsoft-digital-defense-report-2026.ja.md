---
publisher: "Microsoft"
edition: "Microsoft Digital Defense Report 2026"
publication_date: "2026-10-01"
observation_period: "Varies by series; country map 2025-07-01 to 2026-06-30; no single window assumed"
dataset_or_scope: "Microsoft telemetry / threat intelligence; public release summary and landing page"
geography: "Global Microsoft visibility; not a representative census"
primary_source: "https://www.microsoft.com/en-us/security/blog/2026/10/01/insights-from-the-2026-microsoft-digital-defense-report/"
evidence_cutoff: "2026-10-31"
last_verified: "2026-11-07"
---

# Microsoft Digital Defense Report 2026

[English](08-microsoft-digital-defense-report-2026.md)

## 位置付け・観測境界

10月1日の公式公開要約とレポート案内ページを確認しました。2025年版は履歴として保持します。PDF全章を検証したものではありません。

| 項目 | 範囲 |
|---|---|
| Observation period | Country map: 2025-07-01–2026-06-30; other series vary |
| Population / method | Microsoft product telemetry and threat intelligence; series-specific populations |
| Geography / bias | Global publisher visibility; customer and detection selection bias |
| Verification | 2026-11-07; evidence cutoff 2026-10-31; live pages, no archived snapshot |

## 出典の事実・主要所見

Microsoftは、攻撃者が偵察・ソーシャルエンジニアリング・マルウェア／エクスプロイト開発・侵害後処理にAIを利用し、多くは既存攻撃工程の一部を支援していると述べています。案内ページは人間と認証情報が主要な入口であること、エージェントIDの統制、システム間の可視性とレジリエンスを強調しています。数値は母集団を取り違えないよう本ノートでは追加しません。

## 設計上の解釈・対応

既存の5平面モデルを維持します。IDでは常設特権を減らし、Control/Dataではツール認可を制約し、Recoveryでは依存先を切り離した復旧を試験し、Telemetryでは人・エージェント・クラウドの記録を関連付けます。これはリポジトリの提案で、効果測定結果ではありません。

## ATT&CK

今回は新たな手法対応付けを確定しません。既存の対応表は分析として参照します。 [ATT&CK](../frameworks/mitre-attack.md)

## 制約・不明点

系列ごとに期間・分母が異なります。国別地図の期間を全レポートへ適用しません。既存の横断マトリクスのMicrosoft列は2025年版のままとし、新版だけで他社横断の合意を再計算しません。

## 一次資料

- [Release summary — 2026-10-01](https://www.microsoft.com/en-us/security/blog/2026/10/01/insights-from-the-2026-microsoft-digital-defense-report/)
- [Report landing page — publication date not stated](https://www.microsoft.com/en-us/corporate-responsibility/topics/cybersecurity/reports/microsoft-digital-defense-report/)
