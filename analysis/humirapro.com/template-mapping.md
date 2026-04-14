# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **119** URLs; **7** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Dosing Information**, **Document PDF Viewer**, **Condition Information Overview**. **20** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:16:53.194Z
- **Website**: https://www.humirapro.com/
- **Total Pages Analyzed**: 119
- **Total Templates Identified**: 7
- **Total Components Identified**: 20
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.HUMIRAPRO.COM TEMPLATES                                                  │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Dosing Information                   │    │ Document PDF Viewer                  │    │ Condition Information Overview       │
│ (12 pages)                           │    │ (11 pages)                           │    │ (9 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Tabs Section {Unmapped}            │    │ • —                                  │    │ • Global Utility Strip {Unmapped}    │
│ • Tab Controls {Unmapped}            │    │ • —                                  │    │ • Primary Header                     │
│ • Induction Dose Tab {Unmapped}      │    │ • —                                  │    │ • Hero Section                       │
│ • Maintenance Dose Tab {Unmapped}    │    │ • —                                  │    │ • Accordion Section                  │
│ • Dosing Images {Unmapped}           │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Uncategorized Content                │    │ Website Sitemap                      │
│ (7 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │
│ • Hero Section {Unmapped}            │    │ • Sitemap Hero                       │
│ • Call to Action Section {Unmapped}  │    │ • Sitemap Links {Unmapped}           │
│ • (+3 more — see Blocks mapped per … │    │ • Footer                             │
└──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.HUMIRAPRO.COM — SUB-TEMPLATES TEMPLATES                                  │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Website Home Page                    │    │ Global Safety Information            │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │
│ • Accordion Section                  │    │ • Accordion Section                  │
│ • (+2 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Dosing Information (`tpl_0`) — 12 pages

- Tabs Section {Unmapped}
- Tab Controls {Unmapped}
- Induction Dose Tab {Unmapped}
- Maintenance Dose Tab {Unmapped}
- Dosing Images {Unmapped}

### Document PDF Viewer (`tpl_1`) — 11 pages

- —

### Condition Information Overview (`tpl_2`) — 9 pages

- Global Utility Strip {Unmapped}
- Primary Header
- Hero Section
- Accordion Section
- CTA Links {Unmapped}
- Footer Section

### Uncategorized Content (`tpl_3`) — 7 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Call to Action Section {Unmapped}
- Accordion Section {Unmapped}
- Image and Text Section {Unmapped}
- Rich Text Section {Unmapped}

### Website Sitemap (`tpl_4`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Sitemap Hero
- Sitemap Links {Unmapped}
- Footer

### Website Home Page (`tpl_5`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Accordion Section
- CTA Links {Unmapped}
- Footer

### Global Safety Information (`tpl_6`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Accordion Section
- CTA Links {Unmapped}
- Footer Navigation {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Accordion Section                    │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │
│ CTA Links {Unmapped}                 │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Hero Section                         │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Footer                               │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Global Utility Navigation {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Global Utility Strip {Unmapped}      │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Primary Header {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Primary Navigation {Unmapped}        │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌───────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                         │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├───────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Accordion Section {Unmapped}      │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Call to Action Section {Unmapped} │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Dosing Images {Unmapped}          │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Navigation {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Footer Section                    │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Hero Section {Unmapped}           │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Image and Text Section {Unmapped} │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Induction Dose Tab {Unmapped}     │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Maintenance Dose Tab {Unmapped}   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Primary Header                    │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Rich Text Section {Unmapped}      │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Sitemap Hero                      │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Sitemap Links {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Tab Controls {Unmapped}           │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└───────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Dosing Information (12 pgs)                                                                       │
│ • Document PDF Viewer (11 pgs)                                                                      │
│ • Condition Information Overview (9 pgs)                                                            │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Uncategorized Content (7 pgs)                                                                     │
│ • Website Sitemap (2 pgs)                                                                           │
│ • Website Home Page (1 pgs)                                                                         │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Global Safety Information (1 pgs)                                                                 │
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
| tpl_0 | Dosing Information | Template for presenting dosing guidelines and details. | https://www.humirapro.com/dosing/uveitis-adult, https://www.humirapro.com/dosing, https://www.humirapro.com/dosing/juvenile-idiopathic-arthritis | 12 |
| tpl_1 | Document PDF Viewer | Template for displaying and interacting with PDF documents. | https://www.humirapro.com/content/dam/humirapro/documents/humira-ambassador-program-ped-derm.pdf, https://www.humirapro.com/content/dam/humirapro/documents/humira-ambassador-program-ped-gastro.pdf, https://www.humirapro.com/content/dam/humirapro/documents/humira-ambassador-program-ped-rheum.pdf | 11 |
| tpl_2 | Condition Information Overview | Template for providing detailed information about conditions. | https://www.humirapro.com/uveitis, https://www.humirapro.com/pediatric-ulcerative-colitis, https://www.humirapro.com/plaque-psoriasis | 9 |
| tpl_3 | Uncategorized Content | Template for content that does not fit into other categories. | https://www.humirapro.com/uveitis-pediatric, https://www.humirapro.com/crohns-disease, https://www.humirapro.com/patient-support | 7 |
| tpl_4 | Website Sitemap | Template for providing a navigational overview of the website. | https://www.humirapro.com/site-map, https://www.humirapro.com/sitemap | 2 |
| tpl_5 | Website Home Page | Template for the main landing page of the website. | https://www.humirapro.com/ | 1 |
| tpl_6 | Global Safety Information | Template for showcasing global safety standards and practices. | https://www.humirapro.com/global-safety | 1 |
