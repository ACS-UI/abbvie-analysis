# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **15** URLs; **10** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **About VUITY Page**, **Presbyopia Information Page**, **Terms and Conditions Page**. **44** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:44:48.227Z
- **Website**: https://www.vuity.com/
- **Total Pages Analyzed**: 15
- **Total Templates Identified**: 10
- **Total Components Identified**: 44
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.VUITY.COM TEMPLATES                                                      │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ About VUITY Page                     │    │ Presbyopia Information Page          │    │ Terms and Conditions Page            │
│ (3 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation                 │    │ • Primary Header {Unmapped}          │    │ • Primary Header {Unmapped}          │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • About VUITY Content                │    │ • Introduction Paragraph {Unmapped}  │    │ • Main Content {Unmapped}            │
│ • (+7 more — see Blocks mapped per … │    │ • (+7 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage                             │    │ FAQ Page                             │    │ Sitemap Page                         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Header                     │    │ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │
│ • Hero Section {Unmapped}            │    │ • Hero Section {Unmapped}            │    │ • Main Navigation {Unmapped}         │
│ • Introductory Text {Unmapped}       │    │ • FAQs Section {Unmapped}            │    │ • Hero Section {Unmapped}            │
│ • (+8 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Doctor Locator Page                  │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │
│ • Introduction Text {Unmapped}       │
│ • (+8 more — see Blocks mapped per … │
└──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.VUITY.COM — SUB-TEMPLATES TEMPLATES                                      │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Cost Information Page                │    │ Email Verification Page              │    │ Error Unreachable Page               │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Header                     │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Banner {Unmapped}             │    │ • Hero Banner {Unmapped}             │
│ • Product Information {Unmapped}     │    │ • Email Verification Message {Unmap… │    │ • Account Sign-In CTA {Unmapped}     │
│ • (+6 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### About VUITY Page (`tpl_0`) — 3 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- About VUITY Content
- Getting Started Section
- How It Works Section
- Results Section
- FAQs Call-to-Action
- Important Safety Information
- Footer Section
- Back to Top Button {Unmapped}

### Presbyopia Information Page (`tpl_1`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Introduction Paragraph {Unmapped}
- Call-to-Action Flexbox {Unmapped}
- Columns Section
- Progression Section {Unmapped}
- Treatment Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links
- Back to Top Button {Unmapped}

### Terms and Conditions Page (`tpl_2`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Main Content {Unmapped}
- Safety Information {Unmapped}
- Footer Links
- Back to Top {Unmapped}

### Homepage (`tpl_3`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header
- Hero Section {Unmapped}
- Introductory Text {Unmapped}
- Columns with CTAs {Unmapped}
- Image Slider {Unmapped}
- Curve Sections {Unmapped}
- Blurry Vision Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer
- Back to Top Button {Unmapped}
- Terms Modal

### FAQ Page (`tpl_4`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- FAQs Section {Unmapped}
- Presbyopia FAQs Accordion
- About VUITY FAQs Accordion
- Efficacy and Safety FAQs Accordion
- How to Use FAQs Accordion
- Footer Section

### Sitemap Page (`tpl_5`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Main Navigation {Unmapped}
- Hero Section {Unmapped}
- Sitemap Links {Unmapped}
- FAQ Call to Action {Unmapped}
- Safety Information {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### Doctor Locator Page (`tpl_6`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Text {Unmapped}
- Columns Section {Unmapped}
- Image Slider {Unmapped}
- Curve Sections {Unmapped}
- Blurry Vision Section {Unmapped}
- Sign-Up Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer
- Back to Top {Unmapped}

### Cost Information Page (`tpl_7`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Product Information {Unmapped}
- Image Comparison Slider {Unmapped}
- Curve Sections {Unmapped}
- Blurry Vision Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### Email Verification Page (`tpl_8`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header
- Hero Banner {Unmapped}
- Email Verification Message {Unmapped}
- Important Safety Information {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### Error Unreachable Page (`tpl_9`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Banner {Unmapped}
- Account Sign-In CTA {Unmapped}
- FAQ CTA {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links
- Back to Top Button {Unmapped}
- Cookie Settings {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Back to Top Button {Unmapped}           │ ✅   │ ✅   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │
│ Utility Navigation {Unmapped}           │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │
│ Important Safety Information {Unmapped} │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Footer                                  │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │
│ Hero Section                            │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Primary Navigation {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │
│ Blurry Vision Section {Unmapped}        │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Curve Sections {Unmapped}               │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Footer Links                            │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Hero Section {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Primary Header {Unmapped}               │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Back to Top {Unmapped}                  │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Footer Section                          │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Hero Banner {Unmapped}                  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T10 omitted from matrix width; see appendix.*


### Template-specific components

```
┌───────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                             │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├───────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ About VUITY Content                   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ About VUITY FAQs Accordion            │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Account Sign-In CTA {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Flexbox {Unmapped}     │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Columns Section                       │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Columns Section {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Columns with CTAs {Unmapped}          │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Cookie Settings {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Efficacy and Safety FAQs Accordion    │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Email Verification Message {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ FAQ Call to Action {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ FAQ CTA {Unmapped}                    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ FAQs Call-to-Action                   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ FAQs Section {Unmapped}               │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
└───────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T10 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • About VUITY Page (3 pgs)                                                                          │
│ • Presbyopia Information Page (2 pgs)                                                               │
│ • Terms and Conditions Page (2 pgs)                                                                 │
│ • Homepage (1 pgs)                                                                                  │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • FAQ Page (1 pgs)                                                                                  │
│ • Sitemap Page (1 pgs)                                                                              │
│ • Doctor Locator Page (1 pgs)                                                                       │
│ • Cost Information Page (1 pgs)                                                                     │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Email Verification Page (1 pgs)                                                                   │
│ • Error Unreachable Page (1 pgs)                                                                    │
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
| tpl_0 | About VUITY Page | Provides information about VUITY. | https://www.vuity.com/about-vuity, https://www.vuity.com/introducing-vuity, https://www.vuity.com/terms-and-conditions | 3 |
| tpl_1 | Presbyopia Information Page | Provides details about presbyopia. | https://www.vuity.com/what-is-presbyopia, https://www.vuity.com/about-presbyopia | 2 |
| tpl_2 | Terms and Conditions Page | Details the terms and conditions. | https://www.vuity.com/termsandconditions, https://www.vuity.com/modals/terms-and-conditions | 2 |
| tpl_3 | Homepage | Main landing page of the website. | https://www.vuity.com/ | 1 |
| tpl_4 | FAQ Page | Answers frequently asked questions. | https://www.vuity.com/frequently-asked-questions | 1 |
| tpl_5 | Sitemap Page | Displays the website's sitemap. | https://www.vuity.com/sitemap | 1 |
| tpl_6 | Doctor Locator Page | Helps users locate doctors. | https://www.vuity.com/find-a-doctor | 1 |
| tpl_7 | Cost Information Page | Details regarding costs and pricing. | https://www.vuity.com/cost | 1 |
| tpl_8 | Email Verification Page | Facilitates email verification process. | https://www.vuity.com/email-verification | 1 |
| tpl_9 | Error Unreachable Page | Displays unreachable error messages. | https://www.vuity.com/your-account-exist | 1 |
