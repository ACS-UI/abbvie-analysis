# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **15** URLs; **14** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Error Page**, **Homepage**, **Sitemap Page**. **53** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:29:19.004Z
- **Website**: https://www.emblaveo.com/
- **Total Pages Analyzed**: 15
- **Total Templates Identified**: 14
- **Total Components Identified**: 53
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.EMBLAVEO.COM TEMPLATES                                                   │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Error Page                           │    │ Homepage                             │    │ Sitemap Page                         │
│ (2 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │    │ • Hero Section {Unmapped}            │
│ • Main Navigation {Unmapped}         │    │ • Three Column CTA {Unmapped}        │    │ • Sitemap List {Unmapped}            │
│ • (+6 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Video Gallery                        │    │ Content Article                      │    │ Registration Form                    │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │    │ • Primary Header {Unmapped}          │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Video Player                       │    │ • Content Section {Unmapped}         │    │ • Registration Form                  │
│ • (+3 more — see Blocks mapped per … │    │ • (+7 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Clinical Data                        │    │ Testing Information                  │    │ Safety Profile                       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │    │ • Primary Header {Unmapped}          │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Study Design Section {Unmapped}    │    │ • Section Navigation {Unmapped}      │    │ • Adverse Reactions {Unmapped}       │
│ • (+5 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Medical Information                  │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │
│ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │
│ • Inquiry Form {Unmapped}            │
│ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.EMBLAVEO.COM — SUB-TEMPLATES TEMPLATES                                   │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Mechanism of Action                  │    │ Dosing Information                   │    │ Ordering Support                     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • Content Columns                    │    │ • Section Navigation {Unmapped}      │    │ • Ordering Section {Unmapped}        │
│ • (+5 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Customer Support                     │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Utility Navigation                 │
│ • Primary Navigation                 │
│ • Hero Section                       │
│ • Main Content                       │
│ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Error Page (`tpl_0`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Hero Section {Unmapped}
- Main Navigation {Unmapped}
- Contact Form {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links {Unmapped}
- Footer Legal {Unmapped}
- Back to Top Button {Unmapped}
- Modal Dialogs {Unmapped}

### Homepage (`tpl_1`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Three Column CTA {Unmapped}
- Promo Drawer {Unmapped}
- Footer Links
- Footer Legal

### Sitemap Page (`tpl_2`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Sitemap List {Unmapped}
- Select Next Level {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links

### Video Gallery (`tpl_3`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Video Player
- Safety Information {Unmapped}
- Footer Links
- Back to Top Button {Unmapped}

### Content Article (`tpl_4`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Content Section {Unmapped}
- Line Chart
- CRE Section {Unmapped}
- Columns Section
- MBL Section {Unmapped}
- Stenotrophomonas Section {Unmapped}
- References Section {Unmapped}
- Safety Information

### Registration Form (`tpl_5`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Registration Form
- Safety Information {Unmapped}
- Footer Links
- Footer Legal {Unmapped}
- Back to Top {Unmapped}

### Clinical Data (`tpl_6`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Study Design Section {Unmapped}
- Patient Population Section {Unmapped}
- Efficacy Section {Unmapped}
- Call to Action Section {Unmapped}
- Safety Information {Unmapped}
- Footer Links

### Testing Information (`tpl_7`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Section Navigation {Unmapped}
- Diagnostics Table
- MIC Testing Information {Unmapped}
- FDA Breakpoints
- Reference Lab Info {Unmapped}
- Safety Information {Unmapped}
- Footer Links

### Safety Profile (`tpl_8`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Adverse Reactions {Unmapped}
- Information Section {Unmapped}
- Call-to-Action Section {Unmapped}
- Safety Information {Unmapped}
- Footer Links
- Footer Legal {Unmapped}
- Back to Top Button {Unmapped}

### Medical Information (`tpl_9`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Inquiry Form {Unmapped}
- Content Prose {Unmapped}
- Back to Top {Unmapped}
- Warn on Leave Modal {Unmapped}

### Mechanism of Action (`tpl_10`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Content Columns
- Image and Text Section {Unmapped}
- Tree Diagram {Unmapped}
- Important Safety Information {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### Dosing Information (`tpl_11`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Section Navigation {Unmapped}
- Recommended Dosing {Unmapped}
- Dose Adjustments {Unmapped}
- Dosing Adjustments Accordion
- CTA: Download Guide {Unmapped}
- Select Next Level {Unmapped}

### Ordering Support (`tpl_12`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Ordering Section {Unmapped}
- Additional Resources {Unmapped}
- Select Next Level {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links

### Customer Support (`tpl_13`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Main Content
- Important Safety Information
- Footer Links
- Back to Top Button


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                            │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Footer Links                            │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │
│ Primary Navigation {Unmapped}           │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │ ✅   │
│ Safety Information {Unmapped}           │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │
│ Back to Top Button {Unmapped}           │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Global Utility Strip {Unmapped}         │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Hero Section {Unmapped}                 │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Important Safety Information {Unmapped} │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Primary Header {Unmapped}               │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Footer Legal {Unmapped}                 │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Global Utility Navigation {Unmapped}    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Primary Navigation                      │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Select Next Level {Unmapped}            │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Utility Navigation                      │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T14 omitted from matrix width; see appendix.*


### Template-specific components

```
┌───────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                         │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├───────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Additional Resources {Unmapped}   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Adverse Reactions {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Back to Top Button                │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call to Action Section {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Call-to-Action Section {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Columns Section                   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Contact Form {Unmapped}           │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Columns                   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Prose {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Section {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ CRE Section {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ CTA: Download Guide {Unmapped}    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Diagnostics Table                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Dose Adjustments {Unmapped}       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└───────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T14 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Error Page (2 pgs)                                                                                │
│ • Homepage (1 pgs)                                                                                  │
│ • Sitemap Page (1 pgs)                                                                              │
│ • Video Gallery (1 pgs)                                                                             │
│ • Content Article (1 pgs)                                                                           │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Registration Form (1 pgs)                                                                         │
│ • Clinical Data (1 pgs)                                                                             │
│ • Testing Information (1 pgs)                                                                       │
│ • Safety Profile (1 pgs)                                                                            │
│ • Medical Information (1 pgs)                                                                       │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Mechanism of Action (1 pgs)                                                                       │
│ • Dosing Information (1 pgs)                                                                        │
│ • Ordering Support (1 pgs)                                                                          │
│ • Customer Support (1 pgs)                                                                          │
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
| tpl_0 | Error Page | Pages displayed when an error occurs. | https://www.emblaveo.com/contact-a-rep, https://www.emblaveo.com/microbiology | 2 |
| tpl_1 | Homepage | The main landing page of the website. | https://www.emblaveo.com/ | 1 |
| tpl_2 | Sitemap Page | Pages listing the sitemap of the website. | https://www.emblaveo.com/sitemap | 1 |
| tpl_3 | Video Gallery | Pages showcasing a collection of videos. | https://www.emblaveo.com/videos | 1 |
| tpl_4 | Content Article | Pages presenting general content articles. | https://www.emblaveo.com/changing-resistance | 1 |
| tpl_5 | Registration Form | Pages containing user registration forms. | https://www.emblaveo.com/registration | 1 |
| tpl_6 | Clinical Data | Pages containing clinical data and related information. | https://www.emblaveo.com/clinical-data | 1 |
| tpl_7 | Testing Information | Pages providing details on testing procedures or results. | https://www.emblaveo.com/susceptibility-testing | 1 |
| tpl_8 | Safety Profile | Pages detailing safety and risk information. | https://www.emblaveo.com/safety | 1 |
| tpl_9 | Medical Information | Pages containing detailed medical information. | https://www.emblaveo.com/medical-info | 1 |
| tpl_10 | Mechanism of Action | Pages explaining the mechanism of action for a product. | https://www.emblaveo.com/mechanism-of-action | 1 |
| tpl_11 | Dosing Information | Pages with dosing guidelines and instructions. | https://www.emblaveo.com/dosing | 1 |
| tpl_12 | Ordering Support | Pages assisting with product ordering. | https://www.emblaveo.com/ordering-and-support | 1 |
| tpl_13 | Customer Support | Pages providing customer support resources. | https://www.emblaveo.com/customer-service | 1 |
