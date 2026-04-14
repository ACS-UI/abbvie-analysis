# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **25** URLs; **6** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Informational Page**, **Resource Page**, **Functional Page**. **19** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:03:52.988Z
- **Website**: https://www.psoriaticarthritisinfo.com/
- **Total Pages Analyzed**: 25
- **Total Templates Identified**: 6
- **Total Components Identified**: 19
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.PSORIATICARTHRITISINFO.COM TEMPLATES                                     │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Informational Page                   │    │ Resource Page                        │    │ Functional Page                      │
│ (11 pages)                           │    │ (5 pages)                            │    │ (5 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • —                                  │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • —                                  │    │ • Primary Navigation {Unmapped}      │
│ • Footer Section                     │    │ • —                                  │    │ • Hero Section                       │
│ • —                                  │    │ • —                                  │    │ • Main Content {Unmapped}            │
│ • —                                  │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage                             │    │ Site Map                             │    │ Interactive Tool                     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section {Unmapped}            │
│ • Call-to-Action Section {Unmapped}  │    │ • Breadcrumb Navigation {Unmapped}   │    │ • Quiz Description {Unmapped}        │
│ • (+2 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Informational Page (`tpl_0`) — 11 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer Section

### Resource Page (`tpl_1`) — 5 pages

- —

### Functional Page (`tpl_2`) — 5 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}
- Important Safety Information {Unmapped}
- Footer Navigation

### Homepage (`tpl_3`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Section {Unmapped}
- Quick Poll {Unmapped}
- Footer

### Site Map (`tpl_4`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Breadcrumb Navigation {Unmapped}
- Sitemap Links {Unmapped}
- Footer Section

### Interactive Tool (`tpl_5`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Quiz Description {Unmapped}
- Quiz Disclaimer {Unmapped}
- Quiz Form {Unmapped}
- Fact Callout {Unmapped}
- Doctor Guide CTA {Unmapped}
- Find Doctor Callout {Unmapped}
- Footer


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Primary Navigation {Unmapped}        │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Hero Section                         │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Footer                               │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │
│ Footer Section                       │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Global Utility Navigation {Unmapped} │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Global Utility Strip {Unmapped}      │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Breadcrumb Navigation {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Call-to-Action Section {Unmapped}       │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Doctor Guide CTA {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Fact Callout {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Find Doctor Callout {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Footer Navigation                       │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Hero Section {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Important Safety Information {Unmapped} │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Main Content {Unmapped}                 │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Quick Poll {Unmapped}                   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Quiz Description {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Quiz Disclaimer {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Quiz Form {Unmapped}                    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Sitemap Links {Unmapped}                │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Informational Page (11 pgs)                                                                       │
│ • Resource Page (5 pgs)                                                                             │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Functional Page (5 pgs)                                                                           │
│ • Homepage (1 pgs)                                                                                  │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Site Map (1 pgs)                                                                                  │
│ • Interactive Tool (1 pgs)                                                                          │
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
| tpl_0 | Informational Page | Pages providing general or detailed information. | https://www.psoriaticarthritisinfo.com/what-is-psoriatic-arthritis, https://www.psoriaticarthritisinfo.com/what-is-psoriatic-arthritis/progression, https://www.psoriaticarthritisinfo.com/what-is-psoriatic-arthritis/symptoms | 11 |
| tpl_1 | Resource Page | Pages containing downloadable resources or reference materials. | https://www.psoriaticarthritisinfo.com/content/dam/psoriaticarthritisinfo/pdf/diagnosed-discussion-guide.pdf, https://www.psoriaticarthritisinfo.com/content/dam/psoriaticarthritisinfo/pdf/undiagnosed-discussion-guide.pdf, https://www.psoriaticarthritisinfo.com/content/dam/psoriaticarthritisinfo/pdf/Psoriatic-Arthritis-Living-Well-Kit.pdf | 5 |
| tpl_2 | Functional Page | Pages designed for specific functional purposes. | https://www.psoriaticarthritisinfo.com/emailsetup, https://www.psoriaticarthritisinfo.com/pdfsetup, https://www.psoriaticarthritisinfo.com/find-a-doctor | 5 |
| tpl_3 | Homepage | The main landing page of the website. | https://www.psoriaticarthritisinfo.com/ | 1 |
| tpl_4 | Site Map | A page listing the structure of the website. | https://www.psoriaticarthritisinfo.com/sitemap | 1 |
| tpl_5 | Interactive Tool | Pages featuring tools for user interaction. | https://www.psoriaticarthritisinfo.com/psoriatic-arthritis-symptoms-quiz | 1 |
