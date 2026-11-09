# Change report / 差分報告

## 2026-11-09 JST — publication maintenance / 公開準備

- Preserve the October 31 evidence cutoff, November 7 initial verification and limited November 8 follow-up checks. This maintenance pass is not a new full source audit.
- Update both root READMEs: the MDDR 2026 / Cloudflare Q3 additions and CHANGELOG are already present; Japanese editions remain pending only for the five older conference notes.
- Preserve the six exact-URL link-check exceptions added on November 8 after browser verification. Earlier statements that no configuration changed describe the November 7 draft, not the entire integrated branch. Source-monitor configuration remains unchanged.
- The six exact-URL exceptions are based on the earlier CI 403 responses and separate browser reads recorded in the verification ledger; they do not establish a passing link check. The last observed pre-publication run (42466384758) failed downloading Lychee before checking links. Publication and current-head results are tracked on the pull request and Actions, not inferred from historical passing runs.

10月31日の情報締切、11月7日の初回確認、11月8日の限定確認を保持し、全面再監査とは扱いません。英日READMEの古い保守案内を修正。11月8日の6 URL完全一致の検査例外は保持し、監視設定は変更しません。6 URLの例外は過去のCI 403と台帳の通常ブラウザ確認に基づくもので、リンク検査合格の証拠ではありません。公開前に最後に確認した実行（42466384758）はLychee取得時に失敗。公開・最新コミットのCI状態はPRとActionsで確認します。

## 2026-10-31 evidence cutoff — verified 2026-11-07 JST

- Added ten conference summaries in English/Japanese (20 files): NVIDIA GTC, Google Cloud Next/GCP, Anthropic Code with Claude San Francisco, Google I/O, Microsoft Build/Azure, AWS Summit Los Angeles, Meta Connect, OpenAI DevDay, Oracle AI World/OCI, GitHub Universe.
- Added MDDR 2026 release-summary review and Cloudflare DDoS Q3 2026 in English/Japanese (4 files), with observation boundaries and separate source facts / repository interpretation.
- Added bilingual October security synthesis (2 files), preserving the prior consensus matrix baseline and existing evidence.
- Updated both READMEs with event-start-date descending conference links and correctly sorted reverse-chronological monthly timelines. Existing links remain; Fortinet moves from unknown month to April 30 using its official release.
- Updated report/supplement indexes, SOURCES.md, and a dedicated date/URL verification ledger. No configuration changes; the monitor retains its September baseline and can still flag now-reviewed editions.

## 日本語

会議10件を英日20ファイル、MDDR 2026公開要約とCloudflare DDoS Q3を英日4ファイル、10月セキュリティ動向を英日2ファイル追加。READMEは開催開始日の降順リンクと月内の逆時系列を整備し、旧リンクを保持。Fortinet公開日を4月30日に補正しました。資料索引・台帳・検証記録を更新し、旧横断分析の基準日は保持しています。

## Limits / 制約

Sources are mutable official pages checked on November 7; no archived October 31 page-state reconstruction. Unknown publication dates and Anthropic's inconsistent event-page duration are explicit. MDDR review covers public summary/landing pages, not every PDF chapter. Existing report metrics and five older English-only conference notes are retained without a new full audit. AWS re:Invent and Microsoft Ignite are after the cutoff. Framework mappings and cloud guidance were not fully revalidated.

確認は11月7日の公式ライブページで、10月31日時点の完全復元ではありません。公開日不明・Anthropic会期表記の不整合は明記。MDDRは公開要約・案内ページの確認です。旧統計・旧会議5件・フレームワーク・クラウドガイダンスの全面再監査ではありません。re:InventとIgniteは締切後のため総括対象外です。

No private files or credentials are included. Source-monitor configuration is unchanged. Integration/publishing results are recorded separately below. / 私的ファイル・認証情報は含めず、source-monitor設定は変更しません。統合・公開結果は以下に分けて記録します。

## Previous checks — November 7 / 11月7日の検査記録

- PASS: 13 bilingual pairs (26 new note files); English/Japanese metadata and source-URL parity.
- PASS: local Markdown targets across 78 files; 15 conference links per README in ascending start-date order; monthly timelines in descending date order; original README link targets preserved.
- PASS: evidence-cutoff and actual-verification dates for all new evidence notes; `git diff --check`.
- Public source content/date checks: see the verification ledger; dynamic-page inconsistencies and redirects are recorded. No full-repository external-link crawl or CI workflow run.
- Scope: 28 new files and 8 modified files, all Markdown. No configuration files changed.

英日13ペア、内部リンク、開催日順、月内日付順、旧READMEリンク保持、締切・確認日、差分空白検査は合格。公開URLの内容確認は台帳参照。全外部リンク巡回・CI起動は未実施です。追加28・変更8ファイル、すべてMarkdownです。

## November 8 integration / 11月8日の統合

- Both root READMEs now list conferences newest-first as well as monthly timeline entries.
- Preserve PR #2's bilingual October conference evidence refresh, Black Hat evidence correction, and source/README links alongside the 36-file draft.
- The evidence cutoff remains October 31. A limited November 8 source recheck and extraction limits are recorded in the verification ledger; unchanged November 7 claims are not labeled newly verified.
- No source-monitor schedule/configuration changes or manual source-monitor execution.
- Local integration validation: PASS across 96 Markdown files, 436 relative links, 14 English/Japanese metadata/source-URL pairs, both 15-event descending conference indexes and 33-entry descending timelines, balanced fences, no conflict markers, and original README links retained. The November 7 results above remain historical.
- Current-head CI and publication state are recorded by the pull request checks and Git history, not inferred from the old successful run.

英日READMEの会議一覧を降順化。既存36ファイルとPR #2を統合し、情報締切と実確認日を分離。96ファイル・相対リンク436件・英日14ペア・降順・旧リンク保持のローカル検査は合格。CIと公開状態はPRチェック・Git履歴で確認します。
