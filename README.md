# Available .EMAIL One-Word Domains (6,758)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-6%2C758%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-6%2C758%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .email one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 6,758 rows · **Live catalog:** 6,758 domains

**Last updated:** 2026-04-12  
**Canonical page:** `https://unique.domains/domains/tld/email`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/email?utm_source=github&utm_medium=referral&utm_campaign=repo_email_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./email.csv">CSV</a> / <a href="./email.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_email_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_email_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .EMAIL search](https://unique.domains/domains/tld/email?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_email_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .EMAIL search](https://unique.domains/domains/tld/email?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_email_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_email_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .EMAIL one-word domain catalog.

### Files

- `email.csv` — public CSV extract (6,758 rows)
- `email.json` — public JSON extract (6,758 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/email-oneword-domains/main/email.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| stock.email     | available | $9.99     | —             | 68             | 40     | 5      | name.com                                                  |
| crazy.email     | resell    | —         | —             | 86             | 98     | 5      | NameCheap, Inc.                                           |
| athletics.email | premium   | $260      | $260          | 69             | 52     | 9      | namecheap                                                 |
| advance.email   | available | $9.99     | $39.99        | 110            | 33     | 7      | name.com                                                  |
| austrian.email  | resell    | —         | —             | 82             | 97     | 8      | Spaceship, Inc.                                           |
| mark.email      | premium   | $1,000    | $1,000        | 66             | 42     | 4      | name.com                                                  |
| eleven.email    | available | $9.99     | $39.99        | 88             | 33     | 6      | name.com                                                  |
| box.email       | resell    | —         | —             | 68             | 78     | 3      | Spaceship, Inc.                                           |
| fitness.email   | premium   | $85.80    | $85.80        | 78             | 36     | 7      | namecheap                                                 |
| amber.email     | available | $9.99     | —             | 66             | 32     | 5      | name.com                                                  |
| matt.email      | resell    | —         | —             | 72             | 71     | 4      | Global Domains International, Inc. DBA DomainCostClub.com |
| menu.email      | premium   | $128.70   | $128.70       | 70             | 34     | 4      | namecheap                                                 |
| chip.email      | available | $9.99     | $39.99        | 76             | 29     | 4      | name.com                                                  |
| now.email       | resell    | —         | —             | 78             | 66     | 3      | Spaceship, Inc.                                           |
| mix.email       | premium   | $123.75   | $123.75       | 66             | 34     | 3      | name.com                                                  |
| device.email    | available | $9.99     | —             | 80             | 27     | 6      | name.com                                                  |
| news.email      | resell    | —         | —             | 100            | 64     | 4      | Chengdu West Dimension Digital Technology Co., Ltd.       |
| organic.email   | premium   | $123.75   | $123.75       | 93             | 33     | 7      | name.com                                                  |
| cow.email       | available | $9.99     | —             | 74             | 26     | 3      | name.com                                                  |
| free.email      | resell    | —         | —             | 88             | 59     | 4      | 1API GmbH                                                 |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 6,758-row public sample | 6,758 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/email?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_email_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/email?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_email_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_email_oneword_domains&utm_content=related_pricing)

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .EMAIL One-Word Domains*. Version 2026-04-12. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .EMAIL page](https://unique.domains/domains/tld/email?utm_source=github&utm_medium=referral&utm_campaign=repo_email_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_email_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_email_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_email_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
