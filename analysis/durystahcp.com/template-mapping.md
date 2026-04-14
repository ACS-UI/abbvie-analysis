# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **25** URLs; **20** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Homepage**, **About Us Page**, **PDF File Page**. **42** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:33:13.556Z
- **Website**: https://www.durystahcp.com/
- **Total Pages Analyzed**: 25
- **Total Templates Identified**: 20
- **Total Components Identified**: 42
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.DURYSTAHCP.COM TEMPLATES                                                 │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Homepage                             │    │ About Us Page                        │    │ PDF File Page                        │
│ (2 pages)                            │    │ (2 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Background Image Section {Unmappe… │    │ • —                                  │
│ • Primary Navigation                 │    │ • Image and Text Section {Unmapped}  │    │ • —                                  │
│ • Hero Section                       │    │ • Rich Text Section {Unmapped}       │    │ • —                                  │
│ • Three Column CTA                   │    │ • CTA Button {Unmapped}              │    │ • —                                  │
│ • (+2 more — see Blocks mapped per … │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Resources Page                       │    │ Study Design Page                    │    │ Video Module                         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Study Design Rich Text Block {Unm… │    │ • Video Player                       │
│ • Primary Navigation {Unmapped}      │    │ • —                                  │    │ • Transcript Link {Unmapped}         │
│ • Hero Section                       │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Training Module                      │    │ Clinical Data Page                   │    │ Patient Site Module                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Background Container {Unmapped}    │    │ • Utility Navigation {Unmapped}      │    │ • Background Section {Unmapped}      │
│ • Image and Text Section {Unmapped}  │    │ • Primary Navigation {Unmapped}      │    │ • Image and Text Block {Unmapped}    │
│ • Rich Text Section {Unmapped}       │    │ • Hero Section                       │    │ • Rich Text Content {Unmapped}       │
│ • Call to Action Button {Unmapped}   │    │ • Tabs Section                       │    │ • Call-to-Action Button {Unmapped}   │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Logo Module                          │    │ Reimbursement Module                 │    │ Prescribing Info Module              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Background Image Section {Unmappe… │    │ • Background Image Section {Unmappe… │    │ • Background Container {Unmapped}    │
│ • Logo Display {Unmapped}            │    │ • Image Logo {Unmapped}              │    │ • Image and Text Component {Unmappe… │
│ • Rich Text Notice {Unmapped}        │    │ • Rich Text Notice {Unmapped}        │    │ • Rich Text Content {Unmapped}       │
│ • CTA Button {Unmapped}              │    │ • Proceed CTA Button {Unmapped}      │    │ • Call-to-Action Button {Unmapped}   │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Savings Program Module               │    │ Usage Guidelines Page                │    │ Sitemap Page                         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Background Image Section {Unmappe… │    │ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │
│ • Logo Image {Unmapped}              │    │ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │
│ • Rich Text Message {Unmapped}       │    │ • Hero Section                       │    │ • Hero Section {Unmapped}            │
│ • Proceed CTA {Unmapped}             │    │ • Safety Information                 │    │ • Sitemap List {Unmapped}            │
│ • —                                  │    │ • Footer Section                     │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.DURYSTAHCP.COM — SUB-TEMPLATES TEMPLATES                                 │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Request Rep Module                   │    │ Overview Module                      │    │ Privacy Policy Page                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │    │ • Background Container {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Interactive Image {Unmapped}       │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Centered Rich Text {Unmapped}      │
│ • Rich Text Content {Unmapped}       │    │ • Safety Information {Unmapped}      │    │ • Proceed Button CTA {Unmapped}      │
│ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Terms of Use Page                    │    │ FAQ Page                             │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Background Container {Unmapped}    │    │ • Global Utility Navigation          │
│ • Image and Text Section {Unmapped}  │    │ • Primary Navigation                 │
│ • Rich Text Block {Unmapped}         │    │ • Hero Section                       │
│ • Call to Action {Unmapped}          │    │ • FAQ Accordion                      │
│ • —                                  │    │ • Important Safety Information {Unm… │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Homepage (`tpl_0`) — 2 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Three Column CTA
- Important Safety Information
- Footer

### About Us Page (`tpl_1`) — 2 pages

- Background Image Section {Unmapped}
- Image and Text Section {Unmapped}
- Rich Text Section {Unmapped}
- CTA Button {Unmapped}

### PDF File Page (`tpl_2`) — 1 pages

- —

### Resources Page (`tpl_3`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section

### Study Design Page (`tpl_4`) — 1 pages

- Study Design Rich Text Block {Unmapped}

### Video Module (`tpl_5`) — 1 pages

- Video Player
- Transcript Link {Unmapped}

### Training Module (`tpl_6`) — 1 pages

- Background Container {Unmapped}
- Image and Text Section {Unmapped}
- Rich Text Section {Unmapped}
- Call to Action Button {Unmapped}

### Clinical Data Page (`tpl_7`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Tabs Section

### Patient Site Module (`tpl_8`) — 1 pages

- Background Section {Unmapped}
- Image and Text Block {Unmapped}
- Rich Text Content {Unmapped}
- Call-to-Action Button {Unmapped}

### Logo Module (`tpl_9`) — 1 pages

- Background Image Section {Unmapped}
- Logo Display {Unmapped}
- Rich Text Notice {Unmapped}
- CTA Button {Unmapped}

### Reimbursement Module (`tpl_10`) — 1 pages

- Background Image Section {Unmapped}
- Image Logo {Unmapped}
- Rich Text Notice {Unmapped}
- Proceed CTA Button {Unmapped}

### Prescribing Info Module (`tpl_11`) — 1 pages

- Background Container {Unmapped}
- Image and Text Component {Unmapped}
- Rich Text Content {Unmapped}
- Call-to-Action Button {Unmapped}

### Savings Program Module (`tpl_12`) — 1 pages

- Background Image Section {Unmapped}
- Logo Image {Unmapped}
- Rich Text Message {Unmapped}
- Proceed CTA {Unmapped}

### Usage Guidelines Page (`tpl_13`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Safety Information
- Footer Section

### Sitemap Page (`tpl_14`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Sitemap List {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links
- Footer Legal {Unmapped}

### Request Rep Module (`tpl_15`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Rich Text Content {Unmapped}
- Call to Action Button {Unmapped}
- Footer
- Modal Dialog
- Safety Bar {Unmapped}

### Overview Module (`tpl_16`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Safety Information {Unmapped}
- Footer Section
- Modal Dialogs {Unmapped}
- Promotional Drawer {Unmapped}
- Safety Bar {Unmapped}

### Privacy Policy Page (`tpl_17`) — 1 pages

- Background Container {Unmapped}
- Interactive Image {Unmapped}
- Centered Rich Text {Unmapped}
- Proceed Button CTA {Unmapped}

### Terms of Use Page (`tpl_18`) — 1 pages

- Background Container {Unmapped}
- Image and Text Section {Unmapped}
- Rich Text Block {Unmapped}
- Call to Action {Unmapped}

### FAQ Page (`tpl_19`) — 1 pages

- Global Utility Navigation
- Primary Navigation
- Hero Section
- FAQ Accordion
- Important Safety Information {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                            │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Primary Navigation {Unmapped}           │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Utility Navigation {Unmapped}           │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Background Container {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Background Image Section {Unmapped}     │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Image and Text Section {Unmapped}       │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Primary Navigation                      │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Rich Text Content {Unmapped}            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call to Action Button {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Call-to-Action Button {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ CTA Button {Unmapped}                   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer                                  │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Section                          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Hero Section {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T20 omitted from matrix width; see appendix.*


### Template-specific components

```
┌─────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                           │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Background Section {Unmapped}       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call to Action {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Centered Rich Text {Unmapped}       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ FAQ Accordion                       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Legal {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Links                        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global Utility Navigation           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Image and Text Block {Unmapped}     │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Image and Text Component {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Image Logo {Unmapped}               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Important Safety Information        │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Interactive Image {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Logo Display {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Logo Image {Unmapped}               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T20 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage (2 pgs)                                                                                  │
│ • About Us Page (2 pgs)                                                                             │
│ • PDF File Page (1 pgs)                                                                             │
│ • Resources Page (1 pgs)                                                                            │
│ • Study Design Page (1 pgs)                                                                         │
│ • Video Module (1 pgs)                                                                              │
│ • Training Module (1 pgs)                                                                           │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Clinical Data Page (1 pgs)                                                                        │
│ • Patient Site Module (1 pgs)                                                                       │
│ • Logo Module (1 pgs)                                                                               │
│ • Reimbursement Module (1 pgs)                                                                      │
│ • Prescribing Info Module (1 pgs)                                                                   │
│ • Savings Program Module (1 pgs)                                                                    │
│ • Usage Guidelines Page (1 pgs)                                                                     │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Sitemap Page (1 pgs)                                                                              │
│ • Request Rep Module (1 pgs)                                                                        │
│ • Overview Module (1 pgs)                                                                           │
│ • Privacy Policy Page (1 pgs)                                                                       │
│ • Terms of Use Page (1 pgs)                                                                         │
│ • FAQ Page (1 pgs)                                                                                  │
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
| tpl_0 | Homepage | Template for the main landing page. | https://www.durystahcp.com/, https://www.durystahcp.com/site-modols/homepage-hero | 2 |
| tpl_1 | About Us Page | Template for pages describing the organization. | https://www.durystahcp.com/site-modols/aboutabbvie, https://www.durystahcp.com/about-durysta | 2 |
| tpl_2 | PDF File Page | Template for PDF file resources. | https://www.durystahcp.com/content/dam/durystahcp/en_us/pdf/DURYSTA_Patient_Enrollment_Form.pdf | 1 |
| tpl_3 | Resources Page | Template for resource listings. | https://www.durystahcp.com/resources | 1 |
| tpl_4 | Study Design Page | Template for study design information. | https://www.durystahcp.com/site-modols/study_design | 1 |
| tpl_5 | Video Module | Template for video content. | https://www.durystahcp.com/site-modols/patient-testimony-video | 1 |
| tpl_6 | Training Module | Template for training resources. | https://www.durystahcp.com/site-modols/trainingcta | 1 |
| tpl_7 | Clinical Data Page | Template for displaying clinical data. | https://www.durystahcp.com/clinical-data | 1 |
| tpl_8 | Patient Site Module | Template for patient-specific content. | https://www.durystahcp.com/site-modols/patient_site | 1 |
| tpl_9 | Logo Module | Template for logo display. | https://www.durystahcp.com/site-modols/logo | 1 |
| tpl_10 | Reimbursement Module | Template for reimbursement details. | https://www.durystahcp.com/site-modols/reimbursementcta | 1 |
| tpl_11 | Prescribing Info Module | Template for prescribing information. | https://www.durystahcp.com/site-modols/prescibing_information | 1 |
| tpl_12 | Savings Program Module | Template for savings program information. | https://www.durystahcp.com/site-modols/durysta-savings-program | 1 |
| tpl_13 | Usage Guidelines Page | Template for usage guidelines. | https://www.durystahcp.com/when-to-use | 1 |
| tpl_14 | Sitemap Page | Template for the sitemap. | https://www.durystahcp.com/sitemap | 1 |
| tpl_15 | Request Rep Module | Template for requesting representative information. | https://www.durystahcp.com/site-modols/patientsite_requestrep | 1 |
| tpl_16 | Overview Module | Template for overview content. | https://www.durystahcp.com/site-modols | 1 |
| tpl_17 | Privacy Policy Page | Template for privacy policy details. | https://www.durystahcp.com/site-modols/privacy-policy | 1 |
| tpl_18 | Terms of Use Page | Template for terms of use. | https://www.durystahcp.com/site-modols/terms-of-use | 1 |
| tpl_19 | FAQ Page | Template for frequently asked questions. | https://www.durystahcp.com/faq | 1 |
