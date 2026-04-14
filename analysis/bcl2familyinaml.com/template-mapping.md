# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **2** URLs; **2** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Informational Homepage**, **Sitemap Page**. **12** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:22:04.419Z
- **Website**: https://www.bcl2familyinaml.com/
- **Total Pages Analyzed**: 2
- **Total Templates Identified**: 2
- **Total Components Identified**: 12
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.BCL2FAMILYINAML.COM TEMPLATES                                            │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Informational Homepage               │    │ Sitemap Page                         │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Section Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Main Content {Unmapped}            │
│ • Hero Section                       │    │ • Footer                             │
│ • Multi-Column CTAs {Unmapped}       │    │ • Back to Top Button {Unmapped}      │
│ • (+4 more — see Blocks mapped per … │    │ • Modal Component                    │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Informational Homepage (`tpl_0`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Multi-Column CTAs {Unmapped}
- AML Overview Section {Unmapped}
- Video Section {Unmapped}
- Accordion Section
- Footer

### Sitemap Page (`tpl_1`) — 1 pages

- Section Navigation {Unmapped}
- Main Content {Unmapped}
- Footer
- Back to Top Button {Unmapped}
- Modal Component


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────┬─────┬─────┐
│ Component                    │ T1  │ T2  │
├──────────────────────────────┼─────┼─────┤
│ Footer                       │ ✅   │ ✅   │
└──────────────────────────────┴─────┴─────┘
```


### Template-specific components

```
┌─────────────────────────────────┬─────┬─────┐
│ Component                       │ T1  │ T2  │
├─────────────────────────────────┼─────┼─────┤
│ Accordion Section               │ ✅   │ ❌   │
│ AML Overview Section {Unmapped} │ ✅   │ ❌   │
│ Back to Top Button {Unmapped}   │ ❌   │ ✅   │
│ Global Utility Strip {Unmapped} │ ✅   │ ❌   │
│ Hero Section                    │ ✅   │ ❌   │
│ Main Content {Unmapped}         │ ❌   │ ✅   │
│ Modal Component                 │ ❌   │ ✅   │
│ Multi-Column CTAs {Unmapped}    │ ✅   │ ❌   │
│ Primary Navigation {Unmapped}   │ ✅   │ ❌   │
│ Section Navigation {Unmapped}   │ ❌   │ ✅   │
│ Video Section {Unmapped}        │ ✅   │ ❌   │
└─────────────────────────────────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Informational Homepage (1 pgs)                                                                    │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Sitemap Page (1 pgs)                                                                              │
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
| tpl_0 | Informational Homepage | A template for the main informational landing page. | https://www.bcl2familyinaml.com/ | 1 |
| tpl_1 | Sitemap Page | A template for a page listing the site's structure. | https://www.bcl2familyinaml.com/sitemap | 1 |
