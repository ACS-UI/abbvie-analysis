# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **10** URLs; **7** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Homepage**, **Error Page**, **Why Product**. **48** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:33:57.313Z
- **Website**: https://hcp.loloestrin.com/
- **Total Pages Analyzed**: 10
- **Total Templates Identified**: 7
- **Total Components Identified**: 48
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│HCP.LOLOESTRIN.COM TEMPLATES                                                 │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage                             │    │ Error Page                           │    │ Why Product                          │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation                 │
│ • Primary site header and navigatio… │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │
│ • columns {Unmapped}                 │    │ • Error Hero Section                 │    │ • Hero Section                       │
│ • main region 1 {Unmapped}           │    │ • Error Message {Unmapped}           │    │ • Call-to-Action Section {Unmapped}  │
│ • (+7 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Formulary Coverage                   │    │ Product Consideration                │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Header Navigation {Unmapp… │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │
│ • CTA Buttons Row {Unmapped}         │    │ • Call-to-Actions Section {Unmapped} │
│ • (+4 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│HCP.LOLOESTRIN.COM — SUB-TEMPLATES TEMPLATES                                 │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Practice Support                     │    │ Sitemap Page                         │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • Call-to-Action Row {Unmapped}      │    │ • Sitemap List {Unmapped}            │
│ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Homepage (`tpl_0`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- columns {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- main region 5 {Unmapped}
- main region 6 {Unmapped}
- Carousel / spotlight {Unmapped}
- Site footer {Unmapped}

### Error Page (`tpl_1`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Error Hero Section
- Error Message {Unmapped}
- Important Safety Information {Unmapped}
- Back to Top Button {Unmapped}
- HCP Certification Modal
- Site Leaving Modal
- Safety Bar {Unmapped}

### Why Product (`tpl_2`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Call-to-Action Section {Unmapped}
- Information Columns
- Modal Call-to-Actions
- Amenorrhea Section {Unmapped}
- Breakthrough Bleeding Section {Unmapped}
- Clinical Study Highlights {Unmapped}

### Formulary Coverage (`tpl_3`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header Navigation {Unmapped}
- Hero Section
- CTA Buttons Row {Unmapped}
- Formulary Lookup
- Coverage Highlights {Unmapped}
- Important Safety Information {Unmapped}
- Footer Section

### Product Consideration (`tpl_4`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Actions Section {Unmapped}
- Patient Profiles Tabs
- Patient Profile: Grace {Unmapped}
- Patient Profile: Zara {Unmapped}
- Patient Profile: Maya {Unmapped}
- Accordion Section

### Practice Support (`tpl_5`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Call-to-Action Row {Unmapped}
- Resources Grid {Unmapped}
- Savings Program Section {Unmapped}
- Contact Section {Unmapped}
- Important Safety Information {Unmapped}

### Sitemap Page (`tpl_6`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Sitemap List {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links
- Footer Legal Text {Unmapped}
- Back to Top Button {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                            │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │ ✅   │
│ Important Safety Information {Unmapped} │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │
│ Primary Navigation {Unmapped}           │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │
│ Global Utility Navigation {Unmapped}    │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │
│ Back to Top Button {Unmapped}           │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Utility Navigation {Unmapped}           │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌──────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Accordion Section                        │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Amenorrhea Section {Unmapped}            │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Breakthrough Bleeding Section {Unmapped} │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Row {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Call-to-Action Section {Unmapped}        │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Actions Section {Unmapped}       │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Carousel / spotlight {Unmapped}          │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Clinical Study Highlights {Unmapped}     │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ columns {Unmapped}                       │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Contact Section {Unmapped}               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Coverage Highlights {Unmapped}           │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ CTA Buttons Row {Unmapped}               │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Error Hero Section                       │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Error Message {Unmapped}                 │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage (1 pgs)                                                                                  │
│ • Error Page (1 pgs)                                                                                │
│ • Why Product (1 pgs)                                                                               │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Formulary Coverage (1 pgs)                                                                        │
│ • Product Consideration (1 pgs)                                                                     │
│ • Practice Support (1 pgs)                                                                          │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Sitemap Page (1 pgs)                                                                              │
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
| tpl_0 | Homepage | The main landing page of the website. | https://hcp.loloestrin.com/ | 1 |
| tpl_1 | Error Page | A page displayed when an error occurs. | https://hcp.loloestrin.com/hcp-resources | 1 |
| tpl_2 | Why Product | A page explaining the reasons to choose a product. | https://hcp.loloestrin.com/why-loloestrinfe | 1 |
| tpl_3 | Formulary Coverage | A page detailing formulary coverage information. | https://hcp.loloestrin.com/hcp-resources/formulary-coverage | 1 |
| tpl_4 | Product Consideration | A page focused on product consideration details. | https://hcp.loloestrin.com/is-lo-loestrin-fe-right-for-her | 1 |
| tpl_5 | Practice Support | A page providing support resources for practices. | https://hcp.loloestrin.com/hcp-resources/support-for-your-practice | 1 |
| tpl_6 | Sitemap Page | A page displaying the website's sitemap. | https://hcp.loloestrin.com/sitemap | 1 |
