# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **41** URLs; **14** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Story Pages**, **Treatment Pages**, **Disease Info**. **40** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:12:02.429Z
- **Website**: https://www.ra.com/
- **Total Pages Analyzed**: 41
- **Total Templates Identified**: 14
- **Total Components Identified**: 40
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.RA.COM TEMPLATES                                                         │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Story Pages                          │    │ Treatment Pages                      │    │ Disease Info                         │
│ (15 pages)                           │    │ (4 pages)                            │    │ (3 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Breadcrumb Navigation {Unmapped}   │
│ • Breadcrumb Navigation {Unmapped}   │    │ • Call-to-Action Section {Unmapped}  │    │ • Hero Section {Unmapped}            │
│ • (+6 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Personalization Page                 │    │ Document PDF Page                    │    │ Survey Page                          │
│ (3 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • —                                  │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • —                                  │    │ • Primary Header {Unmapped}          │
│ • Breadcrumb Navigation {Unmapped}   │    │ • —                                  │    │ • Breadcrumb Navigation {Unmapped}   │
│ • Hero Section                       │    │ • —                                  │    │ • Hero Section {Unmapped}            │
│ • (+3 more — see Blocks mapped per … │    │ • —                                  │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Generic Information Page             │    │ Partnering Information Page          │    │ Subscription Pages                   │
│ (2 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Rich Text Content {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Navigation {Unmapp… │
│ • —                                  │    │ • Primary Header {Unmapped}          │    │ • Main Navigation {Unmapped}         │
│ • —                                  │    │ • Breadcrumb Navigation {Unmapped}   │    │ • Hero Section                       │
│ • —                                  │    │ • Hero Section                       │    │ • Subscription Form                  │
│ • —                                  │    │ • (+6 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Resources Pages                      │
│ (2 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │
│ • Breadcrumb Navigation {Unmapped}   │
│ • Hero Section {Unmapped}            │
│ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.RA.COM — SUB-TEMPLATES TEMPLATES                                         │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage                             │    │ Find a Rheumatologist                │    │ Search Results Page                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Breadcrumb Navigation {Unmapped}   │    │ • Breadcrumb Navigation {Unmapped}   │
│ • Footer                             │    │ • Hero Section                       │    │ • Search Results                     │
│ • —                                  │    │ • (+2 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Site Map                             │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Global Utility Navigation          │
│ • Primary Navigation                 │
│ • Breadcrumb Navigation {Unmapped}   │
│ • Main Content Area {Unmapped}       │
│ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Story Pages (`tpl_0`) — 15 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Breadcrumb Navigation {Unmapped}
- Main Content Columns {Unmapped}
- Video Player
- Rich Text Content {Unmapped}
- Recommended Topics {Unmapped}
- Footer Links
- Social Media Links {Unmapped}

### Treatment Pages (`tpl_1`) — 4 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Section {Unmapped}
- Content Columns {Unmapped}
- Video Section
- Quote Section
- Poll Section {Unmapped}
- Footer

### Disease Info (`tpl_2`) — 3 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Breadcrumb Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Content Columns {Unmapped}
- Disease Activity Levels {Unmapped}
- Quick Poll {Unmapped}
- Call-to-Action Section {Unmapped}
- Video Section {Unmapped}
- Footer {Unmapped}

### Personalization Page (`tpl_3`) — 3 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Breadcrumb Navigation {Unmapped}
- Hero Section
- Personalization Columns
- Content Section {Unmapped}
- Footer

### Document PDF Page (`tpl_4`) — 2 pages

- —

### Survey Page (`tpl_5`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Breadcrumb Navigation {Unmapped}
- Hero Section {Unmapped}
- What is RAPID3 {Unmapped}
- Call to Action Section {Unmapped}
- Survey Form {Unmapped}
- Footer Links {Unmapped}
- Back to Top Button {Unmapped}

### Generic Information Page (`tpl_6`) — 2 pages

- Rich Text Content {Unmapped}

### Partnering Information Page (`tpl_7`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Breadcrumb Navigation {Unmapped}
- Hero Section
- Video Section
- CTA Section {Unmapped}
- Survey Section {Unmapped}
- Check-In Section {Unmapped}
- Next Page CTA {Unmapped}
- Footer Links

### Subscription Pages (`tpl_8`) — 2 pages

- Global Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Hero Section
- Subscription Form
- Call to Action Section {Unmapped}
- Footer Links
- Back to Top Button {Unmapped}

### Resources Pages (`tpl_9`) — 2 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Breadcrumb Navigation {Unmapped}
- Hero Section {Unmapped}
- Video Section
- Call-to-Action Section {Unmapped}
- Resources Section {Unmapped}
- Poll Section {Unmapped}
- Support Groups Section {Unmapped}
- Footer

### Homepage (`tpl_10`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Footer

### Find a Rheumatologist (`tpl_11`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Breadcrumb Navigation {Unmapped}
- Hero Section
- Main Content Columns {Unmapped}
- Doctor Locator {Unmapped}

### Search Results Page (`tpl_12`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Breadcrumb Navigation {Unmapped}
- Search Results
- Call to Action Section {Unmapped}
- Footer Links {Unmapped}
- Back to Top Button {Unmapped}
- Modal Dialogs {Unmapped}

### Site Map (`tpl_13`) — 1 pages

- Global Utility Navigation
- Primary Navigation
- Breadcrumb Navigation {Unmapped}
- Main Content Area {Unmapped}
- Sitemap Columns
- Footer Links
- Footer Legal Text


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Breadcrumb Navigation {Unmapped}     │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │ ❌   │
│ Primary Navigation {Unmapped}        │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Hero Section                         │ ✅   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Footer                               │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Footer Links                         │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global Utility Navigation {Unmapped} │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Utility Navigation {Unmapped}        │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Back to Top Button {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Call to Action Section {Unmapped}    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Call-to-Action Section {Unmapped}    │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global Utility Strip {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Hero Section {Unmapped}              │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Main Content Columns {Unmapped}      │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Video Section                        │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T14 omitted from matrix width; see appendix.*


### Template-specific components

```
┌────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                          │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Check-In Section {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Columns {Unmapped}         │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Section {Unmapped}         │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ CTA Section {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Disease Activity Levels {Unmapped} │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Doctor Locator {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer {Unmapped}                  │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Legal Text                  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global Utility Navigation          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Main Content Area {Unmapped}       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Main Navigation {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Modal Dialogs {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Next Page CTA {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Personalization Columns            │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
└────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T14 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Story Pages (15 pgs)                                                                              │
│ • Treatment Pages (4 pgs)                                                                           │
│ • Disease Info (3 pgs)                                                                              │
│ • Personalization Page (3 pgs)                                                                      │
│ • Document PDF Page (2 pgs)                                                                         │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Survey Page (2 pgs)                                                                               │
│ • Generic Information Page (2 pgs)                                                                  │
│ • Partnering Information Page (2 pgs)                                                               │
│ • Subscription Pages (2 pgs)                                                                        │
│ • Resources Pages (2 pgs)                                                                           │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage (1 pgs)                                                                                  │
│ • Find a Rheumatologist (1 pgs)                                                                     │
│ • Search Results Page (1 pgs)                                                                       │
│ • Site Map (1 pgs)                                                                                  │
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
| tpl_0 | Story Pages | Details and transcripts of stories shared on the platform. | https://www.ra.com/rheumatoid-arthritis-resources/patient-stories/convo-with-rheum-transcript, https://www.ra.com/rheumatoid-arthritis-resources/patient-stories/looking-back-transcript, https://www.ra.com/rheumatoid-arthritis-resources/patient-stories/ra-remission-transcript | 15 |
| tpl_1 | Treatment Pages | Information on treatment goals, options, and overviews. | https://www.ra.com/rheumatoid-arthritis-treatment/ra-treatments-explained, https://www.ra.com/rheumatoid-arthritis-treatment/remission, https://www.ra.com/rheumatoid-arthritis-treatment | 4 |
| tpl_2 | Disease Info | Template group "disease_info" from agent grouping (no merge metadata). | https://www.ra.com/what-is-rheumatoid-arthritis/symptoms, https://www.ra.com/what-is-rheumatoid-arthritis/about-ra, https://www.ra.com/what-is-rheumatoid-arthritis | 3 |
| tpl_3 | Personalization Page | Allows users to customize their experience. | https://www.ra.com/personalization-activation, https://www.ra.com/personalization-realization, https://www.ra.com/personalization-motivation | 3 |
| tpl_4 | Document PDF Page | Hosts downloadable PDF documents. | https://www.ra.com/content/dam/ra/documents/Joint_Profiler.pdf, https://www.ra.com/content/dam/ra/documents/RAPID3_Calculation.pdf | 2 |
| tpl_5 | Survey Page | Collects user feedback through surveys. | https://www.ra.com/rheumatoid-arthritis-resources/rapid3-survey, https://www.ra.com/rheumatoid-arthritis-resources/ra-check-in | 2 |
| tpl_6 | Generic Information Page | Provides general information across various topics. | https://www.ra.com/global-isi/use-stmt-generic, https://www.ra.com/global-isi | 2 |
| tpl_7 | Partnering Information Page | Details opportunities and information for partnerships. | https://www.ra.com/rheumatoid-arthritis-resources/partner-with-rheumatologist, https://www.ra.com/rheumatoid-arthritis-treatment/partner-with-rheumatologist | 2 |
| tpl_8 | Subscription Pages | Handles subscription confirmations and user subscriptions. | https://www.ra.com/subscribe, https://www.ra.com/subscribe/confirmation | 2 |
| tpl_9 | Resources Pages | Provides access to various support and informational resources. | https://www.ra.com/rheumatoid-arthritis-resources/ra-support, https://www.ra.com/rheumatoid-arthritis-resources | 2 |
| tpl_10 | Homepage | The main landing page of the website. | https://www.ra.com/ | 1 |
| tpl_11 | Find a Rheumatologist | Assists users in locating rheumatology specialists. | https://www.ra.com/rheumatoid-arthritis-resources/find-a-rheumatologist | 1 |
| tpl_12 | Search Results Page | Displays results for user search queries. | https://www.ra.com/search-results | 1 |
| tpl_13 | Site Map | Provides a structured overview of the website's sections. | https://www.ra.com/sitemap | 1 |
