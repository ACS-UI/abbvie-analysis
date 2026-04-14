# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **39** URLs; **3** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Resource PDF**, **Information Page**, **Home Page**. **16** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:17:29.690Z
- **Website**: https://www.synthroidpro.com/
- **Total Pages Analyzed**: 39
- **Total Templates Identified**: 3
- **Total Components Identified**: 16
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.SYNTHROIDPRO.COM TEMPLATES                                               │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Resource PDF                         │    │ Information Page                     │    │ Home Page                            │
│ (19 pages)                           │    │ (7 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • —                                  │    │ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │
│ • —                                  │    │ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Main Navigation {Unmapped}         │    │ • Hero Section (Desktop)             │
│ • —                                  │    │ • Hero Section                       │    │ • Hero Section (Mobile)              │
│ • —                                  │    │ • (+6 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Resource PDF (`tpl_0`) — 19 pages

- —

### Information Page (`tpl_1`) — 7 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Main Navigation {Unmapped}
- Hero Section
- Content Highlight
- Copay Card Section {Unmapped}
- Cash Pay Program {Unmapped}
- Program Benefits {Unmapped}
- Simple Start {Unmapped}
- Enrollment Options {Unmapped}

### Home Page (`tpl_2`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section (Desktop)
- Hero Section (Mobile)
- Card Grid
- Important Safety Information {Unmapped}
- Footer


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │
├──────────────────────────────────────┼─────┼─────┼─────┤
│ Global Utility Navigation {Unmapped} │ ❌   │ ✅   │ ✅   │
└──────────────────────────────────────┴─────┴─────┴─────┘
```


### Template-specific components

```
┌─────────────────────────────────────────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │
├─────────────────────────────────────────┼─────┼─────┼─────┤
│ Card Grid                               │ ❌   │ ❌   │ ✅   │
│ Cash Pay Program {Unmapped}             │ ❌   │ ✅   │ ❌   │
│ Content Highlight                       │ ❌   │ ✅   │ ❌   │
│ Copay Card Section {Unmapped}           │ ❌   │ ✅   │ ❌   │
│ Enrollment Options {Unmapped}           │ ❌   │ ✅   │ ❌   │
│ Footer                                  │ ❌   │ ❌   │ ✅   │
│ Hero Section                            │ ❌   │ ✅   │ ❌   │
│ Hero Section (Desktop)                  │ ❌   │ ❌   │ ✅   │
│ Hero Section (Mobile)                   │ ❌   │ ❌   │ ✅   │
│ Important Safety Information {Unmapped} │ ❌   │ ❌   │ ✅   │
│ Main Navigation {Unmapped}              │ ❌   │ ✅   │ ❌   │
│ Primary Header {Unmapped}               │ ❌   │ ✅   │ ❌   │
│ Primary Navigation {Unmapped}           │ ❌   │ ❌   │ ✅   │
│ Program Benefits {Unmapped}             │ ❌   │ ✅   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┘
```


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Resource PDF (19 pgs)                                                                             │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Information Page (7 pgs)                                                                          │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Home Page (1 pgs)                                                                                 │
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
| tpl_0 | Resource PDF | Pages providing downloadable PDF resources. | https://www.synthroidpro.com/content/dam/synthroidproivy/Images/SYNT-INT-0801/Synthroid_How_To_Take.pdf, https://www.synthroidpro.com/content/dam/synthroidproivy/Images/SYNT-INT-0801/Synthroid_Doctor_Discussion_Guide.pdf, https://www.synthroidpro.com/content/dam/synthroidproivy/Images/SYNT-INT-0801/Synthroid_Patient_Brochure_Digital.pdf | 19 |
| tpl_1 | Information Page | Pages containing general information about topics. | https://www.synthroidpro.com/cost-coverage#savings, https://www.synthroidpro.com/references, https://www.synthroidpro.com/sitemap | 7 |
| tpl_2 | Home Page | The main landing page for the website. | https://www.synthroidpro.com/ | 1 |
