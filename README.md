# Available .NL One-Word Domains (7,859)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-7%2C859%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .nl one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **7,859 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 7,859 domains · **Median ask:** $14.09 · **High-demand under $2,500:** 0

**Last updated:** 2026-08-20
**Canonical page:** `https://unique.domains/domains/tld/nl`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/nl?utm_source=github&utm_medium=referral&utm_campaign=repo_nl_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./nl.csv">CSV</a> / <a href="./nl.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_nl_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_nl_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .NL search](https://unique.domains/domains/tld/nl?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_nl_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .NL search](https://unique.domains/domains/tld/nl?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_nl_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_nl_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .NL one-word domain catalog.

### Files

- `nl.csv`, public CSV extract (1,000 rows)
- `nl.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/nl-oneword-domains/main/nl.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain      | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                        |
| ----------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------------- |
| abiding.nl  | available | $11.99    | $11.99        | high           | low    | 7      | name.com                         |
| unhappy.nl  | available | $11.99    | $11.99        | high           | low    | 7      | name.com                         |
| annoy.nl    | available | $6.98     | $7.99         | medium         | low    | 5      | namesilo                         |
| bad.nl      | resell    | —         | —             | high           | medium | 3      | team.blue nl B.V.                |
| ill.nl      | premium   | $3,131.82 | —             | medium         | low    | 3      | Internet Domain Service BS Corp. |
| apian.nl    | available | $6.98     | $7.99         | low            | low    | 5      | namesilo                         |
| bed.nl      | resell    | —         | —             | high           | low    | 3      | Hostnet B.V.                     |
| liked.nl    | premium   | $1,635.79 | —             | high           | low    | 5      | Metaregistrar B.V.               |
| balmy.nl    | available | $11.99    | —             | high           | low    | 5      | name.com                         |
| fat.nl      | resell    | —         | —             | medium         | low    | 3      | The Registrar Company B.V.       |
| older.nl    | premium   | $1,098.25 | $11.99        | medium         | low    | 5      | Metaregistrar B.V.               |
| bared.nl    | available | $6.98     | $7.99         | medium         | low    | 5      | namesilo                         |
| flu.nl      | resell    | —         | —             | medium         | low    | 3      | Realtime Register                |
| shrub.nl    | premium   | $2,566.81 | —             | medium         | low    | 5      | Metaregistrar B.V.               |
| clxxx.nl    | available | $6.98     | $7.99         | low            | low    | 5      | namesilo                         |
| gal.nl      | resell    | —         | —             | medium         | low    | 3      | Realtime Register                |
| marble.nl   | premium   | $4,180.10 | —             | medium         | low    | 6      | Realtime Register                |
| dying.nl    | available | $11.99    | $11.99        | high           | low    | 5      | name.com                         |
| hot.nl      | resell    | —         | —             | high           | low    | 3      | Funbit B.V.                      |
| complain.nl | premium   | $1,019.85 | —             | medium         | low    | 8      | Metaregistrar B.V.               |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 7,859 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/nl?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_nl_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/nl?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_nl_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_nl_oneword_domains&utm_content=related_pricing)

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

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set covers 3,432 available one-word .NL domain names built from short, everyday word combinations such as carcoat.nl, coffeecupful.nl, and goodasgold.nl. Each domain sits under the .NL country-code TLD, commonly used for Dutch and Netherlands-focused projects. The median asking price across this list is about $21, making it accessible for early-stage founders and domain investors alike. When comparing these domains, weigh word clarity, renewal cost, and relevance to a Dutch or European audience before committing to a purchase.

- 3,432 available one-word .NL domain names
- Median asking price near $21
- Compound-word style: carcoat.nl, makefriends.nl
- Ideal for brandable, ownable-now .NL names

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .NL One-Word Domains*. Version 2026-08-20. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .NL page](https://unique.domains/domains/tld/nl?utm_source=github&utm_medium=referral&utm_campaign=repo_nl_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_nl_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_nl_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_nl_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
