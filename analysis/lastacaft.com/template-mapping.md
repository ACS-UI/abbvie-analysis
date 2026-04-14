# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **8** URLs; **8** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Homepage**, **FAQ Page**, **Informational Page**. **46** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:21:59.148Z
- **Website**: https://www.lastacaft.com/
- **Total Pages Analyzed**: 8
- **Total Templates Identified**: 8
- **Total Components Identified**: 46
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.LASTACAFT.COM TEMPLATES                                                  │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage                             │    │ FAQ Page                             │    │ Informational Page                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Image Grid CTAs {Unmapped}         │    │ • FAQ Accordion                      │    │ • Introduction Text {Unmapped}       │
│ • (+6 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │    │ • (+11 more — see Blocks mapped per… │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ About Page                           │    │ Healthcare Provider Page             │    │ Store Locator Page                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │    │ • Hero Section                       │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │    │ • Introduction Text {Unmapped}       │
│ • Content Columns {Unmapped}         │    │ • About Section {Unmapped}           │    │ • Retailer Grid {Unmapped}           │
│ • (+7 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.LASTACAFT.COM — SUB-TEMPLATES TEMPLATES                                  │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Coupon Page                          │    │ Sitemap Page                         │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Header                     │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │
│ • Coupon Call to Action {Unmapped}   │    │ • Sitemap Links {Unmapped}           │
│ • (+5 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Homepage (`tpl_0`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section {Unmapped}
- Image Grid CTAs {Unmapped}
- Why Choose Section {Unmapped}
- Testimonials Carousel {Unmapped}
- Savings Section {Unmapped}
- FAQs Section {Unmapped}
- Footer Section {Unmapped}
- Back to Top Button {Unmapped}

### FAQ Page (`tpl_1`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- FAQ Accordion
- Still Have Questions Section {Unmapped}
- Footer

### Informational Page (`tpl_2`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Text {Unmapped}
- Allergens Overview {Unmapped}
- Pollen Details {Unmapped}
- Grass Details {Unmapped}
- Ragweed Details {Unmapped}
- Pet Dander Details {Unmapped}
- Tips Section {Unmapped}
- Mobile Tips Section {Unmapped}
- Pollen Tracker {Unmapped}
- Offer Section {Unmapped}
- Footer Section {Unmapped}
- Back to Top Button {Unmapped}

### About Page (`tpl_3`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Columns {Unmapped}
- Video Player {Unmapped}
- Call-to-Action Buttons {Unmapped}
- Why Choose Section {Unmapped}
- How It Works {Unmapped}
- Social Media Links {Unmapped}
- Footer Navigation {Unmapped}
- Back to Top Button {Unmapped}

### Healthcare Provider Page (`tpl_4`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- About Section {Unmapped}
- Features Columns
- CTA Section {Unmapped}
- FAQ Section {Unmapped}
- Social Media Links {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### Store Locator Page (`tpl_5`) — 1 pages

- Utility Navigation {Unmapped}
- Hero Section
- Introduction Text {Unmapped}
- Retailer Grid {Unmapped}
- Coupon Section {Unmapped}
- Social Links {Unmapped}
- Back to Top Button {Unmapped}

### Coupon Page (`tpl_6`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Header
- Hero Section
- Coupon Call to Action {Unmapped}
- Form Section
- Footer Section
- Social Media Links {Unmapped}
- Back to Top Button {Unmapped}
- Modal Component

### Sitemap Page (`tpl_7`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Sitemap Links {Unmapped}
- Footer Links {Unmapped}
- Footer Legal Information {Unmapped}
- Social Media Links {Unmapped}
- Back to Top Button {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Back to Top Button {Unmapped}        │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Global Utility Navigation {Unmapped} │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Hero Section                         │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │
│ Primary Navigation {Unmapped}        │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Social Media Links {Unmapped}        │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │
│ Hero Section {Unmapped}              │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Utility Navigation {Unmapped}        │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Footer                               │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Footer Section {Unmapped}            │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Introduction Text {Unmapped}         │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Primary Header {Unmapped}            │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Why Choose Section {Unmapped}        │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


### Template-specific components

```
┌─────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                           │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ About Section {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Allergens Overview {Unmapped}       │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Buttons {Unmapped}   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Content Columns {Unmapped}          │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Coupon Call to Action {Unmapped}    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Coupon Section {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ CTA Section {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ FAQ Accordion                       │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ FAQ Section {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ FAQs Section {Unmapped}             │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Features Columns                    │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Footer Legal Information {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Links {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Navigation {Unmapped}        │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage (1 pgs)                                                                                  │
│ • FAQ Page (1 pgs)                                                                                  │
│ • Informational Page (1 pgs)                                                                        │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • About Page (1 pgs)                                                                                │
│ • Healthcare Provider Page (1 pgs)                                                                  │
│ • Store Locator Page (1 pgs)                                                                        │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Coupon Page (1 pgs)                                                                               │
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
| tpl_0 | Homepage | The main entry point of a website, providing an overview and navigation. | https://www.lastacaft.com/ | 1 |
| tpl_1 | FAQ Page | A page addressing frequently asked questions for user assistance. | https://www.lastacaft.com/frequently-asked-questions | 1 |
| tpl_2 | Informational Page | A page containing detailed information on specific topics or subjects. | https://www.lastacaft.com/understanding-eye-allergies | 1 |
| tpl_3 | About Page | A page providing information about the organization or entity. | https://www.lastacaft.com/about | 1 |
| tpl_4 | Healthcare Provider Page | A page targeted towards healthcare professionals or providers. | https://www.lastacaft.com/doc | 1 |
| tpl_5 | Store Locator Page | A page enabling users to find physical store locations. | https://www.lastacaft.com/where-to-buy | 1 |
| tpl_6 | Coupon Page | A page dedicated to displaying promotional offers or discounts. | https://www.lastacaft.com/savings | 1 |
| tpl_7 | Sitemap Page | A page listing the structure and navigation links of the website. | https://www.lastacaft.com/sitemap | 1 |
