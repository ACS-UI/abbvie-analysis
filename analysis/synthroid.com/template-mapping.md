# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **35** URLs; **8** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Downloadable Resources**, **Information Page**, **Homepage**. **30** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:19:51.280Z
- **Website**: https://www.synthroid.com/
- **Total Pages Analyzed**: 35
- **Total Templates Identified**: 8
- **Total Components Identified**: 30
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.SYNTHROID.COM TEMPLATES                                                  │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Downloadable Resources               │    │ Information Page                     │    │ Homepage                             │
│ (14 pages)                           │    │ (7 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • —                                  │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │
│ • —                                  │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section                       │    │ • Hero Section (Desktop)             │
│ • —                                  │    │ • Cards Section                      │    │ • Hero Section (Mobile)              │
│ • —                                  │    │ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Signup Page                          │    │ Search Results                       │    │ Sitemap                              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section {Unmapped}            │
│ • Signup Form                        │    │ • Search Results                     │    │ • Sitemap Links {Unmapped}           │
│ • (+3 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.SYNTHROID.COM — SUB-TEMPLATES TEMPLATES                                  │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ FAQ Page                             │    │ Program Page                         │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • FAQ Section: Synthroid {Unmapped}  │    │ • Tabs Section                       │
│ • (+2 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Downloadable Resources (`tpl_0`) — 14 pages

- —

### Information Page (`tpl_1`) — 7 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Cards Section
- Video Section
- Accordion Section
- Call to Action Section {Unmapped}
- Footer Section

### Homepage (`tpl_2`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section (Desktop)
- Hero Section (Mobile)
- Call-to-Action Cards
- Interactive Info Tree {Unmapped}
- Video Story Section
- Footer

### Signup Page (`tpl_3`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Signup Form
- Safety Information {Unmapped}
- Footer
- Back to Top {Unmapped}

### Search Results (`tpl_4`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Search Results
- Important Safety Information {Unmapped}
- Footer
- Back to Top {Unmapped}

### Sitemap (`tpl_5`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Sitemap Links {Unmapped}
- Safety Information {Unmapped}
- Footer Links {Unmapped}
- Back to Top Button {Unmapped}

### FAQ Page (`tpl_6`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section {Unmapped}
- FAQ Section: Synthroid {Unmapped}
- FAQ Section: Dosing {Unmapped}
- FAQ Section: Payment {Unmapped}

### Program Page (`tpl_7`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Tabs Section
- Benefits Cards
- Steps to Enroll {Unmapped}
- FAQ Section {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Primary Navigation {Unmapped}        │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Hero Section                         │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Utility Navigation {Unmapped}        │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │
│ Footer                               │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Global Utility Navigation {Unmapped} │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ✅   │
│ Back to Top {Unmapped}               │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Hero Section {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Primary Header {Unmapped}            │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Safety Information {Unmapped}        │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


### Template-specific components

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Accordion Section                       │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Back to Top Button {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Benefits Cards                          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call to Action Section {Unmapped}       │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Cards                    │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Cards Section                           │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ FAQ Section {Unmapped}                  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ FAQ Section: Dosing {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ FAQ Section: Payment {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ FAQ Section: Synthroid {Unmapped}       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Footer Links {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Footer Section                          │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Hero Section (Desktop)                  │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Hero Section (Mobile)                   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Downloadable Resources (14 pgs)                                                                   │
│ • Information Page (7 pgs)                                                                          │
│ • Homepage (1 pgs)                                                                                  │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Signup Page (1 pgs)                                                                               │
│ • Search Results (1 pgs)                                                                            │
│ • Sitemap (1 pgs)                                                                                   │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • FAQ Page (1 pgs)                                                                                  │
│ • Program Page (1 pgs)                                                                              │
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
| tpl_0 | Downloadable Resources | Templates for pages offering resources for download or viewing. | https://www.synthroid.com/content/dam/synthroidivy/docs/understanding_hypothyroidism.pdf, https://www.synthroid.com/content/dam/synthroidivy/docs/waiting-room.pdf, https://www.synthroid.com/content/dam/synthroidivy/docs/how-to-take-synthroid.pdf | 14 |
| tpl_1 | Information Page | Templates for pages providing detailed information or support. | https://www.synthroid.com/what-is-synthroid, https://www.synthroid.com/hypothyroidism-a-closer-look, https://www.synthroid.com/myths-facts | 7 |
| tpl_2 | Homepage | Templates for the main entry point of a website. | https://www.synthroid.com/ | 1 |
| tpl_3 | Signup Page | Templates for pages facilitating user registration. | https://www.synthroid.com/sign-up | 1 |
| tpl_4 | Search Results | Templates for pages displaying search outcomes. | https://www.synthroid.com/search-results | 1 |
| tpl_5 | Sitemap | Templates for pages displaying the website's structure. | https://www.synthroid.com/sitemap | 1 |
| tpl_6 | FAQ Page | Templates for frequently asked questions pages. | https://www.synthroid.com/faq | 1 |
| tpl_7 | Program Page | Templates for pages detailing specific programs or offerings. | https://www.synthroid.com/synthroid-delivers-program | 1 |
