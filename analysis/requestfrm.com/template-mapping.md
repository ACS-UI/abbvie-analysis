# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **2** URLs; **2** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Reimbursement Support Page**, **Generic Sitemap**. **15** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:29:10.258Z
- **Website**: https://www.requestfrm.com/
- **Total Pages Analyzed**: 2
- **Total Templates Identified**: 2
- **Total Components Identified**: 15
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.REQUESTFRM.COM TEMPLATES                                                 │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Reimbursement Support Page           │    │ Generic Sitemap                      │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Header Branding                    │
│ • Primary Branding Header            │    │ • Important Safety Links {Unmapped}  │
│ • Hero Section                       │    │ • Product Logos {Unmapped}           │
│ • Product Logos {Unmapped}           │    │ • Main Content {Unmapped}            │
│ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Reimbursement Support Page (`tpl_0`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Branding Header
- Hero Section
- Product Logos {Unmapped}
- Content Introduction {Unmapped}
- Access Information {Unmapped}
- Interactive Form Section
- Footer Safety Links

### Generic Sitemap (`tpl_1`) — 1 pages

- Header Branding
- Important Safety Links {Unmapped}
- Product Logos {Unmapped}
- Main Content {Unmapped}
- Footer
- Back to Top Button {Unmapped}
- Contact Medical Affairs Modal
- Leaving Site Modal


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────┬─────┬─────┐
│ Component                    │ T1  │ T2  │
├──────────────────────────────┼─────┼─────┤
│ Product Logos {Unmapped}     │ ✅   │ ✅   │
└──────────────────────────────┴─────┴─────┘
```


### Template-specific components

```
┌───────────────────────────────────┬─────┬─────┐
│ Component                         │ T1  │ T2  │
├───────────────────────────────────┼─────┼─────┤
│ Access Information {Unmapped}     │ ✅   │ ❌   │
│ Back to Top Button {Unmapped}     │ ❌   │ ✅   │
│ Contact Medical Affairs Modal     │ ❌   │ ✅   │
│ Content Introduction {Unmapped}   │ ✅   │ ❌   │
│ Footer                            │ ❌   │ ✅   │
│ Footer Safety Links               │ ✅   │ ❌   │
│ Global Utility Strip {Unmapped}   │ ✅   │ ❌   │
│ Header Branding                   │ ❌   │ ✅   │
│ Hero Section                      │ ✅   │ ❌   │
│ Important Safety Links {Unmapped} │ ❌   │ ✅   │
│ Interactive Form Section          │ ✅   │ ❌   │
│ Leaving Site Modal                │ ❌   │ ✅   │
│ Main Content {Unmapped}           │ ❌   │ ✅   │
│ Primary Branding Header           │ ✅   │ ❌   │
└───────────────────────────────────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Reimbursement Support Page (1 pgs)                                                                │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Generic Sitemap (1 pgs)                                                                           │
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
| tpl_0 | Reimbursement Support Page | A template for pages providing reimbursement support. | https://www.requestfrm.com/ | 1 |
| tpl_1 | Generic Sitemap | A template for generic sitemap pages. | https://www.requestfrm.com/sitemap | 1 |
