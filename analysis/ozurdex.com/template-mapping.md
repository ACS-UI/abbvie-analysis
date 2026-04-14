# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **17** URLs; **9** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **PDF Document Page**, **Homepage**, **How It Works Page**. **41** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:41:03.230Z
- **Website**: https://www.ozurdex.com/
- **Total Pages Analyzed**: 17
- **Total Templates Identified**: 9
- **Total Components Identified**: 41
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.OZURDEX.COM TEMPLATES                                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ PDF Document Page                    │    │ Homepage                             │    │ How It Works Page                    │
│ (8 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • —                                  │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • —                                  │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section                       │    │ • Hero Section                       │
│ • —                                  │    │ • Image and Text Section 1 {Unmappe… │    │ • How It Works Section {Unmapped}    │
│ • —                                  │    │ • (+4 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ About Condition Page                 │    │ Site Navigation Page                 │    │ Warning Page                         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │    │ • Headline Section {Unmapped}        │
│ • Primary Navigation {Unmapped}      │    │ • Main Navigation {Unmapped}         │    │ • CTA Columns {Unmapped}             │
│ • Hero Banner                        │    │ • Logo Header {Unmapped}             │    │ • —                                  │
│ • Condition Impact {Unmapped}        │    │ • Mobile Navigation Toggle {Unmappe… │    │ • —                                  │
│ • (+5 more — see Blocks mapped per … │    │ • Banner Navigation {Unmapped}       │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.OZURDEX.COM — SUB-TEMPLATES TEMPLATES                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Search Results Page                  │    │ Cookies Settings Page                │    │ What to Expect Page                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Page Title {Unmapped}              │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Privacy Preference Center {Unmapp… │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Manage Consent Preferences {Unmap… │    │ • Hero Section                       │
│ • Search Results                     │    │ • Required Cookies Accordion {Unmap… │    │ • Content Columns                    │
│ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### PDF Document Page (`tpl_0`) — 8 pages

- —

### Homepage (`tpl_1`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Image and Text Section 1 {Unmapped}
- Image and Text Section 2 {Unmapped}
- Image and Text Section 3 {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### How It Works Page (`tpl_2`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- How It Works Section {Unmapped}
- Ozurdex Implant Section {Unmapped}
- What Does Ozurdex Do Section {Unmapped}
- Macula Comparison Section {Unmapped}
- Video Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### About Condition Page (`tpl_3`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Banner
- Condition Impact {Unmapped}
- Visual Acuity {Unmapped}
- Symptoms {Unmapped}
- DME Information {Unmapped}
- RVO Information {Unmapped}
- Footer

### Site Navigation Page (`tpl_4`) — 1 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Logo Header {Unmapped}
- Mobile Navigation Toggle {Unmapped}
- Banner Navigation {Unmapped}

### Warning Page (`tpl_5`) — 1 pages

- Headline Section {Unmapped}
- CTA Columns {Unmapped}

### Search Results Page (`tpl_6`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Search Results
- Safety Information {Unmapped}
- Footer Links
- Back to Top Button {Unmapped}
- Cookie Settings Modal {Unmapped}

### Cookies Settings Page (`tpl_7`) — 1 pages

- Page Title {Unmapped}
- Privacy Preference Center {Unmapped}
- Manage Consent Preferences {Unmapped}
- Required Cookies Accordion {Unmapped}
- Functional Cookies Accordion {Unmapped}
- Advertising Cookies Accordion {Unmapped}
- Confirm Choices CTA {Unmapped}
- Powered by OneTrust {Unmapped}

### What to Expect Page (`tpl_8`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Columns
- Before Procedure {Unmapped}
- During Procedure {Unmapped}
- After Procedure {Unmapped}
- Safety Information {Unmapped}
- Footer Links
- Back to Top {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Primary Navigation {Unmapped}           │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Utility Navigation {Unmapped}           │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │ ✅   │
│ Hero Section                            │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Footer                                  │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Footer Links                            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Important Safety Information {Unmapped} │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Safety Information {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T9 omitted from matrix width; see appendix.*


### Template-specific components

```
┌──────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Advertising Cookies Accordion {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ After Procedure {Unmapped}               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Back to Top {Unmapped}                   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Back to Top Button {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Banner Navigation {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Before Procedure {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Condition Impact {Unmapped}              │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Confirm Choices CTA {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Columns                          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Cookie Settings Modal {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ CTA Columns {Unmapped}                   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ DME Information {Unmapped}               │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ During Procedure {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Functional Cookies Accordion {Unmapped}  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T9 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • PDF Document Page (8 pgs)                                                                         │
│ • Homepage (1 pgs)                                                                                  │
│ • How It Works Page (1 pgs)                                                                         │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • About Condition Page (1 pgs)                                                                      │
│ • Site Navigation Page (1 pgs)                                                                      │
│ • Warning Page (1 pgs)                                                                              │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Search Results Page (1 pgs)                                                                       │
│ • Cookies Settings Page (1 pgs)                                                                     │
│ • What to Expect Page (1 pgs)                                                                       │
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
| tpl_0 | PDF Document Page | This template represents pages for viewing or downloading PDF documents. | https://www.ozurdex.com/content/dam/ozurdex/pdf/DME_Patient_Brochure.pdf, https://www.ozurdex.com/content/dam/ozurdex/pdf/RVO_Patient_Brochure.pdf, https://www.ozurdex.com/content/dam/ozurdex/pdf/US-OZU-230013_021100_OZX%20DME%20Patient%20Slim%20Jim_HR.pdf | 8 |
| tpl_1 | Homepage | This template represents the main entry point of the website. | https://www.ozurdex.com/ | 1 |
| tpl_2 | How It Works Page | This template represents pages explaining the functionality or process of a service. | https://www.ozurdex.com/howitworks | 1 |
| tpl_3 | About Condition Page | This template represents pages providing information about specific conditions. | https://www.ozurdex.com/aboutyourcondition | 1 |
| tpl_4 | Site Navigation Page | This template represents pages providing navigation options for the website. | https://www.ozurdex.com/header-site-nav | 1 |
| tpl_5 | Warning Page | This template represents pages displaying warnings or alerts. | https://www.ozurdex.com/warn-on-leave | 1 |
| tpl_6 | Search Results Page | This template represents pages displaying search results. | https://www.ozurdex.com/search-results | 1 |
| tpl_7 | Cookies Settings Page | This template represents pages for managing cookie preferences. | https://www.ozurdex.com/cookies-settings | 1 |
| tpl_8 | What to Expect Page | This template represents pages outlining expectations or guidelines. | https://www.ozurdex.com/whattoexpect | 1 |
