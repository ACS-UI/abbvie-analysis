# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **33** URLs; **16** layout templates were identified (signature (DOM fingerprint)). Highest-traffic templates by page count include **Page layout group 6**, **What Is Duopa — group 4**, **Patient Stories — group 9**. **13** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T12:32:50.692Z
- **Website**: https://www.duopa.com/
- **Total Pages Analyzed**: 33
- **Total Templates Identified**: 16
- **Total Components Identified**: 13
- **Grouping**: signature (DOM fingerprint)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.DUOPA.COM TEMPLATES                                                      │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 6                  │    │ What Is Duopa — group 4              │    │ Patient Stories — group 9            │
│ (6 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • Form / subscription {Unmapped}     │    │ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • (+5 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 1                  │    │ How Duopa Works — group 2            │    │ Mentor Program — group 3             │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │
│ • (+4 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Sitemap — group 5                    │    │ Duopa Share — group 7                │    │ Advanced Parkinsons — group 8        │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Form / subscription {Unmapped}     │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • —                                  │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • —                                  │    │ • main region 0 {Unmapped}           │
│ • Form / subscription {Unmapped}     │    │ • —                                  │    │ • main region 1 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • —                                  │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Carrying Case — group 10             │    │ My Duopa Materials — group 11        │    │ Resources — group 12                 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │
│ • (+6 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.DUOPA.COM — SUB-TEMPLATES TEMPLATES                                      │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Search Results — group 13            │    │ Duopa Your Day — group 14            │    │ As Parkinsons Advances — group 15    │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • search results coveo {Unmapped}    │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • Form / subscription {Unmapped}     │    │ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • (+6 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Education Program — group 16         │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │
│ • Form / subscription {Unmapped}     │
│ • Site footer {Unmapped}             │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Page layout group 6 (`tpl_5`) — 6 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Form / subscription {Unmapped}
- Site footer {Unmapped}

### What Is Duopa — group 4 (`tpl_3`) — 2 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- columns {Unmapped}
- Form / subscription {Unmapped}
- Site footer {Unmapped}

### Patient Stories — group 9 (`tpl_8`) — 2 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- Form / subscription {Unmapped}
- Site footer {Unmapped}

### Page layout group 1 (`tpl_0`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- Form / subscription {Unmapped}
- Site footer {Unmapped}

### How Duopa Works — group 2 (`tpl_1`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- Form / subscription {Unmapped}
- Site footer {Unmapped}

### Mentor Program — group 3 (`tpl_2`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Form / subscription {Unmapped}
- Site footer {Unmapped}

### Sitemap — group 5 (`tpl_4`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Form / subscription {Unmapped}
- Site footer {Unmapped}

### Duopa Share — group 7 (`tpl_6`) — 1 pages

- Form / subscription {Unmapped}

### Advanced Parkinsons — group 8 (`tpl_7`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- Form / subscription {Unmapped}
- Site footer {Unmapped}

### Carrying Case — group 10 (`tpl_9`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- Carousel / spotlight {Unmapped}
- Form / subscription {Unmapped}
- Site footer {Unmapped}

### My Duopa Materials — group 11 (`tpl_10`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- Form / subscription {Unmapped}
- Site footer {Unmapped}

### Resources — group 12 (`tpl_11`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- Form / subscription {Unmapped}
- Form / subscription {Unmapped}
- Site footer {Unmapped}

### Search Results — group 13 (`tpl_12`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- search results coveo {Unmapped}
- Form / subscription {Unmapped}
- Site footer {Unmapped}

### Duopa Your Day — group 14 (`tpl_13`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- Carousel / spotlight {Unmapped}
- Form / subscription {Unmapped}
- Site footer {Unmapped}

### As Parkinsons Advances — group 15 (`tpl_14`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- Form / subscription {Unmapped}
- Site footer {Unmapped}

### Education Program — group 16 (`tpl_15`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Form / subscription {Unmapped}
- Site footer {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌───────────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                     │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├───────────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Form / subscription {Unmapped}                │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Global utility bar {Unmapped}                 │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Primary site header and navigation {Unmapped} │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Site footer {Unmapped}                        │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ main region 0 {Unmapped}                      │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ main region 1 {Unmapped}                      │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │
│ main region 2 {Unmapped}                      │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │
│ main region 3 {Unmapped}                      │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │
│ main region 4 {Unmapped}                      │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Carousel / spotlight {Unmapped}               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└───────────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T16 omitted from matrix width; see appendix.*


### Template-specific components

```
┌─────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                       │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ columns {Unmapped}              │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ search results coveo {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T16 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Page layout group 6 (6 pgs)                                                                       │
│ • What Is Duopa — group 4 (2 pgs)                                                                   │
│ • Patient Stories — group 9 (2 pgs)                                                                 │
│ • Page layout group 1 (1 pgs)                                                                       │
│ • How Duopa Works — group 2 (1 pgs)                                                                 │
│ • Mentor Program — group 3 (1 pgs)                                                                  │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Sitemap — group 5 (1 pgs)                                                                         │
│ • Duopa Share — group 7 (1 pgs)                                                                     │
│ • Advanced Parkinsons — group 8 (1 pgs)                                                             │
│ • Carrying Case — group 10 (1 pgs)                                                                  │
│ • My Duopa Materials — group 11 (1 pgs)                                                             │
│ • Resources — group 12 (1 pgs)                                                                      │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Search Results — group 13 (1 pgs)                                                                 │
│ • Duopa Your Day — group 14 (1 pgs)                                                                 │
│ • As Parkinsons Advances — group 15 (1 pgs)                                                         │
│ • Education Program — group 16 (1 pgs)                                                              │
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
| tpl_0 | Page layout group 1 | Same structural layout across 1 page(s) in the crawl. | https://www.duopa.com/ | 1 |
| tpl_1 | How Duopa Works — group 2 | Same structural layout across 1 page(s) in the crawl. | https://www.duopa.com/how-duopa-works | 1 |
| tpl_2 | Mentor Program — group 3 | Same structural layout across 1 page(s) in the crawl. | https://www.duopa.com/mentor-program | 1 |
| tpl_3 | What Is Duopa — group 4 | Same structural layout across 2 page(s) in the crawl. | https://www.duopa.com/what-is-duopa, https://www.duopa.com/how-duopa-may-help | 2 |
| tpl_4 | Sitemap — group 5 | Same structural layout across 1 page(s) in the crawl. | https://www.duopa.com/sitemap | 1 |
| tpl_5 | Page layout group 6 | Same structural layout across 6 page(s) in the crawl. | https://www.duopa.com/my-duopa-materials-evening-routine-transcript, https://www.duopa.com/my-duopa-materials-pump-cassette-care-transcript, https://www.duopa.com/resources-david-video-transcript | 6 |
| tpl_6 | Duopa Share — group 7 | Same structural layout across 1 page(s) in the crawl. | https://www.duopa.com/duopa-share | 1 |
| tpl_7 | Advanced Parkinsons — group 8 | Same structural layout across 1 page(s) in the crawl. | https://www.duopa.com/advanced-parkinsons | 1 |
| tpl_8 | Patient Stories — group 9 | Same structural layout across 2 page(s) in the crawl. | https://www.duopa.com/patient-stories, https://www.duopa.com/resources-paul-video-transcript | 2 |
| tpl_9 | Carrying Case — group 10 | Same structural layout across 1 page(s) in the crawl. | https://www.duopa.com/carrying-case | 1 |
| tpl_10 | My Duopa Materials — group 11 | Same structural layout across 1 page(s) in the crawl. | https://www.duopa.com/my-duopa-materials | 1 |
| tpl_11 | Resources — group 12 | Same structural layout across 1 page(s) in the crawl. | https://www.duopa.com/resources | 1 |
| tpl_12 | Search Results — group 13 | Same structural layout across 1 page(s) in the crawl. | https://www.duopa.com/search-results | 1 |
| tpl_13 | Duopa Your Day — group 14 | Same structural layout across 1 page(s) in the crawl. | https://www.duopa.com/duopa-your-day | 1 |
| tpl_14 | As Parkinsons Advances — group 15 | Same structural layout across 1 page(s) in the crawl. | https://www.duopa.com/as-parkinsons-advances | 1 |
| tpl_15 | Education Program — group 16 | Same structural layout across 1 page(s) in the crawl. | https://www.duopa.com/education-program | 1 |
