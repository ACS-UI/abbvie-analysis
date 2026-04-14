# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **8** URLs; **4** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **PDF Document**, **Home Page**, **Interactive Tool**. **25** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:31:32.593Z
- **Website**: https://www.rheumfordialogue.abbvie.com/
- **Total Pages Analyzed**: 8
- **Total Templates Identified**: 4
- **Total Components Identified**: 25
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.RHEUMFORDIALOGUE.ABBVIE.COM TEMPLATES                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ PDF Document                         │    │ Home Page                            │    │ Interactive Tool                     │
│ (2 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • —                                  │    │ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │
│ • —                                  │    │ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Carousel                      │    │ • Hero Section                       │
│ • —                                  │    │ • Introduction Section {Unmapped}    │    │ • Main Content {Unmapped}            │
│ • —                                  │    │ • (+5 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Sitemap Page                         │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │
│ • Primary Header {Unmapped}          │
│ • Main Navigation {Unmapped}         │
│ • Sitemap Title {Unmapped}           │
│ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### PDF Document (`tpl_0`) — 2 pages

- —

### Home Page (`tpl_1`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Carousel
- Introduction Section {Unmapped}
- Tabs Section
- Joint Discussion Section {Unmapped}
- Resource Hub {Unmapped}
- Patient Assessment Tool {Unmapped}
- Footer References

### Interactive Tool (`tpl_2`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}
- Assessment Tool Embed
- Rich Text Information {Unmapped}
- Footer
- Back to Top Button {Unmapped}
- Cookie Consent {Unmapped}
- Modal Dialogs

### Sitemap Page (`tpl_3`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Main Navigation {Unmapped}
- Sitemap Title {Unmapped}
- Sitemap Links {Unmapped}
- Footer Support
- Footer Legal
- Back to Top Button {Unmapped}
- Warn on Leave Modal


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┤
│ Back to Top Button {Unmapped}        │ ❌   │ ❌   │ ✅   │ ✅   │
│ Global Utility Navigation {Unmapped} │ ❌   │ ✅   │ ✅   │ ❌   │
│ Primary Header {Unmapped}            │ ❌   │ ✅   │ ❌   │ ✅   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌─────────────────────────────────────┬─────┬─────┬─────┬─────┐
│ Component                           │ T1  │ T2  │ T3  │ T4  │
├─────────────────────────────────────┼─────┼─────┼─────┼─────┤
│ Assessment Tool Embed               │ ❌   │ ❌   │ ✅   │ ❌   │
│ Cookie Consent {Unmapped}           │ ❌   │ ❌   │ ✅   │ ❌   │
│ Footer                              │ ❌   │ ❌   │ ✅   │ ❌   │
│ Footer Legal                        │ ❌   │ ❌   │ ❌   │ ✅   │
│ Footer References                   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Footer Support                      │ ❌   │ ❌   │ ❌   │ ✅   │
│ Hero Carousel                       │ ❌   │ ✅   │ ❌   │ ❌   │
│ Hero Section                        │ ❌   │ ❌   │ ✅   │ ❌   │
│ Introduction Section {Unmapped}     │ ❌   │ ✅   │ ❌   │ ❌   │
│ Joint Discussion Section {Unmapped} │ ❌   │ ✅   │ ❌   │ ❌   │
│ Main Content {Unmapped}             │ ❌   │ ❌   │ ✅   │ ❌   │
│ Main Navigation {Unmapped}          │ ❌   │ ❌   │ ❌   │ ✅   │
│ Modal Dialogs                       │ ❌   │ ❌   │ ✅   │ ❌   │
│ Patient Assessment Tool {Unmapped}  │ ❌   │ ✅   │ ❌   │ ❌   │
└─────────────────────────────────────┴─────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • PDF Document (2 pgs)                                                                              │
│ • Home Page (1 pgs)                                                                                 │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Interactive Tool (1 pgs)                                                                          │
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
| tpl_0 | PDF Document | This template is for pages that primarily serve PDF documents. | https://www.rheumfordialogue.abbvie.com/content/dam/rheumfordialogue/pdf/RheumForDialogueSurveyInfographic.pdf, https://www.rheumfordialogue.abbvie.com/content/dam/rheumfordialogue/pdf/Giant-Cell-Arteritis-Fact-Sheet.pdf | 2 |
| tpl_1 | Home Page | This template represents the main landing page of the website. | https://www.rheumfordialogue.abbvie.com/ | 1 |
| tpl_2 | Interactive Tool | This template is used for pages containing interactive tools or applications. | https://www.rheumfordialogue.abbvie.com/patient-assessment-tool | 1 |
| tpl_3 | Sitemap Page | This template represents the sitemap of the website. | https://www.rheumfordialogue.abbvie.com/sitemap | 1 |
