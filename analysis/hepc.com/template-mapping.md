# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **33** URLs; **7** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **PDF Resource**, **Information Page**, **Interactive Tool**. **32** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:53:45.420Z
- **Website**: https://www.hepc.com/
- **Total Pages Analyzed**: 33
- **Total Templates Identified**: 7
- **Total Components Identified**: 32
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.HEPC.COM TEMPLATES                                                       │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ PDF Resource                         │    │ Information Page                     │    │ Interactive Tool                     │
│ (10 pages)                           │    │ (10 pages)                           │    │ (5 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • —                                  │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │
│ • —                                  │    │ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │
│ • —                                  │    │ • Hero Section                       │    │ • Hero Section                       │
│ • —                                  │    │ • Breadcrumb Navigation {Unmapped}   │    │ • Interactive Tool {Unmapped}        │
│ • —                                  │    │ • (+9 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Sitemap                              │    │ Transcript Page                      │
│ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │
│ • Main Navigation {Unmapped}         │    │ • Header Logo {Unmapped}             │
│ • Main Content {Unmapped}            │    │ • Search Bar                         │
│ • (+5 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.HEPC.COM — SUB-TEMPLATES TEMPLATES                                       │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage                             │    │ Search Page                          │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │
│ • Primary Header {Unmapped}          │    │ • Primary Header {Unmapped}          │
│ • Main Navigation {Unmapped}         │    │ • Main Navigation {Unmapped}         │
│ • Hero Section                       │    │ • Search Hero {Unmapped}             │
│ • (+5 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### PDF Resource (`tpl_0`) — 10 pages

- —

### Information Page (`tpl_1`) — 10 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Breadcrumb Navigation {Unmapped}
- Content Introduction {Unmapped}
- Icon Grid {Unmapped}
- Fact Section {Unmapped}
- Testing Recommendations {Unmapped}
- Risk Factors {Unmapped}
- Statistics Section {Unmapped}
- Quote Section
- Next Steps CTA {Unmapped}
- Footer

### Interactive Tool (`tpl_2`) — 5 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Interactive Tool {Unmapped}
- Three Column CTA {Unmapped}
- CTA Section {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### Sitemap (`tpl_3`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Main Navigation {Unmapped}
- Main Content {Unmapped}
- Footer
- Back to Top Button {Unmapped}
- Terms of Use Modal
- Map Directions Modal
- Advertising Modal

### Transcript Page (`tpl_4`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Header Logo {Unmapped}
- Search Bar
- Main Content Area {Unmapped}
- Back to Top Button {Unmapped}
- Terms of Use Modal
- Map Directions Modal
- Advertising Modal

### Homepage (`tpl_5`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Main Navigation {Unmapped}
- Hero Section
- Interactive Info Poll {Unmapped}
- Feature Columns {Unmapped}
- Call-to-Action Section {Unmapped}
- Footer Links {Unmapped}
- Back to Top Button {Unmapped}

### Search Page (`tpl_6`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Main Navigation {Unmapped}
- Search Hero {Unmapped}
- Breadcrumb Navigation {Unmapped}
- Search Results
- Footer
- Back to Top {Unmapped}
- Modal Dialogs {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                        │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Back to Top Button {Unmapped}    │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Footer                           │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Primary Header {Unmapped}        │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │
│ Utility Navigation {Unmapped}    │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │
│ Hero Section                     │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Main Navigation {Unmapped}       │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │
│ Advertising Modal                │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Breadcrumb Navigation {Unmapped} │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Global Utility Strip {Unmapped}  │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Map Directions Modal             │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Primary Navigation {Unmapped}    │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Terms of Use Modal               │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │
└──────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                          │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Back to Top {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Call-to-Action Section {Unmapped}  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Content Introduction {Unmapped}    │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ CTA Section {Unmapped}             │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Fact Section {Unmapped}            │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Feature Columns {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Footer Links {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Header Logo {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Icon Grid {Unmapped}               │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Interactive Info Poll {Unmapped}   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Interactive Tool {Unmapped}        │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Main Content {Unmapped}            │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Main Content Area {Unmapped}       │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Modal Dialogs {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
└────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • PDF Resource (10 pgs)                                                                             │
│ • Information Page (10 pgs)                                                                         │
│ • Interactive Tool (5 pgs)                                                                          │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Sitemap (2 pgs)                                                                                   │
│ • Transcript Page (2 pgs)                                                                           │
│ • Homepage (1 pgs)                                                                                  │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Search Page (1 pgs)                                                                               │
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
| tpl_0 | PDF Resource | Pages containing downloadable PDF resources. | https://www.hepc.com/content/dam/hepc/pdf/your-doctor-discussion-guide-undiaognosed.pdf, https://www.hepc.com/content/dam/hepc/pdf/your-doctor-discussion-guide-diaognosed.pdf, https://www.hepc.com/content/dam/hepc/pdf/diagnosed-doctor-discussion-guide.pdf | 10 |
| tpl_1 | Information Page | Pages providing detailed information on various topics. | https://www.hepc.com/how-hep-c-transmitted, https://www.hepc.com/living-with-hep-c, https://www.hepc.com/hep-c-cure | 10 |
| tpl_2 | Interactive Tool | Pages featuring tools for user interaction or data manipulation. | https://www.hepc.com/personalization, https://www.hepc.com/find-hep-c-doctor, https://www.hepc.com/find-hep-c-specialist | 5 |
| tpl_3 | Sitemap | Pages displaying the website's structure and navigation paths. | https://www.hepc.com/sitemap, https://www.hepc.com/site-map | 2 |
| tpl_4 | Transcript Page | Pages providing transcripts of audio or video content. | https://www.hepc.com/living-with-hep-c/video-transcript-12, https://www.hepc.com/living-with-hep-c/video-transcript | 2 |
| tpl_5 | Homepage | The main landing page of the website. | https://www.hepc.com/ | 1 |
| tpl_6 | Search Page | Pages allowing users to search for content or resources. | https://www.hepc.com/search-results | 1 |
