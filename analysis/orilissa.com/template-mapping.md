# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **86** URLs; **8** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Agent Unassigned Page**, **Video Email Page**, **Homepage**. **30** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:45:04.345Z
- **Website**: https://www.orilissa.com/
- **Total Pages Analyzed**: 86
- **Total Templates Identified**: 8
- **Total Components Identified**: 30
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.ORILISSA.COM TEMPLATES                                                   │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Agent Unassigned Page                │    │ Video Email Page                     │    │ Homepage                             │
│ (64 pages)                           │    │ (4 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site Header                        │    │ • Send Mail Tool {Unmapped}          │    │ • Global Utility Navigation {Unmapp… │
│ • Main Content Region {Unmapped}     │    │ • Form Fields                        │    │ • Primary Navigation {Unmapped}      │
│ • Content Columns                    │    │ • Form Buttons {Unmapped}            │    │ • Hero Section                       │
│ • Subscription Form                  │    │ • Captcha Protection {Unmapped}      │    │ • Call-to-Action Cards               │
│ • (+3 more — see Blocks mapped per … │    │ • Loading Feedback {Unmapped}        │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Search Results Page                  │    │ Savings Card Page                    │    │ Find Doctor Page                     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Breadcrumb Navigation {Unmapped}   │
│ • Search Results                     │    │ • Breadcrumbs Navigation {Unmapped}  │    │ • Footer Navigation                  │
│ • (+4 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.ORILISSA.COM — SUB-TEMPLATES TEMPLATES                                   │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Site Map Page                        │    │ Email Resource Page                  │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Email Form                         │
│ • Primary Navigation {Unmapped}      │    │ • Captcha Security {Unmapped}        │
│ • Site Map Links - Home {Unmapped}   │    │ • Form Feedback {Unmapped}           │
│ • Footer Navigation                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Agent Unassigned Page (`tpl_0`) — 64 pages

- Site Header
- Main Content Region {Unmapped}
- Content Columns
- Subscription Form
- Subscription Form
- Subscription Form
- Site Footer

### Video Email Page (`tpl_1`) — 4 pages

- Send Mail Tool {Unmapped}
- Form Fields
- Form Buttons {Unmapped}
- Captcha Protection {Unmapped}
- Loading Feedback {Unmapped}

### Homepage (`tpl_2`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Cards
- Important Safety Information {Unmapped}
- Footer Links

### Search Results Page (`tpl_3`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Search Results
- Safety Information {Unmapped}
- Footer Navigation
- Back to Top {Unmapped}
- Modal Dialogs

### Savings Card Page (`tpl_4`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Breadcrumbs Navigation {Unmapped}
- Savings Card Information {Unmapped}
- Savings Card Form
- Savings Card Image {Unmapped}
- Help Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links

### Find Doctor Page (`tpl_5`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation
- Breadcrumb Navigation {Unmapped}
- Footer Navigation

### Site Map Page (`tpl_6`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Site Map Links - Home {Unmapped}
- Footer Navigation

### Email Resource Page (`tpl_7`) — 1 pages

- Email Form
- Captcha Security {Unmapped}
- Form Feedback {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Primary Navigation {Unmapped}           │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │ ✅   │
│ Footer Navigation                       │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │
│ Global Utility Navigation {Unmapped}    │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ✅   │
│ Hero Section                            │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Footer Links                            │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Important Safety Information {Unmapped} │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Utility Navigation {Unmapped}           │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


### Template-specific components

```
┌─────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                           │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Back to Top {Unmapped}              │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Breadcrumb Navigation {Unmapped}    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Breadcrumbs Navigation {Unmapped}   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Call-to-Action Cards                │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Captcha Protection {Unmapped}       │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Captcha Security {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Columns                     │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Email Form                          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Form Buttons {Unmapped}             │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Form Feedback {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Form Fields                         │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Help Section {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Loading Feedback {Unmapped}         │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Main Content Region {Unmapped}      │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Agent Unassigned Page (64 pgs)                                                                    │
│ • Video Email Page (4 pgs)                                                                          │
│ • Homepage (1 pgs)                                                                                  │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Search Results Page (1 pgs)                                                                       │
│ • Savings Card Page (1 pgs)                                                                         │
│ • Find Doctor Page (1 pgs)                                                                          │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Site Map Page (1 pgs)                                                                             │
│ • Email Resource Page (1 pgs)                                                                       │
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
| tpl_0 | Agent Unassigned Page | Page template for unassigned agent scenarios. | https://www.orilissa.com/insurance-and-savings/co-pay-card, https://www.orilissa.com/insurance-and-savings/coverage, https://www.orilissa.com/insurance-and-savings/orilissa-complete | 64 |
| tpl_1 | Video Email Page | Page template for video email content. | https://www.orilissa.com/emails/video-emails/6122699813001, https://www.orilissa.com/emails/video-emails/6122698946001, https://www.orilissa.com/emails/video-emails/6250706766001 | 4 |
| tpl_2 | Homepage | Main landing page of the site. | https://www.orilissa.com/ | 1 |
| tpl_3 | Search Results Page | Page template for displaying search results. | https://www.orilissa.com/search-results | 1 |
| tpl_4 | Savings Card Page | Page template for savings card information. | https://www.orilissa.com/savings-card | 1 |
| tpl_5 | Find Doctor Page | Page template for locating doctors. | https://www.orilissa.com/find-an-obgyn | 1 |
| tpl_6 | Site Map Page | Page template for site map navigation. | https://www.orilissa.com/site-map | 1 |
| tpl_7 | Email Resource Page | Page template for email resource display. | https://www.orilissa.com/emails/endo-resource | 1 |
