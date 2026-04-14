# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **10** URLs; **3** layout templates were identified (signature (DOM fingerprint)). Highest-traffic templates by page count include **Page layout group 1**, **Sitemap — group 2**, **Telemedicine Resources — group 3**. **11** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T12:38:19.551Z
- **Website**: https://www.duopahcp.com/
- **Total Pages Analyzed**: 10
- **Total Templates Identified**: 3
- **Total Components Identified**: 11
- **Grouping**: signature (DOM fingerprint)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.DUOPAHCP.COM TEMPLATES                                                   │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 1                  │    │ Sitemap — group 2                    │    │ Telemedicine Resources — group 3     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │
│ • carousel {Unmapped}                │    │ • Site footer {Unmapped}             │    │ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │    │ • —                                  │    │ • main region 1 {Unmapped}           │
│ • main region 2 {Unmapped}           │    │ • —                                  │    │ • main region 2 {Unmapped}           │
│ • (+5 more — see Blocks mapped per … │    │ • —                                  │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Page layout group 1 (`tpl_0`) — 1 pages

- Site header {Unmapped}
- carousel {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- main region 5 {Unmapped}
- main region 6 {Unmapped}
- Site footer {Unmapped}

### Sitemap — group 2 (`tpl_1`) — 1 pages

- Site header {Unmapped}
- Site footer {Unmapped}

### Telemedicine Resources — group 3 (`tpl_2`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- main region 5 {Unmapped}
- columns {Unmapped}
- Site footer {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────┬─────┬─────┬─────┐
│ Component                    │ T1  │ T2  │ T3  │
├──────────────────────────────┼─────┼─────┼─────┤
│ Site footer {Unmapped}       │ ✅   │ ✅   │ ✅   │
│ Site header {Unmapped}       │ ✅   │ ✅   │ ✅   │
│ main region 1 {Unmapped}     │ ✅   │ ❌   │ ✅   │
│ main region 2 {Unmapped}     │ ✅   │ ❌   │ ✅   │
│ main region 3 {Unmapped}     │ ✅   │ ❌   │ ✅   │
│ main region 4 {Unmapped}     │ ✅   │ ❌   │ ✅   │
│ main region 5 {Unmapped}     │ ✅   │ ❌   │ ✅   │
└──────────────────────────────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌──────────────────────────────┬─────┬─────┬─────┐
│ Component                    │ T1  │ T2  │ T3  │
├──────────────────────────────┼─────┼─────┼─────┤
│ carousel {Unmapped}          │ ✅   │ ❌   │ ❌   │
│ columns {Unmapped}           │ ❌   │ ❌   │ ✅   │
│ main region 0 {Unmapped}     │ ❌   │ ❌   │ ✅   │
│ main region 6 {Unmapped}     │ ✅   │ ❌   │ ❌   │
└──────────────────────────────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Page layout group 1 (1 pgs)                                                                       │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Sitemap — group 2 (1 pgs)                                                                         │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Telemedicine Resources — group 3 (1 pgs)                                                          │
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
| tpl_0 | Page layout group 1 | Same structural layout across 1 page(s) in the crawl. | https://www.duopahcp.com/ | 1 |
| tpl_1 | Sitemap — group 2 | Same structural layout across 1 page(s) in the crawl. | https://www.duopahcp.com/sitemap | 1 |
| tpl_2 | Telemedicine Resources — group 3 | Same structural layout across 1 page(s) in the crawl. | https://www.duopahcp.com/telemedicine-resources | 1 |
