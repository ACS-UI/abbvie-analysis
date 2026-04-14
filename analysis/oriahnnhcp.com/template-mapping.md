# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **102** URLs; **12** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Document PDF**, **Agent Batch**, **Efficacy Section**. **44** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:42:27.912Z
- **Website**: https://www.oriahnnhcp.com/
- **Total Pages Analyzed**: 102
- **Total Templates Identified**: 12
- **Total Components Identified**: 44
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.ORIAHNNHCP.COM TEMPLATES                                                 │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Document PDF                         │    │ Agent Batch                          │    │ Efficacy Section                     │
│ (18 pages)                           │    │ (16 pages)                           │    │ (7 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • —                                  │    │ • Disease Severity Tabs              │    │ • Hero Section                       │
│ • —                                  │    │ • Patient Demographics Tabs          │    │ • Efficacy Flexbox {Unmapped}        │
│ • —                                  │    │ • Fibroid Location Chart {Unmapped}  │    │ • Important Safety Information {Unm… │
│ • —                                  │    │ • Primary Fibroid Volume Chart {Unm… │    │ • Footer Links                       │
│ • —                                  │    │ • (+6 more — see Blocks mapped per … │    │ • Back to Top Button {Unmapped}      │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Safety Information                   │    │ Homepage                             │    │ Contact Page                         │
│ (2 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Adverse Reactions Table {Unmapped} │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │
│ • Discontinuation Section {Unmapped} │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Important Safety Information {Unm… │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Footer                             │    │ • CTA Columns {Unmapped}             │    │ • Contact Form                       │
│ • Back to Top Button {Unmapped}      │    │ • (+2 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Search Results                       │    │ Clinical Data                        │    │ Resources                            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation                 │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │
│ • Search Box                         │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Hero Section                       │    │ • Section Navigation {Unmapped}      │    │ • Educational Resources              │
│ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.ORIAHNNHCP.COM — SUB-TEMPLATES TEMPLATES                                 │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Access Page                          │    │ Patient Stories                      │    │ Site Map                             │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Main Navigation {Unmapped}         │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Insurance Coverage Introduction {… │    │ • Patient Profiles {Unmapped}        │    │ • Sitemap Links {Unmapped}           │
│ • (+5 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Document PDF (`tpl_0`) — 18 pages

- —

### Agent Batch (`tpl_1`) — 16 pages

- Disease Severity Tabs
- Patient Demographics Tabs
- Fibroid Location Chart {Unmapped}
- Primary Fibroid Volume Chart {Unmapped}
- Uterine Volume Chart {Unmapped}
- MBL Volume Chart {Unmapped}
- BMI Chart {Unmapped}
- Race Chart {Unmapped}
- Ethnicity Chart {Unmapped}
- Age Chart {Unmapped}

### Efficacy Section (`tpl_2`) — 7 pages

- Hero Section
- Efficacy Flexbox {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links
- Back to Top Button {Unmapped}

### Safety Information (`tpl_3`) — 2 pages

- Adverse Reactions Table {Unmapped}
- Discontinuation Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### Homepage (`tpl_4`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- CTA Columns {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links

### Contact Page (`tpl_5`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Contact Form
- Important Safety Information {Unmapped}
- Footer Links
- Back to Top Button {Unmapped}

### Search Results (`tpl_6`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Search Box
- Hero Section
- Search Results {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links
- Back to Top Button {Unmapped}

### Clinical Data (`tpl_7`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Section Navigation {Unmapped}
- Study Design {Unmapped}
- Primary Endpoint {Unmapped}
- Reduction Over Time {Unmapped}
- Subgroup Analysis {Unmapped}

### Resources (`tpl_8`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Educational Resources
- Contact Representative CTA {Unmapped}
- Speaker Program CTA {Unmapped}
- Important Safety Information
- Footer Links

### Access Page (`tpl_9`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Insurance Coverage Introduction {Unmapped}
- Insurance Lookup Form {Unmapped}
- Insurance Coverage Chart {Unmapped}
- Insurance Coverage Details {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links

### Patient Stories (`tpl_10`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Patient Profiles {Unmapped}
- Statistical Highlight {Unmapped}
- Discussion Prompts {Unmapped}
- Counseling Call-to-Action {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links

### Site Map (`tpl_11`) — 1 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Hero Section
- Sitemap Links {Unmapped}
- Safety Information {Unmapped}
- Footer Links


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                            │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │
│ Footer Links                            │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │
│ Important Safety Information {Unmapped} │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Primary Navigation {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │
│ Back to Top Button {Unmapped}           │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │
│ Utility Navigation {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Global Utility Navigation {Unmapped}    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T12 omitted from matrix width; see appendix.*


### Template-specific components

```
┌────────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                  │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├────────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Adverse Reactions Table {Unmapped}         │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Age Chart {Unmapped}                       │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ BMI Chart {Unmapped}                       │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Contact Form                               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Contact Representative CTA {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Counseling Call-to-Action {Unmapped}       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ CTA Columns {Unmapped}                     │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Discontinuation Section {Unmapped}         │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Discussion Prompts {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Disease Severity Tabs                      │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Educational Resources                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Efficacy Flexbox {Unmapped}                │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Ethnicity Chart {Unmapped}                 │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Fibroid Location Chart {Unmapped}          │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└────────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T12 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Document PDF (18 pgs)                                                                             │
│ • Agent Batch (16 pgs)                                                                              │
│ • Efficacy Section (7 pgs)                                                                          │
│ • Safety Information (2 pgs)                                                                        │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Homepage (1 pgs)                                                                                  │
│ • Contact Page (1 pgs)                                                                              │
│ • Search Results (1 pgs)                                                                            │
│ • Clinical Data (1 pgs)                                                                             │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Resources (1 pgs)                                                                                 │
│ • Access Page (1 pgs)                                                                               │
│ • Patient Stories (1 pgs)                                                                           │
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
| tpl_0 | Document PDF | Template for pages displaying or managing PDF documents. | https://www.oriahnnhcp.com/content/dam/elagolixhcp/pdf/hcp-appeals-letter-optimized.pdf, https://www.oriahnnhcp.com/content/dam/elagolixhcp/pdf/hcp-letter-medical-necessity-optimized.pdf, https://www.oriahnnhcp.com/content/dam/elagolixhcp/pdf/hcp-letter-medical-necessity-instruction-guide-optimized.pdf | 18 |
| tpl_1 | Agent Batch | Template for agent-related batch processing pages. | https://www.oriahnnhcp.com/clinical-trial-data/efficacy-disease-severity, https://www.oriahnnhcp.com/dosing-information/dosing-information-flexbox, https://www.oriahnnhcp.com/patient-support-and-savings | 16 |
| tpl_2 | Efficacy Section | Template for pages detailing efficacy information. | https://www.oriahnnhcp.com/efficacy/efficacy-flexbox-hemoglobin, https://www.oriahnnhcp.com/efficacy/efficacy-flexbox-subgroup1, https://www.oriahnnhcp.com/efficacy/efficacy-flexbox-subgroup | 7 |
| tpl_3 | Safety Information | Template for pages related to safety and adverse reactions. | https://www.oriahnnhcp.com/safety-adverse-reactions/safety-adverse-reactions-flexbox, https://www.oriahnnhcp.com/safety-adverse-reactions | 2 |
| tpl_4 | Homepage | Template for the main landing page of the website. | https://www.oriahnnhcp.com/ | 1 |
| tpl_5 | Contact Page | Template for pages used to contact the organization. | https://www.oriahnnhcp.com/contact-a-rep | 1 |
| tpl_6 | Search Results | Template for displaying search results. | https://www.oriahnnhcp.com/search-results | 1 |
| tpl_7 | Clinical Data | Template for pages displaying clinical data and insights. | https://www.oriahnnhcp.com/clinical-trial-data | 1 |
| tpl_8 | Resources | Template for pages providing various resources. | https://www.oriahnnhcp.com/resources | 1 |
| tpl_9 | Access Page | Template for pages related to accessing resources or information. | https://www.oriahnnhcp.com/access | 1 |
| tpl_10 | Patient Stories | Template for pages showcasing patient stories and testimonials. | https://www.oriahnnhcp.com/patient-stories | 1 |
| tpl_11 | Site Map | Template for the site map page. | https://www.oriahnnhcp.com/site-map | 1 |
