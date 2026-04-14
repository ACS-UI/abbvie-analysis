# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **6** URLs; **6** layout templates were identified (signature (DOM fingerprint)). Highest-traffic templates by page count include **Page layout group 1**, **Tiposdeestrenimiento — group 2**, **Spanishgutcheck — group 3**. **9** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T14:43:59.441Z
- **Website**: https://es.linzess.com/
- **Total Pages Analyzed**: 6
- **Total Templates Identified**: 6
- **Total Components Identified**: 9
- **Grouping**: signature (DOM fingerprint)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│ES.LINZESS.COM TEMPLATES                                                     │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 1                  │    │ Tiposdeestrenimiento — group 2       │    │ Spanishgutcheck — group 3            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • columns {Unmapped}                 │    │ • Site footer {Unmapped}             │
│ • Back to top {Unmapped}             │    │ • (+4 more — see Blocks mapped per … │    │ • Back to top {Unmapped}             │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Porquelinzess — group 4              │    │ Savings Card — group 5               │    │ Consejosparamanejarelestrenimiento … │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • Site footer {Unmapped}             │    │ • main region 1 {Unmapped}           │
│ • Back to top {Unmapped}             │    │ • Back to top {Unmapped}             │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Page layout group 1 (`tpl_0`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}
- Back to top {Unmapped}

### Tiposdeestrenimiento — group 2 (`tpl_1`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- columns {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- Site footer {Unmapped}
- Back to top {Unmapped}

### Spanishgutcheck — group 3 (`tpl_2`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}
- Back to top {Unmapped}

### Porquelinzess — group 4 (`tpl_3`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}
- Back to top {Unmapped}

### Savings Card — group 5 (`tpl_4`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}
- Back to top {Unmapped}

### Consejosparamanejarelestrenimiento — group 6 (`tpl_5`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- Site footer {Unmapped}
- Back to top {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌───────────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                     │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │
├───────────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Back to top {Unmapped}                        │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Global utility bar {Unmapped}                 │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ main region 0 {Unmapped}                      │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Primary site header and navigation {Unmapped} │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Site footer {Unmapped}                        │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ main region 2 {Unmapped}                      │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
│ main region 3 {Unmapped}                      │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
└───────────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌──────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                    │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │
├──────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ columns {Unmapped}           │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ main region 1 {Unmapped}     │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
└──────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Page layout group 1 (1 pgs)                                                                       │
│ • Tiposdeestrenimiento — group 2 (1 pgs)                                                            │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Spanishgutcheck — group 3 (1 pgs)                                                                 │
│ • Porquelinzess — group 4 (1 pgs)                                                                   │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Savings Card — group 5 (1 pgs)                                                                    │
│ • Consejosparamanejarelestrenimiento — group 6 (1 pgs)                                              │
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
| tpl_0 | Page layout group 1 | Same structural layout across 1 page(s) in the crawl. | https://es.linzess.com/ | 1 |
| tpl_1 | Tiposdeestrenimiento — group 2 | Same structural layout across 1 page(s) in the crawl. | https://es.linzess.com/tiposdeestrenimiento | 1 |
| tpl_2 | Spanishgutcheck — group 3 | Same structural layout across 1 page(s) in the crawl. | https://es.linzess.com/spanishgutcheck | 1 |
| tpl_3 | Porquelinzess — group 4 | Same structural layout across 1 page(s) in the crawl. | https://es.linzess.com/porquelinzess | 1 |
| tpl_4 | Savings Card — group 5 | Same structural layout across 1 page(s) in the crawl. | https://es.linzess.com/savings-card | 1 |
| tpl_5 | Consejosparamanejarelestrenimiento — group 6 | Same structural layout across 1 page(s) in the crawl. | https://es.linzess.com/consejosparamanejarelestrenimiento | 1 |
