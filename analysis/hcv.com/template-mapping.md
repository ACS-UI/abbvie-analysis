# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **30** URLs; **9** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Living with HCV**, **Awareness Content**, **Resources Content**. **42** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:23:45.315Z
- **Website**: https://www.hcv.com/
- **Total Pages Analyzed**: 30
- **Total Templates Identified**: 9
- **Total Components Identified**: 42
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.HCV.COM TEMPLATES                                                        │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Living with HCV                      │    │ Awareness Content                    │    │ Resources Content                    │
│ (5 pages)                            │    │ (4 pages)                            │    │ (4 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Main Navigation                    │    │ • Primary Header {Unmapped}          │
│ • Hero Banner {Unmapped}             │    │ • Hero Section                       │    │ • Hero Section {Unmapped}            │
│ • Breadcrumb Trail {Unmapped}        │    │ • Breadcrumb Navigation {Unmapped}   │    │ • Breadcrumb Navigation {Unmapped}   │
│ • (+6 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Management Content                   │    │ Screening Content                    │    │ Provider Resources                   │
│ (3 pages)                            │    │ (3 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Breadcrumb Navigation {Unmapped}   │    │ • Breadcrumb Navigation {Unmapped}   │    │ • New HCV Providers Section {Unmapp… │
│ • (+2 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.HCV.COM — SUB-TEMPLATES TEMPLATES                                        │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage                             │    │ Search Results                       │    │ External Link Modal                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │    │ • Modal Header                       │
│ • Primary Header                     │    │ • Primary Navigation {Unmapped}      │    │ • Modal Body Text {Unmapped}         │
│ • Hero Section                       │    │ • Search Results Header {Unmapped}   │    │ • Modal CTA - Yes {Unmapped}         │
│ • New HCV Providers                  │    │ • Search Controls                    │    │ • Modal CTA - Cancel {Unmapped}      │
│ • (+8 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Living with HCV (`tpl_0`) — 5 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Banner {Unmapped}
- Breadcrumb Trail {Unmapped}
- Content Introduction {Unmapped}
- Detailed Information {Unmapped}
- Healthcare Insights {Unmapped}
- Broader Implications {Unmapped}
- Resources Section {Unmapped}
- Footer {Unmapped}

### Awareness Content (`tpl_1`) — 4 pages

- Utility Navigation
- Main Navigation
- Hero Section
- Breadcrumb Navigation {Unmapped}
- Section Title
- Video Highlight
- Video Grid

### Resources Content (`tpl_2`) — 4 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section {Unmapped}
- Breadcrumb Navigation {Unmapped}
- Content Introduction {Unmapped}
- Card Grid {Unmapped}
- Footer Links {Unmapped}

### Management Content (`tpl_3`) — 3 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Breadcrumb Navigation {Unmapped}
- On-Treatment Monitoring Section {Unmapped}
- Footer Links

### Screening Content (`tpl_4`) — 3 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Breadcrumb Navigation {Unmapped}
- Screening Guides Section {Unmapped}
- Footer Section

### Provider Resources (`tpl_5`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- New HCV Providers Section {Unmapped}
- Existing HCV Providers Section {Unmapped}
- Tabs Section
- Awareness Tab {Unmapped}
- Footer

### Homepage (`tpl_6`) — 1 pages

- Utility Navigation
- Primary Header
- Hero Section
- New HCV Providers
- Existing HCV Providers
- Welcome Section
- Awareness Card
- Screening & Assessments Card
- Management Card
- Living With HCV Card
- Resources Card
- Footer Section

### Search Results (`tpl_7`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Search Results Header {Unmapped}
- Search Controls
- Sort Accordion
- Filter Accordion
- Search Results List {Unmapped}
- Footer

### External Link Modal (`tpl_8`) — 1 pages

- Modal Header
- Modal Body Text {Unmapped}
- Modal CTA - Yes {Unmapped}
- Modal CTA - Cancel {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                         │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Primary Navigation {Unmapped}        │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Breadcrumb Navigation {Unmapped}     │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Utility Navigation {Unmapped}        │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Content Introduction {Unmapped}      │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer                               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Footer Section                       │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │
│ Global Utility Navigation {Unmapped} │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Utility Navigation                   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T9 omitted from matrix width; see appendix.*


### Template-specific components

```
┌───────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                 │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├───────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Awareness Card                            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Awareness Tab {Unmapped}                  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Breadcrumb Trail {Unmapped}               │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Broader Implications {Unmapped}           │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Card Grid {Unmapped}                      │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Detailed Information {Unmapped}           │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Existing HCV Providers                    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Existing HCV Providers Section {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Filter Accordion                          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer {Unmapped}                         │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Links                              │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Footer Links {Unmapped}                   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Healthcare Insights {Unmapped}            │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Hero Banner {Unmapped}                    │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└───────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T9 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Living with HCV (5 pgs)                                                                           │
│ • Awareness Content (4 pgs)                                                                         │
│ • Resources Content (4 pgs)                                                                         │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Management Content (3 pgs)                                                                        │
│ • Screening Content (3 pgs)                                                                         │
│ • Provider Resources (2 pgs)                                                                        │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage (1 pgs)                                                                                  │
│ • Search Results (1 pgs)                                                                            │
│ • External Link Modal (1 pgs)                                                                       │
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
| tpl_0 | Living with HCV | Templates for living with HCV overview and profile pages. | https://www.hcv.com/living-with-hcv/meet-maria, https://www.hcv.com/living-with-hcv, https://www.hcv.com/living-with-hcv/meet-mark | 5 |
| tpl_1 | Awareness Content | Templates related to awareness articles and overview pages. | https://www.hcv.com/awareness/people-who-use-drugs, https://www.hcv.com/awareness, https://www.hcv.com/awareness/liver-and-cirrhosis | 4 |
| tpl_2 | Resources Content | Templates for glossary, overview, patient, and Spanish resources. | https://www.hcv.com/resources/spanish-resources, https://www.hcv.com/resources, https://www.hcv.com/resources/resources-for-your-patient | 4 |
| tpl_3 | Management Content | Templates related to management articles and overview pages. | https://www.hcv.com/management, https://www.hcv.com/management/hcv-and-substance-use, https://www.hcv.com/management/posttreatment-follow-up | 3 |
| tpl_4 | Screening Content | Templates related to screening articles and overview pages. | https://www.hcv.com/screening-assessments, https://www.hcv.com/screening-assessments/pretreatment-assessments, https://www.hcv.com/screening-assessments/clinical-calculators | 3 |
| tpl_5 | Provider Resources | Template for provider-specific resources. | https://www.hcv.com/new-hcv-providers, https://www.hcv.com/existing-hcv-providers | 2 |
| tpl_6 | Homepage | Template for the main homepage. | https://www.hcv.com/ | 1 |
| tpl_7 | Search Results | Template for displaying search results. | https://www.hcv.com/search-results | 1 |
| tpl_8 | External Link Modal | Template for external link modal functionality. | https://www.hcv.com/modals/wolexternallink/wolcdcviralhepatitisamongpeoplewithhiv | 1 |
