# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **17** URLs; **13** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Homepage**, **Savings Card**, **Side Effects**. **48** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:37:13.247Z
- **Website**: https://www.oriahnn.com/
- **Total Pages Analyzed**: 17
- **Total Templates Identified**: 13
- **Total Components Identified**: 48
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.ORIAHNN.COM TEMPLATES                                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage                             │    │ Savings Card                         │    │ Side Effects                         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │    │ • Hero Section {Unmapped}            │
│ • Call-to-Action Section {Unmapped}  │    │ • Introduction Columns               │    │ • Side Effects Summary {Unmapped}    │
│ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Search Results                       │    │ Product Overview                     │    │ Insurance Information                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │
│ • Main Site Navigation {Unmapped}    │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Page Hero Section {Unmapped}       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Search Results Display {Unmapped}  │    │ • Introduction Columns               │    │ • Two-Column CTA {Unmapped}          │
│ • (+2 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Site Map                             │    │ Interactive Quiz                     │    │ Usage Instructions                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation                 │
│ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • Site Map Content                   │    │ • Quiz Introduction {Unmapped}       │    │ • Daily Routine Section {Unmapped}   │
│ • (+2 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.ORIAHNN.COM — SUB-TEMPLATES TEMPLATES                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Discussion Guide                     │    │ Symptoms Information                 │    │ Fibroids Information                 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section                       │    │ • Hero Section                       │
│ • —                                  │    │ • Symptoms Highlight {Unmapped}      │    │ • Introduction Columns               │
│ • —                                  │    │ • (+5 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Clinical Trials                      │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │
│ • Introduction Text {Unmapped}       │
│ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Homepage (`tpl_0`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Call-to-Action Section {Unmapped}
- Icon and Text Section {Unmapped}
- Savings Card Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer {Unmapped}

### Savings Card (`tpl_1`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Columns
- Savings Card Section
- Eligibility Form
- Support Section {Unmapped}
- Important Safety Information {Unmapped}

### Side Effects (`tpl_2`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Side Effects Summary {Unmapped}
- Side Effects Details {Unmapped}
- Discontinuation Statistics {Unmapped}
- Call-to-Action Section {Unmapped}
- Important Safety Information {Unmapped}

### Search Results (`tpl_3`) — 1 pages

- Global Utility Navigation {Unmapped}
- Main Site Navigation {Unmapped}
- Page Hero Section {Unmapped}
- Search Results Display {Unmapped}
- Safety Information Section {Unmapped}
- Page Footer {Unmapped}

### Product Overview (`tpl_4`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Columns
- Quick Benefits {Unmapped}
- Detailed Information {Unmapped}
- CTA Proven Results {Unmapped}
- CTA Gynecologist {Unmapped}
- Safety Information {Unmapped}

### Insurance Information (`tpl_5`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Two-Column CTA {Unmapped}
- Form Embed
- Support Section {Unmapped}
- Safety Information {Unmapped}

### Site Map (`tpl_6`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Site Map Content
- Important Safety Information
- Footer Section

### Interactive Quiz (`tpl_7`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Quiz Introduction {Unmapped}
- Quiz Form {Unmapped}
- Safety Information Section {Unmapped}
- Footer Links {Unmapped}

### Usage Instructions (`tpl_8`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Daily Routine Section {Unmapped}
- Morning Capsule Instruction {Unmapped}
- Evening Capsule Instruction {Unmapped}
- Schedule Guidance {Unmapped}
- Food Guidance {Unmapped}
- Savings Information
- Important Safety Information

### Discussion Guide (`tpl_9`) — 1 pages

- Utility Navigation
- Primary Navigation

### Symptoms Information (`tpl_10`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Symptoms Highlight {Unmapped}
- Interactive Quiz CTA {Unmapped}
- Symptoms Details {Unmapped}
- Signs Section {Unmapped}
- Helpful Resources {Unmapped}
- Safety Information {Unmapped}

### Fibroids Information (`tpl_11`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Columns
- Who Gets Uterine Fibroids?
- Types of Fibroids
- Call-to-Action Tout Section {Unmapped}
- Next Page Call-to-Action {Unmapped}
- Important Safety Information {Unmapped}

### Clinical Trials (`tpl_12`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Text {Unmapped}
- Clinical Trial Summary {Unmapped}
- Accordion Section
- Hemoglobin Results {Unmapped}
- Carousel Section
- Call to Action Section {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Primary Navigation {Unmapped}           │ ✅   │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Hero Section                            │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │
│ Utility Navigation {Unmapped}           │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Global Utility Navigation {Unmapped}    │ ✅   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Important Safety Information {Unmapped} │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Hero Section {Unmapped}                 │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Introduction Columns                    │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Primary Navigation                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Safety Information {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Utility Navigation                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Call-to-Action Section {Unmapped}       │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Important Safety Information            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Safety Information Section {Unmapped}   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Support Section {Unmapped}              │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T13 omitted from matrix width; see appendix.*


### Template-specific components

```
┌────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                              │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Accordion Section                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call to Action Section {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Tout Section {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Carousel Section                       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Clinical Trial Summary {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ CTA Gynecologist {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ CTA Proven Results {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Daily Routine Section {Unmapped}       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Detailed Information {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Discontinuation Statistics {Unmapped}  │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Eligibility Form                       │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Evening Capsule Instruction {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Food Guidance {Unmapped}               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer {Unmapped}                      │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T13 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage (1 pgs)                                                                                  │
│ • Savings Card (1 pgs)                                                                              │
│ • Side Effects (1 pgs)                                                                              │
│ • Search Results (1 pgs)                                                                            │
│ • Product Overview (1 pgs)                                                                          │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Insurance Information (1 pgs)                                                                     │
│ • Site Map (1 pgs)                                                                                  │
│ • Interactive Quiz (1 pgs)                                                                          │
│ • Usage Instructions (1 pgs)                                                                        │
│ • Discussion Guide (1 pgs)                                                                          │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Symptoms Information (1 pgs)                                                                      │
│ • Fibroids Information (1 pgs)                                                                      │
│ • Clinical Trials (1 pgs)                                                                           │
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
| tpl_0 | Homepage | The main landing page of the website. | https://www.oriahnn.com/ | 1 |
| tpl_1 | Savings Card | Pages about savings card offers. | https://www.oriahnn.com/savings-card | 1 |
| tpl_2 | Side Effects | Pages describing potential side effects. | https://www.oriahnn.com/side-effects-and-safety-considerations | 1 |
| tpl_3 | Search Results | Pages displaying search results. | https://www.oriahnn.com/search-results | 1 |
| tpl_4 | Product Overview | Pages summarizing product details. | https://www.oriahnn.com/what-is-oriahnn | 1 |
| tpl_5 | Insurance Information | Pages detailing insurance-related information. | https://www.oriahnn.com/savings-and-insurance | 1 |
| tpl_6 | Site Map | Pages showing the website's structure. | https://www.oriahnn.com/site-map | 1 |
| tpl_7 | Interactive Quiz | Pages featuring interactive quizzes. | https://www.oriahnn.com/heavy-periods-quiz | 1 |
| tpl_8 | Usage Instructions | Pages providing instructions for usage. | https://www.oriahnn.com/how-to-take-oriahnn | 1 |
| tpl_9 | Discussion Guide | Pages containing guides for discussions. | https://www.oriahnn.com/talking-to-your-gynecologist | 1 |
| tpl_10 | Symptoms Information | Pages detailing symptoms of conditions. | https://www.oriahnn.com/uterine-fibroids-symptoms | 1 |
| tpl_11 | Fibroids Information | Pages offering details about fibroids. | https://www.oriahnn.com/what-are-uterine-fibroids | 1 |
| tpl_12 | Clinical Trials | Pages providing information about clinical trials. | https://www.oriahnn.com/clinical-trials | 1 |
