# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **37** URLs; **4** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Agent Unassigned Page**, **Content Page**, **Homepage**. **23** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:22:34.251Z
- **Website**: https://www.lupronprostatecancer.com/
- **Total Pages Analyzed**: 37
- **Total Templates Identified**: 4
- **Total Components Identified**: 23
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.LUPRONPROSTATECANCER.COM TEMPLATES                                       │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Agent Unassigned Page                │    │ Content Page                         │    │ Homepage                             │
│ (29 pages)                           │    │ (3 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Utility Navigation                 │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation                 │    │ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │
│ • Content Cards                      │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Content Cards                      │    │ • Page Title {Unmapped}              │    │ • CTA Columns {Unmapped}             │
│ • (+5 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ PDF Document Page                    │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • —                                  │
│ • —                                  │
│ • —                                  │
│ • —                                  │
│ • —                                  │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Agent Unassigned Page (`tpl_0`) — 29 pages

- Utility Navigation
- Primary Navigation
- Content Cards
- Content Cards
- Content Cards
- Content Cards
- Content Cards
- Content Cards
- Site Footer

### Content Page (`tpl_1`) — 3 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Page Title {Unmapped}
- Content Section 1 {Unmapped}
- Content Section 2 {Unmapped}
- Content Section 3
- Related Pages
- Important Safety Information

### Homepage (`tpl_2`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- CTA Columns {Unmapped}
- Prose Columns {Unmapped}
- Accordion Section
- Footer Section

### PDF Document Page (`tpl_3`) — 1 pages

- —


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────┬─────┬─────┬─────┬─────┐
│ Component                    │ T1  │ T2  │ T3  │ T4  │
├──────────────────────────────┼─────┼─────┼─────┼─────┤
│ Hero Section                 │ ❌   │ ✅   │ ✅   │ ❌   │
│ Primary Navigation           │ ✅   │ ✅   │ ❌   │ ❌   │
│ Utility Navigation           │ ✅   │ ✅   │ ❌   │ ❌   │
└──────────────────────────────┴─────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┤
│ Accordion Section                    │ ❌   │ ❌   │ ✅   │ ❌   │
│ Content Cards                        │ ✅   │ ❌   │ ❌   │ ❌   │
│ Content Section 1 {Unmapped}         │ ❌   │ ✅   │ ❌   │ ❌   │
│ Content Section 2 {Unmapped}         │ ❌   │ ✅   │ ❌   │ ❌   │
│ Content Section 3                    │ ❌   │ ✅   │ ❌   │ ❌   │
│ CTA Columns {Unmapped}               │ ❌   │ ❌   │ ✅   │ ❌   │
│ Footer Section                       │ ❌   │ ❌   │ ✅   │ ❌   │
│ Global Utility Navigation {Unmapped} │ ❌   │ ❌   │ ✅   │ ❌   │
│ Important Safety Information         │ ❌   │ ✅   │ ❌   │ ❌   │
│ Page Title {Unmapped}                │ ❌   │ ✅   │ ❌   │ ❌   │
│ Primary Navigation {Unmapped}        │ ❌   │ ❌   │ ✅   │ ❌   │
│ Prose Columns {Unmapped}             │ ❌   │ ❌   │ ✅   │ ❌   │
│ Related Pages                        │ ❌   │ ✅   │ ❌   │ ❌   │
│ Site Footer                          │ ✅   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Agent Unassigned Page (29 pgs)                                                                    │
│ • Content Page (3 pgs)                                                                              │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage (1 pgs)                                                                                  │
│ • PDF Document Page (1 pgs)                                                                         │
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
| tpl_0 | Agent Unassigned Page | Pages related to unassigned agent tasks. | https://www.lupronprostatecancer.com/support-and-resources, https://www.lupronprostatecancer.com/about-lupron-depot, https://www.lupronprostatecancer.com/faqs | 29 |
| tpl_1 | Content Page | General content pages for various topics. | https://www.lupronprostatecancer.com/about-lupron-depot/how-lupron-depot-is-given, https://www.lupronprostatecancer.com/getting-started, https://www.lupronprostatecancer.com/about-lupron-depot/common-side-effects | 3 |
| tpl_2 | Homepage | The main landing page of the website. | https://www.lupronprostatecancer.com/ | 1 |
| tpl_3 | PDF Document Page | Pages displaying or linking to PDF documents. | https://www.lupronprostatecancer.com/content/dam/lupronpatientivy/patient/pdf/keeptrackofscores.pdf | 1 |
