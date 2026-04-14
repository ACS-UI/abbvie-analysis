# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **53** URLs; **17** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **PDF Document**, **Informational Page**, **Site Map**. **63** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:01:05.424Z
- **Website**: https://www.hsdiseasesource.com/
- **Total Pages Analyzed**: 53
- **Total Templates Identified**: 17
- **Total Components Identified**: 63
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.HSDISEASESOURCE.COM TEMPLATES                                            │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ PDF Document                         │    │ Informational Page                   │    │ Site Map                             │
│ (6 pages)                            │    │ (3 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • —                                  │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Navigation {Unmapp… │
│ • —                                  │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section                       │    │ • Hero Section                       │
│ • —                                  │    │ • Breadcrumb Navigation {Unmapped}   │    │ • Sitemap Columns {Unmapped}         │
│ • —                                  │    │ • (+6 more — see Blocks mapped per … │    │ • Footer Section                     │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Home Page                            │    │ Search Results                       │    │ Specialist Locator                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Header                     │    │ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │
│ • Mega Navigation                    │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Search Results                     │    │ • Hero Section                       │
│ • (+6 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+7 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Diagnosis Criteria                   │    │ Customization Page                   │    │ Events Page                          │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Header {Unmapped}          │    │ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │
│ • Mega Navigation {Unmapped}         │    │ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • Hero Section                       │    │ • What is HS Section {Unmapped}      │    │ • Breadcrumb Navigation {Unmapped}   │
│ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Resources Page                       │    │ Treatment Options                    │    │ Care Team Overview                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Utility Navigation                 │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Header {Unmapped}          │    │ • Primary Navigation                 │    │ • Primary Header {Unmapped}          │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Mega Navigation {Unmapped}         │
│ • Breadcrumb Navigation {Unmapped}   │    │ • Breadcrumb Navigation {Unmapped}   │    │ • Hero Section                       │
│ • (+6 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.HSDISEASESOURCE.COM — SUB-TEMPLATES TEMPLATES                            │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Symptoms Page                        │    │ Disease Progression                  │    │ Differential Diagnosis               │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Primary Navigation Menu {Unmapped} │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Hero Section {Unmapped}            │    │ • Breadcrumb Navigation {Unmapped}   │    │ • Breadcrumb Navigation {Unmapped}   │
│ • (+8 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Disease Staging                      │    │ Case Studies                         │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │
│ • Breadcrumb Navigation {Unmapped}   │    │ • Breadcrumb Navigation {Unmapped}   │
│ • (+5 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### PDF Document (`tpl_0`) — 6 pages

- —

### Informational Page (`tpl_1`) — 3 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Breadcrumb Navigation {Unmapped}
- Comorbidity Overview {Unmapped}
- Comorbidity Cards
- Callout Section {Unmapped}
- Did You Know Section {Unmapped}
- CTA Section {Unmapped}
- References Section {Unmapped}

### Site Map (`tpl_2`) — 2 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Sitemap Columns {Unmapped}
- Footer Section

### Home Page (`tpl_3`) — 1 pages

- Utility Navigation
- Primary Header
- Mega Navigation
- Hero Section
- Informational Section {Unmapped}
- Interactive Guide {Unmapped}
- Treatment Explorer {Unmapped}
- Image Gallery
- Affected Areas Info {Unmapped}
- Footer

### Search Results (`tpl_4`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Search Results
- Footer
- Back to Top Button {Unmapped}
- Modal Dialogs

### Specialist Locator (`tpl_5`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Breadcrumb Navigation {Unmapped}
- Specialist Introduction {Unmapped}
- Locator Tool {Unmapped}
- Locator Results {Unmapped}
- Reference Section {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### Diagnosis Criteria (`tpl_6`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Mega Navigation {Unmapped}
- Hero Section
- Breadcrumb Navigation {Unmapped}
- Main Content Introduction {Unmapped}
- Additional Considerations {Unmapped}
- Footer Section

### Customization Page (`tpl_7`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Hero Section {Unmapped}
- What is HS Section {Unmapped}
- Information Tree Section {Unmapped}
- Image Spread Section {Unmapped}
- Where HS Occurs Section {Unmapped}
- Footer Section {Unmapped}

### Events Page (`tpl_8`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Breadcrumb Navigation {Unmapped}
- Events Section {Unmapped}
- Organizations Section {Unmapped}
- Resources Call-to-Action {Unmapped}
- Footer

### Resources Page (`tpl_9`) — 1 pages

- Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Breadcrumb Navigation {Unmapped}
- Introduction Text {Unmapped}
- Practice Resources {Unmapped}
- Patient Resources {Unmapped}
- Conversation Guides {Unmapped}
- Additional Resources {Unmapped}
- Footer Links

### Treatment Options (`tpl_10`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Breadcrumb Navigation {Unmapped}
- Content Columns
- Info Tree Interaction {Unmapped}
- Call to Action Section {Unmapped}
- Footer Section

### Care Team Overview (`tpl_11`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Mega Navigation {Unmapped}
- Hero Section
- Breadcrumb Navigation {Unmapped}
- Main Content Columns
- Role of Care Team Members {Unmapped}
- Call-to-Action Section {Unmapped}
- References Section {Unmapped}
- Footer

### Symptoms Page (`tpl_12`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Primary Navigation Menu {Unmapped}
- Hero Section {Unmapped}
- Breadcrumb Navigation {Unmapped}
- Clinical Presentation Section {Unmapped}
- Main Page Callout {Unmapped}
- Hotspot Tool {Unmapped}
- Impact Statistics {Unmapped}
- Psychosocial Impact Section {Unmapped}
- Quote Section {Unmapped}
- HS Diagnosis Quiz CTA {Unmapped}

### Disease Progression (`tpl_13`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Breadcrumb Navigation {Unmapped}
- Main Content Columns
- Callout Section {Unmapped}
- Interactive Info Tree {Unmapped}
- Tabs Component
- Footer Section

### Differential Diagnosis (`tpl_14`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Breadcrumb Navigation {Unmapped}
- Importance of Early Diagnosis {Unmapped}
- HS Diagnosis Statistics {Unmapped}
- Differential Diagnoses {Unmapped}
- Diagnosis Quiz {Unmapped}

### Disease Staging (`tpl_15`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Breadcrumb Navigation {Unmapped}
- Hurley Staging Introduction {Unmapped}
- Hurley Staging Details {Unmapped}
- Severity Considerations {Unmapped}
- Case Studies CTA {Unmapped}
- Footer Links

### Case Studies (`tpl_16`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Hero Section {Unmapped}
- Breadcrumb Navigation {Unmapped}
- Case Study 1 {Unmapped}
- Case Study 2 {Unmapped}
- Case Study 3 {Unmapped}
- Call-to-Action Section {Unmapped}
- References Section {Unmapped}
- Footer


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                         │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Breadcrumb Navigation {Unmapped}     │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Primary Navigation {Unmapped}        │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Primary Header {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Footer                               │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Global Utility Navigation {Unmapped} │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Global Utility Strip {Unmapped}      │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Footer Section                       │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Hero Section {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ References Section {Unmapped}        │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Back to Top Button {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Call-to-Action Section {Unmapped}    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Callout Section {Unmapped}           │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Links                         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T17 omitted from matrix width; see appendix.*


### Template-specific components

```
┌──────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Additional Considerations {Unmapped}     │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Additional Resources {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Affected Areas Info {Unmapped}           │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Call to Action Section {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Case Studies CTA {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Case Study 1 {Unmapped}                  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Case Study 2 {Unmapped}                  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Case Study 3 {Unmapped}                  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Clinical Presentation Section {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Comorbidity Cards                        │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Comorbidity Overview {Unmapped}          │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Columns                          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Conversation Guides {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ CTA Section {Unmapped}                   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T17 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • PDF Document (6 pgs)                                                                              │
│ • Informational Page (3 pgs)                                                                        │
│ • Site Map (2 pgs)                                                                                  │
│ • Home Page (1 pgs)                                                                                 │
│ • Search Results (1 pgs)                                                                            │
│ • Specialist Locator (1 pgs)                                                                        │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Diagnosis Criteria (1 pgs)                                                                        │
│ • Customization Page (1 pgs)                                                                        │
│ • Events Page (1 pgs)                                                                               │
│ • Resources Page (1 pgs)                                                                            │
│ • Treatment Options (1 pgs)                                                                         │
│ • Care Team Overview (1 pgs)                                                                        │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Symptoms Page (1 pgs)                                                                             │
│ • Disease Progression (1 pgs)                                                                       │
│ • Differential Diagnosis (1 pgs)                                                                    │
│ • Disease Staging (1 pgs)                                                                           │
│ • Case Studies (1 pgs)                                                                              │
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
| tpl_0 | PDF Document | Contains downloadable PDF resources. | https://www.hsdiseasesource.com/content/dam/hsdiseasesource/pdf/discussion-guides/HS_DA_Digital_FAQ_Tear_Sheet.pdf, https://www.hsdiseasesource.com/content/dam/hsdiseasesource/pdf/discussion-guides/ConversationGuide_DownloadPDF_FF.pdf, https://www.hsdiseasesource.com/content/dam/hsdiseasesource/pdf/discussion-guides/ConversationGuide_DownloadPDF_Spouse.pdf | 6 |
| tpl_1 | Informational Page | Provides general information on various topics. | https://www.hsdiseasesource.com/hs-comorbidities, https://www.hsdiseasesource.com/hs-causes, https://www.hsdiseasesource.com/what-is-hs | 3 |
| tpl_2 | Site Map | Overview of website structure and navigation. | https://www.hsdiseasesource.com/sitemap, https://www.hsdiseasesource.com/site-map | 2 |
| tpl_3 | Home Page | Main landing page of the website. | https://www.hsdiseasesource.com/ | 1 |
| tpl_4 | Search Results | Displays outcomes of user searches. | https://www.hsdiseasesource.com/search-results | 1 |
| tpl_5 | Specialist Locator | Helps users find medical specialists. | https://www.hsdiseasesource.com/locate-an-hs-specialist | 1 |
| tpl_6 | Diagnosis Criteria | Outlines criteria for diagnosing conditions. | https://www.hsdiseasesource.com/hs-diagnosis-criteria | 1 |
| tpl_7 | Customization Page | Allows users to customize their experience. | https://www.hsdiseasesource.com/personalization | 1 |
| tpl_8 | Events Page | Lists upcoming events and activities. | https://www.hsdiseasesource.com/events-and-organizations | 1 |
| tpl_9 | Resources Page | Offers links and materials for further learning. | https://www.hsdiseasesource.com/resources | 1 |
| tpl_10 | Treatment Options | Explores available treatments and therapies. | https://www.hsdiseasesource.com/hs-treatment-options | 1 |
| tpl_11 | Care Team Overview | Provides information about the healthcare team involved. | https://www.hsdiseasesource.com/multi-disciplinary-care-team | 1 |
| tpl_12 | Symptoms Page | Lists symptoms associated with conditions. | https://www.hsdiseasesource.com/hs-signs-and-symptoms | 1 |
| tpl_13 | Disease Progression | Describes the stages of disease development. | https://www.hsdiseasesource.com/hs-progression | 1 |
| tpl_14 | Differential Diagnosis | Compares and contrasts similar diagnoses. | https://www.hsdiseasesource.com/hs-differential-diagnosis | 1 |
| tpl_15 | Disease Staging | Details the classification of disease stages. | https://www.hsdiseasesource.com/hs-disease-staging | 1 |
| tpl_16 | Case Studies | Showcases detailed examples or scenarios. | https://www.hsdiseasesource.com/hs-case-studies | 1 |
