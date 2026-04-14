# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **5** URLs; **2** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Durysta Home**, **Site Map**. **13** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:19:50.841Z
- **Website**: https://www.durystasavingsprogram.com/
- **Total Pages Analyzed**: 5
- **Total Templates Identified**: 2
- **Total Components Identified**: 13
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.DURYSTASAVINGSPROGRAM.COM TEMPLATES                                      │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Durysta Home                         │    │ Site Map                             │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Navigation          │
│ • Primary Header                     │    │ • Primary Navigation                 │
│ • Hero Section                       │    │ • Hero Section                       │
│ • Eligibility Section {Unmapped}     │    │ • Site Map Section                   │
│ • (+5 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Durysta Home (`tpl_0`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header
- Hero Section
- Eligibility Section {Unmapped}
- Terms and Conditions {Unmapped}
- Quick Links {Unmapped}
- Important Safety Information {Unmapped}
- Footer
- Modals

### Site Map (`tpl_1`) — 1 pages

- Global Utility Navigation
- Primary Navigation
- Hero Section
- Site Map Section
- FAQ Call-to-Action
- Important Safety Information
- Footer


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────┬─────┬─────┐
│ Component                    │ T1  │ T2  │
├──────────────────────────────┼─────┼─────┤
│ Footer                       │ ✅   │ ✅   │
│ Hero Section                 │ ✅   │ ✅   │
└──────────────────────────────┴─────┴─────┘
```


### Template-specific components

```
┌─────────────────────────────────────────┬─────┬─────┐
│ Component                               │ T1  │ T2  │
├─────────────────────────────────────────┼─────┼─────┤
│ Eligibility Section {Unmapped}          │ ✅   │ ❌   │
│ FAQ Call-to-Action                      │ ❌   │ ✅   │
│ Global Utility Navigation               │ ❌   │ ✅   │
│ Global Utility Strip {Unmapped}         │ ✅   │ ❌   │
│ Important Safety Information            │ ❌   │ ✅   │
│ Important Safety Information {Unmapped} │ ✅   │ ❌   │
│ Modals                                  │ ✅   │ ❌   │
│ Primary Header                          │ ✅   │ ❌   │
│ Primary Navigation                      │ ❌   │ ✅   │
│ Quick Links {Unmapped}                  │ ✅   │ ❌   │
│ Site Map Section                        │ ❌   │ ✅   │
│ Terms and Conditions {Unmapped}         │ ✅   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Durysta Home (1 pgs)                                                                              │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Site Map (1 pgs)                                                                                  │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

*None in this tier.*


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
| tpl_0 | Durysta Home | The homepage for the Durysta product. | https://www.durystasavingsprogram.com/ | 1 |
| tpl_1 | Site Map | A page providing a map of the website's structure. | https://www.durystasavingsprogram.com/sitemap | 1 |
