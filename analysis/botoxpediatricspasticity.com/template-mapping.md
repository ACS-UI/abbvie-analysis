# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **6** URLs; **1** layout template were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Access Denied Page**. **13** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:37:45.303Z
- **Website**: https://www.botoxpediatricspasticity.com/
- **Total Pages Analyzed**: 6
- **Total Templates Identified**: 1
- **Total Components Identified**: 13
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.BOTOXPEDIATRICSPASTICITY.COM TEMPLATES                                   │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Access Denied Page                   │
│ (6 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Global Utility Links {Unmapped}    │
│ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │
│ • Desktop Hero Text {Unmapped}       │
│ • (+9 more — see Blocks mapped per … │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Access Denied Page (`tpl_0`) — 6 pages

- Global Utility Links {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Desktop Hero Text {Unmapped}
- Mobile Hero Text {Unmapped}
- Call-to-Action Block 1 {Unmapped}
- Thumbnail Box 1 {Unmapped}
- Thumbnail Box 2 {Unmapped}
- Thumbnail Box 3 {Unmapped}
- Call-to-Action Block 2 {Unmapped}
- Exit Interstitial Modal
- Important Safety Information Bar {Unmapped}
- Footer


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────┬─────┐
│ Component                    │ T1  │
├──────────────────────────────┼─────┤
│ (after blocks step)          │ —   │
└──────────────────────────────┴─────┘
```


### Template-specific components

```
┌─────────────────────────────────────────────┬─────┐
│ Component                                   │ T1  │
├─────────────────────────────────────────────┼─────┤
│ Call-to-Action Block 1 {Unmapped}           │ ✅   │
│ Call-to-Action Block 2 {Unmapped}           │ ✅   │
│ Desktop Hero Text {Unmapped}                │ ✅   │
│ Exit Interstitial Modal                     │ ✅   │
│ Footer                                      │ ✅   │
│ Global Utility Links {Unmapped}             │ ✅   │
│ Hero Section                                │ ✅   │
│ Important Safety Information Bar {Unmapped} │ ✅   │
│ Mobile Hero Text {Unmapped}                 │ ✅   │
│ Primary Navigation {Unmapped}               │ ✅   │
│ Thumbnail Box 1 {Unmapped}                  │ ✅   │
│ Thumbnail Box 2 {Unmapped}                  │ ✅   │
│ Thumbnail Box 3 {Unmapped}                  │ ✅   │
└─────────────────────────────────────────────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Access Denied Page (6 pgs)                                                                        │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

*None in this tier.*


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
| tpl_0 | Access Denied Page | This template represents pages indicating restricted access. | https://www.botoxpediatricspasticity.com/, https://www.botoxpediatricspasticity.com/about-spasticity, https://www.botoxpediatricspasticity.com/sitemap | 6 |
