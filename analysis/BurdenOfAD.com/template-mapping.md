# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **15** URLs; **7** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Sitemap Page**, **Home Page**, **PDF Resource**. **32** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:21:43.942Z
- **Website**: https://www.burdenofad.com/
- **Total Pages Analyzed**: 15
- **Total Templates Identified**: 7
- **Total Components Identified**: 32
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.BURDENOFAD.COM TEMPLATES                                                 │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Sitemap Page                         │    │ Home Page                            │    │ PDF Resource                         │
│ (2 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Global Utility Navigation {Unmapp… │    │ • —                                  │
│ • Primary Navigation                 │    │ • Primary Header                     │    │ • —                                  │
│ • Main Content {Unmapped}            │    │ • Hero Carousel                      │    │ • —                                  │
│ • Footer Links                       │    │ • Statistics Section {Unmapped}      │    │ • —                                  │
│ • (+3 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Treatment Options                    │    │ Patient Outcomes                     │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Header                     │
│ • Hero Section                       │    │ • Main Navigation {Unmapped}         │
│ • Introduction Text {Unmapped}       │    │ • Hero Section                       │
│ • (+5 more — see Blocks mapped per … │    │ • (+7 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.BURDENOFAD.COM — SUB-TEMPLATES TEMPLATES                                 │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Mechanism of Disease                 │    │ Resources Page                       │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation          │    │ • Global Utility Navigation {Unmapp… │
│ • Main Navigation Header             │    │ • Primary Navigation {Unmapped}      │
│ • Page Hero Section                  │    │ • Hero Section                       │
│ • Introductory Content {Unmapped}    │    │ • Tools and Information Section {Un… │
│ • (+6 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Sitemap Page (`tpl_0`) — 2 pages

- Utility Navigation
- Primary Navigation
- Main Content {Unmapped}
- Footer Links
- Footer Legal Text
- Back to Top {Unmapped}
- Modal Component

### Home Page (`tpl_1`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header
- Hero Carousel
- Statistics Section {Unmapped}
- Testimonial Section {Unmapped}
- Video Section
- Footer

### PDF Resource (`tpl_2`) — 1 pages

- —

### Treatment Options (`tpl_3`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Text {Unmapped}
- Treatment Options Accordion
- Guidelines Section {Unmapped}
- Call to Action Section {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### Patient Outcomes (`tpl_4`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Header
- Main Navigation {Unmapped}
- Hero Section
- Introduction Text {Unmapped}
- Tabbed Content
- Chart Section {Unmapped}
- Accordion Section
- Call to Action {Unmapped}
- Testimonial Section {Unmapped}
- Video Section

### Mechanism of Disease (`tpl_5`) — 1 pages

- Global Utility Navigation
- Main Navigation Header
- Page Hero Section
- Introductory Content {Unmapped}
- Content Navigation Tabs
- Visual Content Display
- Call-to-Action Section {Unmapped}
- Page Footer
- Back to Top Button {Unmapped}
- Modal Dialogs

### Resources Page (`tpl_6`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Tools and Information Section {Unmapped}
- Patient Eczema Assessment {Unmapped}
- Footer


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Footer                               │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Hero Section                         │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │
│ Back to Top Button {Unmapped}        │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │
│ Global Utility Navigation {Unmapped} │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Introduction Text {Unmapped}         │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Primary Header                       │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Primary Navigation {Unmapped}        │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Testimonial Section {Unmapped}       │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Utility Navigation {Unmapped}        │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Video Section                        │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Accordion Section                    │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Back to Top {Unmapped}               │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call to Action {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Call to Action Section {Unmapped}    │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Section {Unmapped}    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Chart Section {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Content Navigation Tabs              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Footer Legal Text                    │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Links                         │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global Utility Navigation            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Guidelines Section {Unmapped}        │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Hero Carousel                        │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Introductory Content {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Main Content {Unmapped}              │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Sitemap Page (2 pgs)                                                                              │
│ • Home Page (1 pgs)                                                                                 │
│ • PDF Resource (1 pgs)                                                                              │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Treatment Options (1 pgs)                                                                         │
│ • Patient Outcomes (1 pgs)                                                                          │
│ • Mechanism of Disease (1 pgs)                                                                      │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Resources Page (1 pgs)                                                                            │
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
| tpl_0 | Sitemap Page | Page displaying the website's sitemap for navigation. | https://www.burdenofad.com/sitemap, https://www.burdenofad.com/site-map | 2 |
| tpl_1 | Home Page | The main landing page of the website. | https://www.burdenofad.com/ | 1 |
| tpl_2 | PDF Resource | Page providing downloadable PDF resources. | https://www.burdenofad.com/content/dam/burdenofad/docs/eczema-assesment.pdf | 1 |
| tpl_3 | Treatment Options | Page detailing available treatments and therapies. | https://www.burdenofad.com/atopic-dermatitis-treatment-options | 1 |
| tpl_4 | Patient Outcomes | Page focusing on results and benefits for patients. | https://www.burdenofad.com/patient-reported-outcomes | 1 |
| tpl_5 | Mechanism of Disease | Page describing the underlying causes and processes of diseases. | https://www.burdenofad.com/mechanism-of-disease | 1 |
| tpl_6 | Resources Page | Page listing available resources and tools. | https://www.burdenofad.com/resources | 1 |
