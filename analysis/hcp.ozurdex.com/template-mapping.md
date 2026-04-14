# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **30** URLs; **8** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **PDF Document**, **HCP Homepage**, **HCP Resources**. **37** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:42:44.255Z
- **Website**: https://hcp.ozurdex.com/
- **Total Pages Analyzed**: 30
- **Total Templates Identified**: 8
- **Total Components Identified**: 37
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│HCP.OZURDEX.COM TEMPLATES                                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ PDF Document                         │    │ HCP Homepage                         │    │ HCP Resources                        │
│ (12 pages)                           │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • —                                  │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • —                                  │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section                       │    │ • Hero Section                       │
│ • —                                  │    │ • Mechanism of Action {Unmapped}     │    │ • Sticky Menu {Unmapped}             │
│ • —                                  │    │ • (+5 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ HCP Reimbursement                    │    │ HCP Mechanism of Action              │    │ HCP Clinical Efficacy                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Reimbursement Support Intro {Unma… │    │ • Highlighted Links {Unmapped}       │    │ • Sticky Navigation {Unmapped}       │
│ • (+4 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│HCP.OZURDEX.COM — SUB-TEMPLATES TEMPLATES                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ HCP Sitemap                          │    │ HCP About Ozurdex                    │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation                 │    │ • Main Navigation {Unmapped}         │
│ • Hero Section                       │    │ • Hero Section                       │
│ • Sitemap Links                      │    │ • Sticky Menu {Unmapped}             │
│ • (+2 more — see Blocks mapped per … │    │ • (+7 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### PDF Document (`tpl_0`) — 12 pages

- —

### HCP Homepage (`tpl_1`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Mechanism of Action {Unmapped}
- Injection Technique {Unmapped}
- Reimbursement Support {Unmapped}
- Resources Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### HCP Resources (`tpl_2`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Sticky Menu {Unmapped}
- Practice Tools {Unmapped}
- Injection Resources {Unmapped}
- Brochure Download {Unmapped}
- Ordering Support {Unmapped}
- Discussion Guide {Unmapped}
- FAQs Accordion

### HCP Reimbursement (`tpl_3`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Reimbursement Support Intro {Unmapped}
- Reimbursement Support Details {Unmapped}
- Contact Information {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### HCP Mechanism of Action (`tpl_4`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Highlighted Links {Unmapped}
- Mechanism of Action {Unmapped}
- NOVADUR Technology {Unmapped}
- Patented Applicator {Unmapped}
- Patient Resources {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### HCP Clinical Efficacy (`tpl_5`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Sticky Navigation {Unmapped}
- Study Design Section {Unmapped}
- Efficacy Outcomes {Unmapped}
- Results in Overall Patients {Unmapped}
- Pseudophakic Patients {Unmapped}
- Phakic Patients {Unmapped}
- Footer

### HCP Sitemap (`tpl_6`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Sitemap Links
- Important Safety Information
- Footer

### HCP About Ozurdex (`tpl_7`) — 1 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Hero Section
- Sticky Menu {Unmapped}
- Macular Edema Info {Unmapped}
- Pathophysiology Info {Unmapped}
- Targeting Inflammation Info {Unmapped}
- Clinical Trials Info {Unmapped}
- Introducing Ozurdex Info {Unmapped}
- Patient Resources {Unmapped}
- Safety Information {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                            │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Footer                                  │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Primary Navigation {Unmapped}           │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Important Safety Information {Unmapped} │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Utility Navigation {Unmapped}           │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Global Utility Navigation {Unmapped}    │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Mechanism of Action {Unmapped}          │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Patient Resources {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Sticky Menu {Unmapped}                  │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


### Template-specific components

```
┌──────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Brochure Download {Unmapped}             │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Clinical Trials Info {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Contact Information {Unmapped}           │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Discussion Guide {Unmapped}              │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Efficacy Outcomes {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ FAQs Accordion                           │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global Utility Strip {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Highlighted Links {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Important Safety Information             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Injection Resources {Unmapped}           │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Injection Technique {Unmapped}           │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Introducing Ozurdex Info {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Macular Edema Info {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Main Navigation {Unmapped}               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • PDF Document (12 pgs)                                                                             │
│ • HCP Homepage (1 pgs)                                                                              │
│ • HCP Resources (1 pgs)                                                                             │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • HCP Reimbursement (1 pgs)                                                                         │
│ • HCP Mechanism of Action (1 pgs)                                                                   │
│ • HCP Clinical Efficacy (1 pgs)                                                                     │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • HCP Sitemap (1 pgs)                                                                               │
│ • HCP About Ozurdex (1 pgs)                                                                         │
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
| tpl_0 | PDF Document | Collection of downloadable PDF documents related to Ozurdex. | https://hcp.ozurdex.com/content/dam/ozurdexhcp/pdf/US-OZU-230009_020857_OZX-Injection-Technique-Supplement_HR.pdf, https://hcp.ozurdex.com/content/dam/ozurdexhcp/pdf/US-OZU-230018_021105_OZX-Tech-FAQ_HR.pdf, https://hcp.ozurdex.com/content/dam/ozurdexhcp/pdf/US-OZU-230017_021104_OZX-Uveitis-Patient-Brochure_HR.pdf | 12 |
| tpl_1 | HCP Homepage | Landing page for healthcare professionals on Ozurdex. | https://hcp.ozurdex.com/ | 1 |
| tpl_2 | HCP Resources | Resources and materials for healthcare professionals regarding Ozurdex. | https://hcp.ozurdex.com/resources | 1 |
| tpl_3 | HCP Reimbursement | Reimbursement information for Ozurdex for healthcare professionals. | https://hcp.ozurdex.com/reimbursement-support | 1 |
| tpl_4 | HCP Mechanism of Action | Explanation of how Ozurdex works for healthcare professionals. | https://hcp.ozurdex.com/mechanism-of-action | 1 |
| tpl_5 | HCP Clinical Efficacy | Details on the clinical efficacy of Ozurdex for healthcare professionals. | https://hcp.ozurdex.com/clinical-efficacy | 1 |
| tpl_6 | HCP Sitemap | Sitemap for healthcare professional pages related to Ozurdex. | https://hcp.ozurdex.com/sitemap | 1 |
| tpl_7 | HCP About Ozurdex | Information about Ozurdex for healthcare professionals. | https://hcp.ozurdex.com/about-ozurdex | 1 |
