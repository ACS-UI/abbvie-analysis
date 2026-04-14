# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **30** URLs; **8** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Home Page**, **Prescribing Page**, **Dosing Page**. **38** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:22:23.107Z
- **Website**: https://www.synthroidhcppr.com/
- **Total Pages Analyzed**: 30
- **Total Templates Identified**: 8
- **Total Components Identified**: 38
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.SYNTHROIDHCPPR.COM TEMPLATES                                             │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Home Page                            │    │ Prescribing Page                     │    │ Dosing Page                          │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │    │ • Primary Header {Unmapped}          │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section {Unmapped}            │
│ • Content Columns                    │    │ • Manufacturing Integrity Section {… │    │ • Dosing Options {Unmapped}          │
│ • (+6 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Sitemap Page                         │    │ Contact Page                         │    │ References Page                      │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • Sitemap Links {Unmapped}           │    │ • Contact Form                       │    │ • References List {Unmapped}         │
│ • (+3 more — see Blocks mapped per … │    │ • (+7 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.SYNTHROIDHCPPR.COM — SUB-TEMPLATES TEMPLATES                             │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Protect Script Page                  │    │ Clinical Scenarios Page              │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation                 │
│ • Primary Header {Unmapped}          │    │ • Primary Navigation                 │
│ • Hero Section                       │    │ • Hero Section                       │
│ • Three Column Banner {Unmapped}     │    │ • Patient Profiles                   │
│ • (+7 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Home Page (`tpl_0`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Columns
- Important Safety Information {Unmapped}
- Footer
- Back to Top Button {Unmapped}
- Special Considerations Modal
- Study Design Modal
- Warn on Leave Modal

### Prescribing Page (`tpl_1`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Manufacturing Integrity Section {Unmapped}
- Patient Information Section {Unmapped}
- Preventing Substitution Section {Unmapped}
- Clinical Guidelines Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### Dosing Page (`tpl_2`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Hero Section {Unmapped}
- Dosing Options {Unmapped}
- Monitoring Guidelines {Unmapped}
- Pill Tabs {Unmapped}
- Footer

### Sitemap Page (`tpl_3`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Sitemap Links {Unmapped}
- Important Safety Information {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### Contact Page (`tpl_4`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Contact Form
- Important Safety Information {Unmapped}
- Footer Section
- Back to Top Button {Unmapped}
- Special Considerations Modal
- Study Design Modal
- Warn on Leave Modal
- Request Submitted Modal

### References Page (`tpl_5`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- References List {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links
- Footer Legal Text
- Back to Top Button {Unmapped}

### Protect Script Page (`tpl_6`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Three Column Banner {Unmapped}
- Statistic Highlight {Unmapped}
- Footer Message
- Protected RX Section {Unmapped}
- Unprotected RX Section {Unmapped}
- Identifying Synthroid {Unmapped}
- Refill Reminder {Unmapped}
- Important Safety Information {Unmapped}

### Clinical Scenarios Page (`tpl_7`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Patient Profiles
- Clinical Insight
- Case Study
- Footer


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                            │ ✅   │ ✅   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │
│ Important Safety Information {Unmapped} │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Footer                                  │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Back to Top Button {Unmapped}           │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Global Utility Navigation {Unmapped}    │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │
│ Primary Navigation {Unmapped}           │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Primary Header {Unmapped}               │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Hero Section {Unmapped}                 │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Special Considerations Modal            │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Study Design Modal                      │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Utility Navigation {Unmapped}           │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Warn on Leave Modal                     │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


### Template-specific components

```
┌────────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                  │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├────────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Case Study                                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Clinical Guidelines Section {Unmapped}     │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Clinical Insight                           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Contact Form                               │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Content Columns                            │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Dosing Options {Unmapped}                  │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Legal Text                          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Footer Links                               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Footer Message                             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Footer Section                             │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Global Utility Strip {Unmapped}            │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Identifying Synthroid {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Manufacturing Integrity Section {Unmapped} │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Monitoring Guidelines {Unmapped}           │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
└────────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Home Page (1 pgs)                                                                                 │
│ • Prescribing Page (1 pgs)                                                                          │
│ • Dosing Page (1 pgs)                                                                               │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Sitemap Page (1 pgs)                                                                              │
│ • Contact Page (1 pgs)                                                                              │
│ • References Page (1 pgs)                                                                           │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Protect Script Page (1 pgs)                                                                       │
│ • Clinical Scenarios Page (1 pgs)                                                                   │
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
| tpl_0 | Home Page | The main landing page template of the website. | https://www.synthroidhcppr.com/ | 1 |
| tpl_1 | Prescribing Page | A page template for outlining prescribing practices. | https://www.synthroidhcppr.com/prescribing | 1 |
| tpl_2 | Dosing Page | A page template for providing dosing guidelines. | https://www.synthroidhcppr.com/dosing | 1 |
| tpl_3 | Sitemap Page | A page template for displaying the website's sitemap. | https://www.synthroidhcppr.com/sitemap | 1 |
| tpl_4 | Contact Page | A page template for displaying contact information. | https://www.synthroidhcppr.com/contact-a-representative | 1 |
| tpl_5 | References Page | A page template for listing references and citations. | https://www.synthroidhcppr.com/references | 1 |
| tpl_6 | Protect Script Page | A page template for secure script handling. | https://www.synthroidhcppr.com/protect-the-script | 1 |
| tpl_7 | Clinical Scenarios Page | A page template designed for presenting clinical scenarios. | https://www.synthroidhcppr.com/clinical-scenarios | 1 |
