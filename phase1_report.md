# Phase 1 search and verification report

**Project:** From Central Mandates to Local Adaptation: Policy Reinvention in China's Disaster Investigation and Evaluation System
**Target journal:** Journal of Chinese Governance
**Policy cutoff and search date:** November 5, 2026 (America/New_York)
**Protocol:** 1.0.0, amended to 1.0.1 before additional primary-source resolution searches

## Status

The bounded search pass covers **all 31 mainland provincial-level regions**. It is **not a fully verified or exhaustive policy census**: unresolved primary sources, blocked downloads, missing metadata and a dynamic consultation page remain. Phase 1 verification is therefore **not complete**. No statistical analysis, policy-reinvention coding, or manuscript findings have been produced.

## Coverage counts

| Measure | Distinct provinces |
|---|---:|
| Searched with documented records | 31 |
| Verified formally issued provincial policies | 8 |
| Draft policies located, including one pending candidate | 6 |
| Of those, official consultation/draft existence verified | 5 |
| Other relevant official document (standard registry record) | 1 |
| No qualifying document located within the bounded search | 7 |
| Not yet searched | 0 |
| Require manual verification or archive/metadata follow-up | 28 |
| Unverified formal-policy leads, excluded from the formal-policy count | 11 |

Counts overlap: Beijing has a verified consultation notice and an unverified formal-policy lead; Xinjiang has verified evidence of prior consultation and an official technical-standard record. Draft counts do not imply that a formal successor does not exist. “Manual verification” includes missing originals, unresolved dates/numbers, unverified leads, incomplete draft/standard texts, and checks of apparently empty jurisdictions; it does not mean all 28 are suspected errors. These are workflow counts, not statistical analysis.

Verified formal-policy provinces: **山西省、黑龙江省、江西省、河南省、湖南省、广东省、云南省、甘肃省**. Verification concerns official notice/full-text evidence of issuance; original-file archival completeness and metadata completeness are separate fields.

## Search method and reproducibility

The province roster was created before searches. Each province received the same two broad official-domain discovery queries covering 暂行办法、实施办法、办法、工作规定 and 征求意见, followed by a quoted province/topic query and a province-title query. Where needed, additional targeted searches resolved specific leads. There were **152 provincial search executions**, four to six per province. Two national-baseline searches bring the root log to **154 rows**. The initial national-baseline response was not serialized; its query and date are retained, its exact timestamp is intentionally blank, and a later identical verification run is archived. All 152 provincial responses are preserved locally.

Official provincial government portals, government gazettes, emergency-management departments and policy repositories were prioritized. The search tool exposed ranked result sets, not complete pagination, database totals or proof of repository coverage. Queries and returned counts appear in `search_log.csv`; `logs/search_results.csv` retains individual returned URLs. Automated title triage and single-agent source review selected the candidate records; not every off-topic search hit received full-text review. Native internal searches of every provincial database/gazette were not completed. Search-engine omissions remain an important limitation.

Primary-source verification used government notices/full text, official government reproductions of provincial documents, and an official standards registry. Official news, interpretations, secondary copies, municipal instruments and national reprints were not treated as provincial formal issuance. Some government reproductions are on municipal/county portals: classification follows the document's issuing authority, not the hosting jurisdiction.

The national baseline is **国办发〔2025〕28号**, signed **2025-08-03**. The saved official reproduction was published **2025-08-07**. Post-mandate eligibility begins on the signed date. Earlier documents are antecedents rather than implementations of the new national measure. See the [official national text](https://www.forestry.gov.cn/c/www/szxx/637285.jhtml).

## Province-by-province disposition

Status labels below report the evidence located, not an inference that other policies are absent. Detailed titles, dates, URLs, provenance paths and limitations are in `provincial_policy_inventory.csv`.

| Province | Search runs | Disposition | Manual follow-up |
|---|---:|---|---|
| 北京市 | 4 | Consultation draft/history; Formal-policy lead: unverified | Yes |
| 天津市 | 4 | No qualifying document located (bounded search) | Yes |
| 河北省 | 6 | Formal-policy lead: unverified | Yes |
| 山西省 | 4 | Verified formal policy | Yes |
| 内蒙古自治区 | 6 | Formal-policy lead: unverified | Yes |
| 辽宁省 | 4 | Consultation draft/history | No current flag |
| 吉林省 | 5 | No qualifying document located (bounded search) | Yes |
| 黑龙江省 | 4 | Verified formal policy | Yes |
| 上海市 | 4 | Consultation draft/history | Yes |
| 江苏省 | 5 | Consultation draft/history | Yes |
| 浙江省 | 5 | No qualifying document located (bounded search) | Yes |
| 安徽省 | 6 | Formal-policy lead: unverified | Yes |
| 福建省 | 5 | No qualifying document located (bounded search) | Yes |
| 江西省 | 4 | Verified formal policy | Yes |
| 山东省 | 6 | Formal-policy lead: unverified | Yes |
| 河南省 | 4 | Verified formal policy | No current flag |
| 湖北省 | 5 | No qualifying document located (bounded search) | Yes |
| 湖南省 | 4 | Verified formal policy | Yes |
| 广东省 | 4 | Verified formal policy | Yes |
| 广西壮族自治区 | 6 | Formal-policy lead: unverified | Yes |
| 海南省 | 6 | Formal-policy lead: unverified | Yes |
| 重庆市 | 4 | Consultation draft/history (candidate only) | Yes |
| 四川省 | 6 | Formal-policy lead: unverified | Yes |
| 贵州省 | 6 | Formal-policy lead: unverified | Yes |
| 云南省 | 4 | Verified formal policy | Yes |
| 西藏自治区 | 5 | No qualifying document located (bounded search) | Yes |
| 陕西省 | 6 | Formal-policy lead: unverified | Yes |
| 甘肃省 | 4 | Verified formal policy | No current flag |
| 青海省 | 5 | No qualifying document located (bounded search) | Yes |
| 宁夏回族自治区 | 6 | Formal-policy lead: unverified | Yes |
| 新疆维吾尔自治区 | 5 | Consultation draft/history; Official standard registry; full text pending | Yes |

## Material verification issues

- **Beijing:** an official indexed result reports a notice signed 2026-11-04 and published on the cutoff date, 2026-11-05. Direct page access and original downloads failed. Its metadata are provisional and it is excluded from the eight verified formal policies. The April consultation notice was readable on the official portal.
- **Chongqing:** an official consultation title was located, but retrieval returned a dynamically populated shell without the notice body or dates. Retain a draft candidate; do not count it among the five confirmed draft/consultation histories.
- **Xinjiang:** the official feedback notice confirms consultation during 2026-03-31–2026-04-10. That feedback document is signed 2026-04-10 and its page is published 2026-06-24; neither is substituted for the missing draft's own date. The official standards platform separately records **DB65/T 5053-2026**, published 2026-07-24 and effective 2026-09-25. The standard's full text and direct relationship to the 2025 measures still require checking. Xinjiang Production and Construction Corps instruments are outside the 31-region provincial denominator and are not substituted for autonomous-region policies.
- **Guangdong and Yunnan:** wrapper “document date” fields conflict with the signed policy text. The inventory uses signed dates, respectively **2026-06-13** and **2025-12-07**, and retains the discrepancy in notes. Missing document numbers remain blank.
- **Hunan:** signed/issued date is **2026-07-31**, but an unambiguous webpage publication date was not established. The publication field is blank; it is not inferred from the URL.
- **Henan:** the original downloaded PDF is the entire **2026年第6号** provincial gazette, dated **2026-03-25**. The policy occupies **PDF pages 2–5**, ending before the next notice on page 5. The file, whole-gazette text and separate policy extraction are retained. Pages 2 and 5 were visually inspected to check title, document number, signed date and the boundary. This corrects the preliminary progress update that described the range as pages 2–4. The inventory's webpage publication date, 2026-02-03, refers to the separately preserved Shenqiu government reproduction.
- **Jiangsu:** the official consultation notice is verified. The tool's extracted attachment title appeared inconsistent with the linked provincial draft label; the PDF original could not be downloaded. The attachment remains a manual-verification item.
- **Shandong:** an official ministry news page describes a provincial policy, but the formal issuing text was not obtained. It remains a lead, not an “other implementation document” or verified formal policy.
- **Hebei, Inner Mongolia, Anhui, Guangxi, Hainan, Sichuan, Guizhou, Shaanxi and Ningxia:** secondary reproductions or links suggest formal instruments. Unverified metadata are explicitly marked. No secondary copy has been promoted to a verified government original.
- **Tianjin, Jilin, Zhejiang, Fujian, Hubei, Tibet and Qinghai:** no qualifying post-baseline instrument was located within this search. This is not evidence of policy absence. Government internal-search interfaces and gazettes need manual follow-up, including checks for pre-existing instruments that may have remained applicable.

## Download and evidence handling

HTTP 403/405/412 responses, connection timeouts and a certificate mismatch prevented some downloads. Failed attempts and one bounded retry of selected official pages are recorded in `metadata/download_log.csv`. Access controls and certificate checks were not bypassed. Original downloaded bytes carry SHA-256 digests; HTML extraction and PDF text are separate derived files. An HTTP success with an empty response shell is not treated as a policy original.

`data/raw/policy_documents/` contains successfully downloaded government source files. `data/raw/context/` holds the national baseline and antecedent news. `data/raw/secondary_leads/` and `data/raw/response_shells/` distinguish non-primary leads and unusable responses. `data/interim/web_snapshots/` contains browser-tool extracts, **not** downloaded originals; these can document source verification but cannot replace raw archival files. For blocked original downloads the inventory's `local_file_path` remains blank. All saved originals and derived paths were checked locally.

## Files and data dictionary

- `provincial_policy_inventory.csv`: **33 rows** covering 31 provinces, with additional rows for Beijing's draft and Xinjiang's technical standard. Includes all requested fields plus IDs, separate primary/lead URLs, evidence locators, hashes, manual-review flags and notes.
- `search_log.csv`: **154 actual search records**, including 152 provincial and two national searches. Every province has at least A/B/C/D runs; failed or empty outcomes remain visible.
- `AGENTS.md`: objectives, source standards, stage boundaries and integrity rules.
- Local support: `protocol/`, `logs/`, `metadata/`, original files, extracted text and rebuild scripts. These are available in the workspace; the requested GitHub commit is limited to the four user-named root deliverables. References to local support paths will require that local evidence package; the four-file commit alone is not a portable replication archive.

Dates are ISO 8601. Blank means unknown/not established, never “no date exists.” Publication dates refer to the specified source page unless notes say otherwise, not necessarily the first publication anywhere. `policy_status` and `verification_status` must be read together. `unverified_formal_policy_lead` is an additional uncertainty category preventing false formal-policy counts. `other_official_implementation_document` includes the one clearly labeled standards-registry record without assuming it is a governmental implementing measure.

## Verification performed and limits

Local checks confirmed the 31-region roster, A/B/C/D coverage for every province, unique query/record IDs, 33 inventory rows, valid CSV/JSON, cutoff compliance of populated dates, resolvable local evidence paths and original-file hashes. Counts were recalculated from the inventory. Source inspection was performed by one AI assistant; no independent human review, inter-rater reliability assessment or preregistration is claimed. AI was used for search orchestration, source triage, extraction, metadata transcription and report preparation.

## GitHub delivery

Target: [zhengrq1-design/china-disaster-policy-reinvention](https://github.com/zhengrq1-design/china-disaster-policy-reinvention).

Initial connector and command-line delivery attempts failed: the connector returned HTTP 404, HTTPS lacked credentials, and SSH returned `Permission denied (publickey)`. The four requested files were committed locally on `codex/phase1-policy-inventory`. Subsequent browser inspection confirmed that the repository exists and the signed-in account owns it. On 2026-11-05, the user explicitly confirmed making the repository public. The repository was changed to public, and delivery uses authenticated GitHub web-editor commits of the four requested files because the browser file-upload interface remained unavailable. The repository commit history is the authoritative record of completed delivery; this report does not claim that command-line Git authentication has been repaired. Supporting evidence remains local, and no remote history is to be overwritten.

## Remaining work

Resolve the manual-review queue before using this as a verified empirical census: obtain inaccessible primary notices and attachments, reconcile missing document numbers/publication dates, inspect the seven non-location jurisdictions' native repositories, verify draft-to-final transitions, and confirm the standard's scope. Then rebuild the inventory/report with an append-only decision trail. No manuscript interpretation should precede that verification.
