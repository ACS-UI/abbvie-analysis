# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **15** URLs; **8** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Featured Experts and Speakers**, **Homepage**, **Resource Page**. **30** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:09:57.609Z
- **Website**: https://www.digitalobgyn.com/
- **Total Pages Analyzed**: 15
- **Total Templates Identified**: 8
- **Total Components Identified**: 30
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.DIGITALOBGYN.COM TEMPLATES                                               │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Featured Experts and Speakers        │    │ Homepage                             │    │ Resource Page                        │
│ (2 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation                 │    │ • Utility Navigation                 │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │    │ • Primary Navigation                 │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Banner                        │
│ • Featured Experts Section {Unmappe… │    │ • Welcome Section {Unmapped}         │    │ • Section Tabs Navigation            │
│ • (+2 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Sitemap Page                         │    │ Information Request Page             │    │ Endometriosis Section                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • —                                  │    │ • Utility Navigation                 │
│ • Primary Navigation {Unmapped}      │    │ • —                                  │    │ • Primary Navigation                 │
│ • Header Logo {Unmapped}             │    │ • —                                  │    │ • Hero Section                       │
│ • Sitemap Heading {Unmapped}         │    │ • —                                  │    │ • Main Content Columns               │
│ • (+4 more — see Blocks mapped per … │    │ • —                                  │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.DIGITALOBGYN.COM — SUB-TEMPLATES TEMPLATES                               │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Bone Health Section                  │    │ Uterine Fibroids Section             │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Banner {Unmapped}             │
│ • Bone Health 101 {Unmapped}         │    │ • Video Library                      │
│ • (+5 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Featured Experts and Speakers (`tpl_0`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Featured Experts Section {Unmapped}
- Expert Accordion
- Footer

### Homepage (`tpl_1`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Welcome Section {Unmapped}
- Endometriosis Resources
- Footer Section
- Back to Top {Unmapped}

### Resource Page (`tpl_2`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Banner
- Section Tabs Navigation
- Patient Advocacy Cards
- Partnerships Cards
- Endometriosis Resources Cards
- Footer Section

### Sitemap Page (`tpl_3`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Header Logo {Unmapped}
- Sitemap Heading {Unmapped}
- Sitemap Links {Unmapped}
- Footer Links {Unmapped}
- Footer Legal Text {Unmapped}
- Back to Top Button {Unmapped}

### Information Request Page (`tpl_4`) — 1 pages

- —

### Endometriosis Section (`tpl_5`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Main Content Columns
- Section Navigation
- Video Library
- Dyspareunia Section
- Footer

### Bone Health Section (`tpl_6`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Bone Health 101 {Unmapped}
- Bone Density Measurement {Unmapped}
- Bone Mass Overview {Unmapped}
- Bone Mass Factors {Unmapped}
- Bone and Estrogen {Unmapped}
- Bone Summary {Unmapped}

### Uterine Fibroids Section (`tpl_7`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Banner {Unmapped}
- Video Library
- Section Navigation {Unmapped}
- Footer


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌───────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                     │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├───────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                  │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Primary Navigation {Unmapped} │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Utility Navigation {Unmapped} │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Footer                        │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Primary Navigation            │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Utility Navigation            │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Footer Section                │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Video Library                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
└───────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


### Template-specific components

```
┌─────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                           │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Back to Top {Unmapped}              │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Back to Top Button {Unmapped}       │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Bone and Estrogen {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Bone Density Measurement {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Bone Health 101 {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Bone Mass Factors {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Bone Mass Overview {Unmapped}       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Bone Summary {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Dyspareunia Section                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Endometriosis Resources             │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Endometriosis Resources Cards       │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Expert Accordion                    │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Featured Experts Section {Unmapped} │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Legal Text {Unmapped}        │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Featured Experts and Speakers (2 pgs)                                                             │
│ • Homepage (1 pgs)                                                                                  │
│ • Resource Page (1 pgs)                                                                             │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Sitemap Page (1 pgs)                                                                              │
│ • Information Request Page (1 pgs)                                                                  │
│ • Endometriosis Section (1 pgs)                                                                     │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Bone Health Section (1 pgs)                                                                       │
│ • Uterine Fibroids Section (1 pgs)                                                                  │
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
| tpl_0 | Featured Experts and Speakers | A template showcasing notable experts and speakers. | https://www.digitalobgyn.com/featured-experts, https://www.digitalobgyn.com/featured-speakers | 2 |
| tpl_1 | Homepage | The main landing page of the website. | https://www.digitalobgyn.com/ | 1 |
| tpl_2 | Resource Page | A template dedicated to providing resources and materials. | https://www.digitalobgyn.com/resources#patient-advocacy | 1 |
| tpl_3 | Sitemap Page | A page displaying the sitemap for navigation. | https://www.digitalobgyn.com/sitemap | 1 |
| tpl_4 | Information Request Page | A form page for requesting additional information. | https://www.digitalobgyn.com/find-my-msl | 1 |
| tpl_5 | Endometriosis Section | A page template focusing on endometriosis-related content. | https://www.digitalobgyn.com/endometriosis | 1 |
| tpl_6 | Bone Health Section | A page template dedicated to information about bone health. | https://www.digitalobgyn.com/bonehealth | 1 |
| tpl_7 | Uterine Fibroids Section | A page template focusing on uterine fibroids-related content. | https://www.digitalobgyn.com/uterinefibroids | 1 |
