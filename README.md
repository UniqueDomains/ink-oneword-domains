# Available .INK One-Word Domains (10,315)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C315%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .ink one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,315 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,315 domains · **Median ask:** $19.87 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-13  
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

- `ink.csv` — public CSV extract (1,000 rows)
- `ink.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/ink-oneword-domains/main/ink.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| finals.ink     | available | $2.99     | —             | 80             | 7      | 6      | name.com         |
| forces.ink     | available | $2.99     | —             | 82             | 12     | 6      | name.com         |
| edamame.ink    | available | $2.99     | —             | 80             | 9      | 7      | name.com         |
| hangon.ink     | available | $2.99     | —             | 82             | 6      | 7      | name.com         |
| pierogi.ink    | available | $2.99     | —             | 82             | 7      | 7      | name.com         |
| stirup.ink     | available | $2.99     | —             | 82             | 3      | 7      | name.com         |
| getlife.ink    | available | $2.99     | —             | 80             | 5      | 8      | name.com         |
| Snickers.ink   | available | $43.98    | —             | 80             | 10     | 8      | namecheap        |
| rumcake.ink    | available | $2.99     | —             | 81             | 3      | 8      | name.com         |
| regions.ink    | available | $2.99     | —             | 64             | 59     | 7      | name.com         |
| makers.ink     | resell    | —         | —             | 62             | 67     | 6      | GoDaddy.com, LLC |
| insight.ink    | premium   | $125      | —             | 76             | 69     | 8      | name.com         |
| motorsport.ink | available | $2.99     | —             | 74             | 23     | 10     | name.com         |
| skills.ink     | resell    | —         | —             | 58             | 47     | 6      | Spaceship, Inc.  |
| cars.ink       | premium   | $125      | —             | 66             | 47     | 4      | name.com         |
| veterans.ink   | available | $2.99     | —             | 56             | 23     | 8      | name.com         |
| videos.ink     | resell    | —         | —             | 52             | 30     | 6      | NameCheap, Inc.  |
| Keith.ink      | premium   | $245      | $245          | 66             | 25     | 5      | namecheap        |
| oceans.ink     | available | $2.99     | —             | 64             | 22     | 6      | name.com         |
| systems.ink    | resell    | —         | —             | 46             | 27     | 7      | GoDaddy.com, LLC |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,315 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/ink?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/ink?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .ink domains. The extension naturally suits names connected to writing, design, publishing, tattoos, creative work, and expressive brands, but some words also read broadly enough for software, media, or consumer projects. Examples such as finals.ink, jewels.ink, forces.ink, and useit.ink show the mix of dictionary words, action-oriented terms, and brandable constructions in this set. When comparing these domains, start with whether the word still feels strong with .ink, then check ask price, likely renewal burden, spelling ease, and any trademark exposure. Names like Chanel.ink and Apples.ink deserve extra caution because the term itself may create obvious rights risk.

- All domains in this set use the .ink extension
- Selection size: 10,304; median ask: 18.73
- Best fits favor clear words that pair naturally with .ink
- Screen carefully for trademark-heavy terms and weak word-fit

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .INK One-Word Domains*. Version 2026-05-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .INK page](https://unique.domains/domains/tld/ink?utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ink_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
