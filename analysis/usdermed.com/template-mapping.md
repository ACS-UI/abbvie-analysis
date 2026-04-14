# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **35** URLs; **4** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Tool Pages**, **Overview Pages**, **Resource Pages**. **19** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:32:55.481Z
- **Website**: https://www.usdermed.com/
- **Total Pages Analyzed**: 35
- **Total Templates Identified**: 4
- **Total Components Identified**: 19
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.USDERMED.COM TEMPLATES                                                   │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Tool Pages                           │    │ Overview Pages                       │    │ Resource Pages                       │
│ (20 pages)                           │    │ (5 pages)                            │    │ (4 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • —                                  │
│ • Primary Header                     │    │ • Primary Header                     │    │ • —                                  │
│ • Hero Section                       │    │ • Hero Section                       │    │ • —                                  │
│ • Main Content {Unmapped}            │    │ • Section Navigation {Unmapped}      │    │ • —                                  │
│ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Navigation Pages                     │
│ (3 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Utility Navigation                 │
│ • Primary Navigation                 │
│ • Hero Section                       │
│ • Introductory Columns               │
│ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Tool Pages (`tpl_0`) — 20 pages

- Global Utility Strip {Unmapped}
- Primary Header
- Hero Section
- Main Content {Unmapped}
- CTA Section {Unmapped}
- Footer
- Back to Top Button {Unmapped}
- Modal Overlay

### Overview Pages (`tpl_1`) — 5 pages

- Global Utility Strip {Unmapped}
- Primary Header
- Hero Section
- Section Navigation {Unmapped}
- Disease Education Section {Unmapped}
- Treatment Considerations Section {Unmapped}
- Video Playlist
- Footer

### Resource Pages (`tpl_2`) — 4 pages

- —

### Navigation Pages (`tpl_3`) — 3 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Introductory Columns
- Call-to-Action Buttons
- Skin Tout Section
- Footer Links
- Back to Top Button {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────┬─────┬─────┬─────┬─────┐
│ Component                       │ T1  │ T2  │ T3  │ T4  │
├─────────────────────────────────┼─────┼─────┼─────┼─────┤
│ Hero Section                    │ ✅   │ ✅   │ ❌   │ ✅   │
│ Back to Top Button {Unmapped}   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Footer                          │ ✅   │ ✅   │ ❌   │ ❌   │
│ Global Utility Strip {Unmapped} │ ✅   │ ✅   │ ❌   │ ❌   │
│ Primary Header                  │ ✅   │ ✅   │ ❌   │ ❌   │
└─────────────────────────────────┴─────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌─────────────────────────────────────────────┬─────┬─────┬─────┬─────┐
│ Component                                   │ T1  │ T2  │ T3  │ T4  │
├─────────────────────────────────────────────┼─────┼─────┼─────┼─────┤
│ Call-to-Action Buttons                      │ ❌   │ ❌   │ ❌   │ ✅   │
│ CTA Section {Unmapped}                      │ ✅   │ ❌   │ ❌   │ ❌   │
│ Disease Education Section {Unmapped}        │ ❌   │ ✅   │ ❌   │ ❌   │
│ Footer Links                                │ ❌   │ ❌   │ ❌   │ ✅   │
│ Introductory Columns                        │ ❌   │ ❌   │ ❌   │ ✅   │
│ Main Content {Unmapped}                     │ ✅   │ ❌   │ ❌   │ ❌   │
│ Modal Overlay                               │ ✅   │ ❌   │ ❌   │ ❌   │
│ Primary Navigation                          │ ❌   │ ❌   │ ❌   │ ✅   │
│ Section Navigation {Unmapped}               │ ❌   │ ✅   │ ❌   │ ❌   │
│ Skin Tout Section                           │ ❌   │ ❌   │ ❌   │ ✅   │
│ Treatment Considerations Section {Unmapped} │ ❌   │ ✅   │ ❌   │ ❌   │
│ Utility Navigation                          │ ❌   │ ❌   │ ❌   │ ✅   │
│ Video Playlist                              │ ❌   │ ✅   │ ❌   │ ❌   │
└─────────────────────────────────────────────┴─────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Tool Pages (20 pgs)                                                                               │
│ • Overview Pages (5 pgs)                                                                            │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Resource Pages (4 pgs)                                                                            │
│ • Navigation Pages (3 pgs)                                                                          │
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
| tpl_0 | Tool Pages | Pages featuring clinical and diagnostic tools. | https://www.usdermed.com/clinical-tools/napsi, https://www.usdermed.com/clinical-tools/pga, https://www.usdermed.com/clinical-tools/wi-nrs | 20 |
| tpl_1 | Overview Pages | Pages providing overviews for various medical conditions. | https://www.usdermed.com/atopic-dermatitis, https://www.usdermed.com/hidradenitis-suppurativa, https://www.usdermed.com/alopecia-areata | 5 |
| tpl_2 | Resource Pages | Pages offering downloadable resources and clinical tools. | https://www.usdermed.com/content/dam/abbviederm/pdf/2026-AASc-and-US-Guidelines.pdf, https://www.usdermed.com/clinical-tools, https://www.usdermed.com/clinical-tools/disease-state-options | 4 |
| tpl_3 | Navigation Pages | Pages designed for site navigation and structure. | https://www.usdermed.com/, https://www.usdermed.com/sitemap, https://www.usdermed.com/site-map | 3 |
