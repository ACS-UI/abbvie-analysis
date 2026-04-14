# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **22** URLs; **14** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Document Library**, **Error Page**, **About Information Page**. **36** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:31:40.457Z
- **Website**: https://www.emrelishcp.com/
- **Total Pages Analyzed**: 22
- **Total Templates Identified**: 14
- **Total Components Identified**: 36
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.EMRELISHCP.COM TEMPLATES                                                 │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Document Library                     │    │ Error Page                           │    │ About Information Page               │
│ (6 pages)                            │    │ (3 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • —                                  │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • —                                  │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • —                                  │    │ • Main Title {Unmapped}              │    │ • About EMRELIS Introduction {Unmap… │
│ • —                                  │    │ • (+3 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage                             │    │ Contact Us Page                      │    │ Safety Profile                       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Header                     │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Call-to-Action Section {Unmapped}  │    │ • Main Content Introduction {Unmapp… │    │ • Main Title {Unmapped}              │
│ • (+2 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Support Resources                    │    │ User Sign-Up Page                    │    │ Search Results Page                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Support Brochures {Unmapped}       │    │ • Important Safety Information {Unm… │    │ • Search Results                     │
│ • (+2 more — see Blocks mapped per … │    │ • References Section {Unmapped}      │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Efficacy Details                     │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │
│ • Efficacy Highlight {Unmapped}      │
│ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.EMRELISHCP.COM — SUB-TEMPLATES TEMPLATES                                 │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Adverse Reaction Guidelines          │    │ Study Design Page                    │    │ Dosing Information                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Dosage Chart {Unmapped}            │    │ • Study Design Overview {Unmapped}   │    │ • Dosing Schedule Section {Unmapped} │
│ • (+3 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Sitemap Page                         │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │
│ • Sitemap Overview {Unmapped}        │
│ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Document Library (`tpl_0`) — 6 pages

- —

### Error Page (`tpl_1`) — 3 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Title {Unmapped}
- Content Accordion
- Image Section {Unmapped}
- Important Safety Information {Unmapped}

### About Information Page (`tpl_2`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- About EMRELIS Introduction {Unmapped}
- Key Features {Unmapped}
- Mechanism of Action {Unmapped}
- Accordion Transcript

### Homepage (`tpl_3`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header
- Hero Section
- Call-to-Action Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### Contact Us Page (`tpl_4`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content Introduction {Unmapped}
- Contact Form
- Safety Information {Unmapped}
- References Section {Unmapped}
- Footer Links

### Safety Profile (`tpl_5`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Title {Unmapped}
- Introductory Prose {Unmapped}
- Detailed Prose {Unmapped}
- Adverse Reaction Chart {Unmapped}
- Adverse Reactions Accordion
- Footer

### Support Resources (`tpl_6`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Support Brochures {Unmapped}
- How to Order {Unmapped}
- Footer

### User Sign-Up Page (`tpl_7`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Important Safety Information {Unmapped}
- References Section {Unmapped}

### Search Results Page (`tpl_8`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Search Results
- Important Safety Information {Unmapped}
- Footer Links

### Efficacy Details (`tpl_9`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Efficacy Highlight {Unmapped}
- Response Duration {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links {Unmapped}

### Adverse Reaction Guidelines (`tpl_10`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Dosage Chart {Unmapped}
- Adverse Reactions Accordion
- Important Safety Information {Unmapped}
- Footer

### Study Design Page (`tpl_11`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Study Design Overview {Unmapped}
- Baseline Characteristics {Unmapped}
- Safety Information {Unmapped}
- References Section {Unmapped}
- Footer Links

### Dosing Information (`tpl_12`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Dosing Schedule Section {Unmapped}
- Important Safety Information {Unmapped}
- References Section {Unmapped}

### Sitemap Page (`tpl_13`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Sitemap Overview {Unmapped}
- Important Safety Info {Unmapped}
- References Section {Unmapped}
- Footer Links


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                            │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Primary Navigation {Unmapped}           │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │
│ Utility Navigation {Unmapped}           │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Important Safety Information {Unmapped} │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ References Section {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Footer                                  │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │
│ Footer Links                            │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Global Utility Navigation {Unmapped}    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Adverse Reactions Accordion             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Main Title {Unmapped}                   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Safety Information {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T14 omitted from matrix width; see appendix.*


### Template-specific components

```
┌───────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                             │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├───────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ About EMRELIS Introduction {Unmapped} │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Accordion Transcript                  │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Adverse Reaction Chart {Unmapped}     │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Baseline Characteristics {Unmapped}   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Section {Unmapped}     │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Contact Form                          │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Content Accordion                     │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Detailed Prose {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Dosage Chart {Unmapped}               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Dosing Schedule Section {Unmapped}    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Efficacy Highlight {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Links {Unmapped}               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global Utility Strip {Unmapped}       │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Hero Section {Unmapped}               │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└───────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T14 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Document Library (6 pgs)                                                                          │
│ • Error Page (3 pgs)                                                                                │
│ • About Information Page (2 pgs)                                                                    │
│ • Homepage (1 pgs)                                                                                  │
│ • Contact Us Page (1 pgs)                                                                           │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Safety Profile (1 pgs)                                                                            │
│ • Support Resources (1 pgs)                                                                         │
│ • User Sign-Up Page (1 pgs)                                                                         │
│ • Search Results Page (1 pgs)                                                                       │
│ • Efficacy Details (1 pgs)                                                                          │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Adverse Reaction Guidelines (1 pgs)                                                               │
│ • Study Design Page (1 pgs)                                                                         │
│ • Dosing Information (1 pgs)                                                                        │
│ • Sitemap Page (1 pgs)                                                                              │
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
| tpl_0 | Document Library | Template for pages hosting collections of documents. | https://www.emrelishcp.com/content/dam/emrelishcp/docs/emr-lomn-template.pdf, https://www.emrelishcp.com/content/dam/emrelishcp/docs/emr-appeals-letter-template.pdf, https://www.emrelishcp.com/content/dam/emrelishcp/docs/emr-branded-patient-brochure.pdf | 6 |
| tpl_1 | Error Page | Template for pages displayed when an unknown error occurs. | https://www.emrelishcp.com/dosing/adverse-reaction-copy, https://www.emrelishcp.com/met-ihc-testing, https://www.emrelishcp.com/efficacy | 3 |
| tpl_2 | About Information Page | Template for pages providing overview and details about the company or product. | https://www.emrelishcp.com/about-emrelis, https://www.emrelishcp.com/about-c-met | 2 |
| tpl_3 | Homepage | Template for the main landing page of the website. | https://www.emrelishcp.com/ | 1 |
| tpl_4 | Contact Us Page | Template for the contact information and inquiry submission page. | https://www.emrelishcp.com/contact-a-rep | 1 |
| tpl_5 | Safety Profile | Template for pages detailing safety information and profiles. | https://www.emrelishcp.com/safety | 1 |
| tpl_6 | Support Resources | Template for pages providing support resources and assistance. | https://www.emrelishcp.com/support#howtoordermetihctesting | 1 |
| tpl_7 | User Sign-Up Page | Template for pages allowing users to sign up for services. | https://www.emrelishcp.com/support/sign-up | 1 |
| tpl_8 | Search Results Page | Template for displaying search results. | https://www.emrelishcp.com/search-results | 1 |
| tpl_9 | Efficacy Details | Template for pages discussing the efficacy of a product or service. | https://www.emrelishcp.com/efficacy/efficacy | 1 |
| tpl_10 | Adverse Reaction Guidelines | Template for pages outlining guidelines for adverse reactions. | https://www.emrelishcp.com/dosing/adverse-reaction | 1 |
| tpl_11 | Study Design Page | Template for pages discussing study designs and methodologies. | https://www.emrelishcp.com/efficacy/study-design | 1 |
| tpl_12 | Dosing Information | Template for pages providing dosing instructions and details. | https://www.emrelishcp.com/dosing | 1 |
| tpl_13 | Sitemap Page | Template for the sitemap of the website. | https://www.emrelishcp.com/sitemap | 1 |
