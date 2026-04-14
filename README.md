# AbbVie Site Analysis Reports

AI-driven analysis of AbbVie's digital portfolio — crawling pages, detecting UI blocks, mapping them to the AEM component catalog, and grouping pages into layout templates.

**Live reports:** [https://acs-ui.github.io/abbvie-analysis/analysis-report.html](https://acs-ui.github.io/abbvie-analysis/analysis-report.html)

---

## Reports

### [`analysis-report-consolidated.html`](analysis-report-consolidated.html) — Consolidated Blocks View
Reads from each site's **`consolidated-blocks.csv`**, which aggregates duplicate block entries across pages into a single row with total occurrence counts and pre-computed screenshot paths.

- Deduplication handled by the analysis pipeline
- Occurrence count = aggregated total from the pipeline
- ~37 unique blocks per site (abbvieaccess.com baseline)

### [`analysis-report.html`](analysis-report.html) — Block Mapping View
Reads from each site's **`block-mapping.csv`**, the raw per-page block data. Deduplication is done at report-generation time; screenshots are derived from the `Source block name` field.

- More complete block coverage (captures blocks the consolidation step may have dropped)
- Occurrence count = row count across all pages per block
- ~42 unique blocks per site (abbvieaccess.com baseline)
- Each block card shows **Variation type** and **Source block name** for traceability

---

## What's in each report

| Section | Details |
|---|---|
| **Portfolio Overview** | KPIs: total sites, not-accessible count, analyzed count, total pages, block types |
| **All Sites / Not Accessible** | Collapsible URL lists from `urls.txt` and `url-delta.txt` |
| **Site Cards** | One per site — pages, blocks, templates, mapped/unmapped counts |
| **Blocks Grid** | Screenshot thumbnails (click to enlarge), sizing badge, AEM mapping status |
| **Template Mapping** | Table of templates with IDs, page counts, and example URLs |

---

## Scope

| | Count |
|---|---|
| Total sites in scope | 133 |
| Not accessible (crawl failed) | 15 |
| Sites with analysis reports | 97 |

Sites listed in `url-delta.txt` could not be crawled and have no analysis data.

---

## AI Disclaimer

These reports are produced by an AI-driven analysis pipeline. While the pipeline strives for accuracy, block detection, AEM catalog mapping, and template grouping may occasionally be incomplete or imperfect. Review findings before using them to drive implementation decisions.
