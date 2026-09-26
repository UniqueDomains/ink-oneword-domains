# Available .INK One-Word Domains (18,696)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-18%2C696%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .ink one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **18,696 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 18,696 domains · **Median ask:** $17.43 · **High-demand under $2,500:** 19

**Last updated:** 2026-09-26
**Canonical page:** `https://unique.domains/domains/tld/ink`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/ink?utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./ink.csv">CSV</a> / <a href="./ink.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .INK search](https://unique.domains/domains/tld/ink?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .INK search](https://unique.domains/domains/tld/ink?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .INK one-word domain catalog.

### Files

- `ink.csv`, public CSV extract (1,000 rows)
- `ink.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/ink-oneword-domains/main/ink.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain     | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                               |
| ---------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------------------- |
| fry.ink    | available | $2.98     | $43.98        | high           | low    | 3      | namecheap                                               |
| wizard.ink | resell    | $33.98    | —             | high           | medium | 6      | Sav.com LLC                                             |
| bja.ink    | premium   | $116      | $116          | medium         | low    | 3      | namesilo                                                |
| ugh.ink    | available | $2.99     | —             | medium         | low    | 3      | name.com                                                |
| she.ink    | resell    | —         | —             | high           | low    | 3      | Spaceship, Inc.                                         |
| cia.ink    | premium   | $116      | $116          | high           | medium | 3      | namesilo                                                |
| aare.ink   | available | $2.98     | $43.98        | high           | low    | 4      | namecheap                                               |
| boys.ink   | resell    | —         | —             | high           | low    | 4      | Spaceship, Inc.                                         |
| kid.ink    | premium   | $832      | $832          | high           | low    | 3      | namesilo                                                |
| acth.ink   | available | $2.99     | $32.49        | medium         | low    | 4      | namesilo                                                |
| call.ink   | resell    | —         | —             | high           | low    | 4      | DNSPod, Inc.                                            |
| lay.ink    | premium   | $116      | $116          | high           | low    | 3      | namesilo                                                |
| akan.ink   | available | $2.99     | $32.49        | high           | low    | 4      | namesilo                                                |
| chat.ink   | resell    | —         | —             | high           | medium | 4      | Alibaba Cloud Computing Ltd. d/b/a HiChina (www.net.cn) |
| lxi.ink    | premium   | $116      | $116          | medium         | low    | 3      | namesilo                                                |
| alas.ink   | available | $2.98     | $43.98        | high           | low    | 4      | namecheap                                               |
| dive.ink   | resell    | —         | —             | high           | low    | 4      | Spaceship, Inc.                                         |
| mid.ink    | premium   | $116      | $116          | high           | low    | 3      | namesilo                                                |
| alir.ink   | available | $2.98     | $43.98        | medium         | low    | 4      | namecheap                                               |
| nigh.ink   | resell    | —         | —             | medium         | low    | 4      | GoDaddy.com, LLC                                        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 18,696 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 19 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/ink?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/ink?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list of one-word .ink domains spans creative, product-style, and lifestyle names such as windowshop.ink, rumcake.ink, and solarpower.ink. With a median ask of $93, these domains sit in an accessible price range for both quick brand launches and speculative holds. Because .ink carries no single dominant industry association, name clarity and renewal cost matter more than sector fit when comparing options within this set.

- 10,319 one-word .ink domains in this set
- Median asking price near $93
- Short, brandable names like getlucky.ink
- Updated daily to reflect current availability

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .INK One-Word Domains*. Version 2026-09-26. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .INK page](https://unique.domains/domains/tld/ink?utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
