# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **220** URLs; **17** layout templates were identified (signature (DOM fingerprint)). Highest-traffic templates by page count include **Home and Search Results**, **Patient Assistance Programs**, **Jumpstart 1 — group 12**. **56** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:05:13.561Z
- **Website**: https://www.abbvieeyecare.com/
- **Total Pages Analyzed**: 220
- **Total Templates Identified**: 17
- **Total Components Identified**: 56
- **Grouping**: signature (DOM fingerprint)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.ABBVIEEYECARE.COM TEMPLATES                                              │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Home and Search Results              │    │ Patient Assistance Programs          │    │ Jumpstart 1 — group 12               │
│ (2 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Navigation {Unmapp… │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • CTA Buttons {Unmapped}             │    │ • Patient Assistance Introduction {… │    │ • Program Overview {Unmapped}        │
│ • (+5 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Prescribing Information              │    │ Contact Us                           │    │ Tech Alliance Overview               │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Hero Banner                        │
│ • Page Heading {Unmapped}            │    │ • Contact Us Heading {Unmapped}      │    │ • Mission Statement {Unmapped}       │
│ • Prescribing Information List {Unm… │    │ • (+3 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Patient Savings Resources            │    │ Product Information                  │    │ Patientcareresources — group 8       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Banner                        │    │ • Hero Section                       │
│ • Patient Savings Introduction {Unm… │    │ • Introduction Text {Unmapped}       │    │ • Introduction Columns {Unmapped}    │
│ • (+3 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page Not Found — group 9             │    │ Ecp — group 10                       │    │ System Error — group 11              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Secondary Navigation {Unmapped}    │    │ • Error Content {Unmapped}           │
│ • Error Message {Unmapped}           │    │ • Footer                             │    │ • CTA Banner {Unmapped}              │
│ • (+2 more — see Blocks mapped per … │    │ • —                                  │    │ • Footer Links                       │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.ABBVIEEYECARE.COM — SUB-TEMPLATES TEMPLATES                              │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Office Resources — group 13          │    │ Thank You — group 14                 │    │ Site Map — group 15                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Banner                        │
│ • Resource Links {Unmapped}          │    │ • Thank You Message {Unmapped}       │    │ • Site Map Heading {Unmapped}        │
│ • (+3 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Sitemap — group 16                   │    │ Helpful Links — group 17             │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │
│ • Important Safety Information {Unm… │    │ • Helpful Links {Unmapped}           │
│ • Footer Navigation                  │    │ • Footer                             │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Home and Search Results (`tpl_0`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- CTA Buttons {Unmapped}
- Introductory Text Section {Unmapped}
- Image Highlight {Unmapped}
- Audience CTA {Unmapped}
- Products Carousel {Unmapped}
- Footer Links

### Patient Assistance Programs (`tpl_5`) — 2 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Patient Assistance Introduction {Unmapped}
- Patient Assistance Details {Unmapped}
- Adverse Events Reporting {Unmapped}
- Our Products Carousel

### Jumpstart 1 — group 12 (`tpl_11`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Program Overview {Unmapped}
- Program Benefits {Unmapped}
- Registration Section {Unmapped}
- Products Section
- Footer

### Prescribing Information (`tpl_1`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Page Heading {Unmapped}
- Prescribing Information List {Unmapped}

### Contact Us (`tpl_2`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Contact Us Heading {Unmapped}
- Contact Us Sections {Unmapped}
- Instagram Carousel {Unmapped}
- Footer

### Tech Alliance Overview (`tpl_3`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Banner
- Mission Statement {Unmapped}
- Resources Links {Unmapped}
- Products Heading {Unmapped}
- Products Carousel
- Product Tabs

### Patient Savings Resources (`tpl_4`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Patient Savings Introduction {Unmapped}
- VUITY Savings Program {Unmapped}
- RESTASIS Savings Program {Unmapped}
- At Your Service Savings Program {Unmapped}

### Product Information (`tpl_6`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Banner
- Introduction Text {Unmapped}
- Product Information Section {Unmapped}
- Accordion Product Details
- Footer

### Patientcareresources — group 8 (`tpl_7`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Columns {Unmapped}
- CTA Links {Unmapped}
- Assistance and Savings Section {Unmapped}
- Eye Conditions Grid {Unmapped}
- Products Carousel

### Page Not Found — group 9 (`tpl_8`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Error Message {Unmapped}
- Call-to-Action Button {Unmapped}
- Important Safety Information {Unmapped}

### Ecp — group 10 (`tpl_9`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Secondary Navigation {Unmapped}
- Footer

### System Error — group 11 (`tpl_10`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Error Content {Unmapped}
- CTA Banner {Unmapped}
- Footer Links

### Office Resources — group 13 (`tpl_12`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Resource Links {Unmapped}
- Office Resources Heading {Unmapped}
- Office Resources Tabs {Unmapped}
- Video Section

### Thank You — group 14 (`tpl_13`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Thank You Message {Unmapped}
- Our Products Heading {Unmapped}
- Products Carousel

### Site Map — group 15 (`tpl_14`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Banner
- Site Map Heading {Unmapped}
- Site Map Links {Unmapped}
- Important Safety Information {Unmapped}

### Sitemap — group 16 (`tpl_15`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Important Safety Information {Unmapped}
- Footer Navigation

### Helpful Links — group 17 (`tpl_16`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Helpful Links {Unmapped}
- Footer


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Primary Navigation {Unmapped}           │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Hero Section                            │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Global Utility Navigation {Unmapped}    │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Utility Navigation {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Footer                                  │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Global Utility Strip {Unmapped}         │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Hero Banner                             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Important Safety Information {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Products Carousel                       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Footer Links                            │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T17 omitted from matrix width; see appendix.*


### Template-specific components

```
┌────────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                  │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├────────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Accordion Product Details                  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Adverse Events Reporting {Unmapped}        │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Assistance and Savings Section {Unmapped}  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ At Your Service Savings Program {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Audience CTA {Unmapped}                    │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Button {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Contact Us Heading {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Contact Us Sections {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ CTA Banner {Unmapped}                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ CTA Buttons {Unmapped}                     │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ CTA Links {Unmapped}                       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Error Content {Unmapped}                   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Error Message {Unmapped}                   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Eye Conditions Grid {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└────────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T17 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Home and Search Results (2 pgs)                                                                   │
│ • Patient Assistance Programs (2 pgs)                                                               │
│ • Jumpstart 1 — group 12 (2 pgs)                                                                    │
│ • Prescribing Information (1 pgs)                                                                   │
│ • Contact Us (1 pgs)                                                                                │
│ • Tech Alliance Overview (1 pgs)                                                                    │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Patient Savings Resources (1 pgs)                                                                 │
│ • Product Information (1 pgs)                                                                       │
│ • Patientcareresources — group 8 (1 pgs)                                                            │
│ • Page Not Found — group 9 (1 pgs)                                                                  │
│ • Ecp — group 10 (1 pgs)                                                                            │
│ • System Error — group 11 (1 pgs)                                                                   │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Office Resources — group 13 (1 pgs)                                                               │
│ • Thank You — group 14 (1 pgs)                                                                      │
│ • Site Map — group 15 (1 pgs)                                                                       │
│ • Sitemap — group 16 (1 pgs)                                                                        │
│ • Helpful Links — group 17 (1 pgs)                                                                  │
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
| tpl_0 | Home and Search Results | Main landing and search pages, providing an overview of the site and navigation for users. | https://www.abbvieeyecare.com/, https://www.abbvieeyecare.com/search-results | 2 |
| tpl_1 | Prescribing Information | Detailed resources for healthcare providers regarding prescription medications and their usage. | https://www.abbvieeyecare.com/prescribing-information | 1 |
| tpl_2 | Contact Us | Page containing contact information and support details for various user queries. | https://www.abbvieeyecare.com/contact-us | 1 |
| tpl_3 | Tech Alliance Overview | Overview of the Tech Alliance program, offering resources for eye care providers and office staff. | https://www.abbvieeyecare.com/techalliance | 1 |
| tpl_4 | Patient Savings Resources | Information about savings programs and financial support for patients. | https://www.abbvieeyecare.com/patientcareresources/patient-savings | 1 |
| tpl_5 | Patient Assistance Programs | Details about assistance programs to help patients access necessary medications. | https://www.abbvieeyecare.com/patientcareresources/patient-assistance, https://www.abbvieeyecare.com/patient/patient-assistance | 2 |
| tpl_6 | Product Information | Comprehensive details about products available through AbbVie Eye Care. | https://www.abbvieeyecare.com/product-information | 1 |
| tpl_7 | Patientcareresources — group 8 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvieeyecare.com/patientcareresources | 1 |
| tpl_8 | Page Not Found — group 9 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvieeyecare.com/page-not-found | 1 |
| tpl_9 | Ecp — group 10 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvieeyecare.com/ecp | 1 |
| tpl_10 | System Error — group 11 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvieeyecare.com/system-error | 1 |
| tpl_11 | Jumpstart 1 — group 12 | Same structural layout across 2 page(s) in the crawl. | https://www.abbvieeyecare.com/ecp/jumpstart_1, https://www.abbvieeyecare.com/ecp/jumpstart | 2 |
| tpl_12 | Office Resources — group 13 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvieeyecare.com/techalliance/office-resources | 1 |
| tpl_13 | Thank You — group 14 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvieeyecare.com/ecp/thank-you | 1 |
| tpl_14 | Site Map — group 15 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvieeyecare.com/site-map | 1 |
| tpl_15 | Sitemap — group 16 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvieeyecare.com/sitemap | 1 |
| tpl_16 | Helpful Links — group 17 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvieeyecare.com/techalliance/helpful-links | 1 |
