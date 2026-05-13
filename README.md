# Available .TUBE One-Word Domains (11,877)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C877%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .tube one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,877 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,877 domains · **Median ask:** $42.18 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-13  
**Canonical page:** `https://unique.domains/domains/tld/tube`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/tube?utm_source=github&utm_medium=referral&utm_campaign=repo_tube_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./tube.csv">CSV</a> / <a href="./tube.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_tube_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tube_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .TUBE search](https://unique.domains/domains/tld/tube?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_tube_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .TUBE search](https://unique.domains/domains/tld/tube?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_tube_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tube_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .TUBE one-word domain catalog.

### Files

- `tube.csv` — public CSV extract (1,000 rows)
- `tube.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/tube-oneword-domains/main/tube.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| IsleofMan.tube     | available | $33.98    | —             | 62             | 91     | 11     | namecheap       |
| makers.tube        | resell    | —         | —             | 62             | 67     | 6      | IONOS SE        |
| donuts.tube        | premium   | $62.50    | —             | 54             | 62     | 6      | name.com        |
| keepthechange.tube | available | $33.98    | —             | 46             | 59     | 15     | namecheap       |
| brain.tube         | resell    | —         | —             | 72             | 48     | 5      | NameCheap, Inc. |
| Books.tube         | premium   | $525      | $28           | 52             | 49     | 5      | namecheap       |
| teams.tube         | available | $33.98    | —             | 62             | 32     | 5      | namecheap       |
| justin.tube        | premium   | $125      | —             | 58             | 38     | 7      | name.com        |
| letsgo.tube        | available | $33.98    | —             | 57             | 31     | 7      | namecheap       |
| WiFi.tube          | premium   | $140      | $28           | 83             | 37     | 5      | namecheap       |
| inspiration.tube   | available | $33.98    | —             | 88             | 30     | 11     | namecheap       |
| stories.tube       | premium   | $62.50    | —             | 58             | 36     | 7      | name.com        |
| trades.tube        | available | $23.99    | $23.99        | 71             | 26     | 6      | namesilo        |
| homes.tube         | premium   | $62.50    | —             | 86             | 34     | 5      | name.com        |
| sites.tube         | available | $33.98    | —             | 53             | 26     | 5      | namecheap       |
| etc.tube           | premium   | $62.50    | —             | 58             | 34     | 3      | name.com        |
| whats.tube         | available | $23.99    | $23.99        | 58             | 24     | 5      | namesilo        |
| Jim.tube           | premium   | $525      | $28           | 78             | 28     | 3      | namecheap       |
| inhouse.tube       | available | $33.98    | —             | 70             | 23     | 8      | namecheap       |
| comics.tube        | premium   | $125      | —             | 68             | 24     | 6      | name.com        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,877 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/tube?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_tube_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/tube?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_tube_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_tube_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection is entirely made up of one-word .tube domains. The set leans toward concise dictionary words and broad commercial terms, with examples such as chart.tube, capital.tube, feature.tube, firm.tube, and elegant.tube. For founders, the key question is whether the word remains memorable and credible when paired with .tube. For investors, the main test is whether the keyword has clear resale logic beyond novelty. With a median ask of 42.18, entry pricing appears low, but .tube is a niche extension, so end-user fit matters more than volume alone. Favor names where the word and extension create a natural phrase or category signal.

- One-word .tube domains only
- 11,875 domains in this selection
- Median ask: 42.18
- Best fit when word + .tube reads naturally

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .TUBE One-Word Domains*. Version 2026-05-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .TUBE page](https://unique.domains/domains/tld/tube?utm_source=github&utm_medium=referral&utm_campaign=repo_tube_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_tube_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_tube_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tube_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
