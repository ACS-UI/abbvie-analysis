# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **7** URLs; **6** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Homepage**, **Why Infed**, **About ID and IDA**. **36** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:16:04.714Z
- **Website**: https://www.infed.com/
- **Total Pages Analyzed**: 7
- **Total Templates Identified**: 6
- **Total Components Identified**: 36
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.INFED.COM TEMPLATES                                                      │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage                             │    │ Why Infed                            │    │ About ID and IDA                     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │    │ • Primary Header                     │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Iron Deficiency Card               │    │ • Call-to-Action Section {Unmapped}  │    │ • Call-to-Action Columns {Unmapped}  │
│ • (+5 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+7 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Dosing and Administration            │    │ References                           │    │ Sitemap                              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │
│ • Primary Header                     │    │ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Main Navigation {Unmapped}         │    │ • Hero Section                       │
│ • Call-to-Action Buttons             │    │ • Hero Section {Unmapped}            │    │ • Sitemap Links {Unmapped}           │
│ • (+7 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Homepage (`tpl_0`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Iron Deficiency Card
- Why INFeD Card
- Dosing & Administration Card
- Access & Coverage Card
- Important Safety Information {Unmapped}
- Footer

### Why Infed (`tpl_1`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Call-to-Action Section {Unmapped}
- Legacy of Balance Section {Unmapped}
- How INFeD Works Section {Unmapped}
- Coverage Section {Unmapped}
- Important Safety Information {Unmapped}

### About ID and IDA (`tpl_2`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header
- Hero Section
- Call-to-Action Columns {Unmapped}
- Prevalence Section {Unmapped}
- Identifying ID Section {Unmapped}
- Demographics Section {Unmapped}
- Symptoms Section {Unmapped}
- Diagnosis Section {Unmapped}
- Management and Treatment Section {Unmapped}
- Learn More Section {Unmapped}

### Dosing and Administration (`tpl_3`) — 1 pages

- Utility Navigation
- Primary Header
- Hero Section
- Call-to-Action Buttons
- Dosing and Duration
- Test Dose Section
- IDA Dosage
- Iron Replacement Dosage
- Prescription Details
- Total Dose Calculator
- Footer Section

### References (`tpl_4`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Main Navigation {Unmapped}
- Hero Section {Unmapped}
- References List {Unmapped}
- Important Safety Information {Unmapped}
- Footer
- Back to Top Button {Unmapped}
- Cookie Settings {Unmapped}

### Sitemap (`tpl_5`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Sitemap Links {Unmapped}
- Important Safety Information {Unmapped}
- Footer
- Back to Top Button {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                            │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │ ✅   │
│ Important Safety Information {Unmapped} │ ✅   │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Footer                                  │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Back to Top Button {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Global Utility Navigation {Unmapped}    │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global Utility Strip {Unmapped}         │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │
│ Primary Header                          │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Primary Header {Unmapped}               │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Primary Navigation {Unmapped}           │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌─────────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                   │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │
├─────────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Access & Coverage Card                      │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Buttons                      │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Call-to-Action Columns {Unmapped}           │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Section {Unmapped}           │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Cookie Settings {Unmapped}                  │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Coverage Section {Unmapped}                 │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Demographics Section {Unmapped}             │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Diagnosis Section {Unmapped}                │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Dosing & Administration Card                │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Dosing and Duration                         │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Footer Section                              │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Hero Section {Unmapped}                     │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ How INFeD Works Section {Unmapped}          │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ IDA Dosage                                  │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
└─────────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage (1 pgs)                                                                                  │
│ • Why Infed (1 pgs)                                                                                 │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • About ID and IDA (1 pgs)                                                                          │
│ • Dosing and Administration (1 pgs)                                                                 │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • References (1 pgs)                                                                                │
│ • Sitemap (1 pgs)                                                                                   │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


## Template Rationale Summary

### Why this template view helps

1. **Scalability**: New pages can be checked against existing template buckets.
2. **Consistency**: Grouping highlights shared layout patterns across sections.
3. **Maintainability**: Updates to a template concept apply to all URLs in that bucket.
4. **Performance**: Shared layouts suggest shared static assets and caching opportunities.
5. **Content operations**: Editors can map content types to template patterns.

### Next steps

- Tune AEM mappings in **block-mapping.csv** and re-run if the site uses custom blocks.
- Refine **human_name** / **description** via the template agent when using signature or agent grouping modes.

## Usage Instructions

1. **Diagram**: Template boxes reflect **page_count** from this run; names come from clustering + optional LLM labelling.
2. **Matrices**: Populated from extract-blocks + AEM catalog mapping.
3. **Phases**: Suggested prioritization by crawl traffic (page counts), not project schedule.
4. **Appendix**: Source-of-truth table for IDs, URLs, and counts.
5. **block-mapping.csv** (in the same output directory): stakeholder matrix aligned with `src/resources/block-mapping.csv` column headers.

## Appendix: Template index (table)

| template_id | human_name | description | example_urls | page_count |
| --- | --- | --- | --- | --- |
| tpl_0 | Homepage | The main landing page of the website. | https://www.infed.com/ | 1 |
| tpl_1 | Why Infed | Reasons and benefits of Infed. | https://www.infed.com/why-infed | 1 |
| tpl_2 | About ID and IDA | Information about ID and IDA. | https://www.infed.com/about-id-and-ida | 1 |
| tpl_3 | Dosing and Administration | Guidelines for dosing and administration. | https://www.infed.com/dosing-and-administration | 1 |
| tpl_4 | References | A list of references and citations. | https://www.infed.com/references | 1 |
| tpl_5 | Sitemap | Overview of the website structure. | https://www.infed.com/sitemap | 1 |
