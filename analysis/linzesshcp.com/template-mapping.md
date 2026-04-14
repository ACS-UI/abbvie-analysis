# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **27** URLs; **8** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Agent Unassigned**, **Downloadable Resources**, **Mechanism of Action**. **23** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:18:37.850Z
- **Website**: https://www.linzesshcp.com/
- **Total Pages Analyzed**: 27
- **Total Templates Identified**: 8
- **Total Components Identified**: 23
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.LINZESSHCP.COM TEMPLATES                                                 │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Agent Unassigned                     │    │ Downloadable Resources               │    │ Mechanism of Action                  │
│ (17 pages)                           │    │ (3 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • —                                  │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • —                                  │    │ • Primary Navigation {Unmapped}      │
│ • Hero Banner {Unmapped}             │    │ • —                                  │    │ • Hero Banner                        │
│ • CIC Safety Introduction {Unmapped} │    │ • —                                  │    │ • Main Content Section {Unmapped}    │
│ • (+3 more — see Blocks mapped per … │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Home Page                            │    │ Dosing Information                   │    │ Safety Profile                       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Banner {Unmapped}             │    │ • Hero Section                       │    │ • Footer Section                     │
│ • Indications Section {Unmapped}     │    │ • Dosing Information Columns {Unmap… │    │ • —                                  │
│ • (+2 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.LINZESSHCP.COM — SUB-TEMPLATES TEMPLATES                                 │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Efficacy Data                        │    │ Patient Profiles                     │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • —                                  │
│ • Section Navigation {Unmapped}      │    │ • —                                  │
│ • (+5 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Agent Unassigned (`tpl_0`) — 17 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Banner {Unmapped}
- CIC Safety Introduction {Unmapped}
- Adverse Reactions Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer

### Downloadable Resources (`tpl_1`) — 3 pages

- —

### Mechanism of Action (`tpl_2`) — 2 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Banner
- Main Content Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer Navigation

### Home Page (`tpl_3`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Banner {Unmapped}
- Indications Section {Unmapped}
- Safety Information {Unmapped}
- Footer {Unmapped}

### Dosing Information (`tpl_4`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Dosing Information Columns {Unmapped}
- Dosing Schedule {Unmapped}
- Clinical Considerations {Unmapped}
- Important Safety Information {Unmapped}
- Footer Section

### Safety Profile (`tpl_5`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Footer Section

### Efficacy Data (`tpl_6`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Section Navigation {Unmapped}
- Pivotal Studies Section One {Unmapped}
- Pivotal Studies Section Two {Unmapped}
- Pivotal Studies Section Three {Unmapped}
- Clinical Trial Design {Unmapped}
- Overall Symptoms Section {Unmapped}

### Patient Profiles (`tpl_7`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Primary Navigation {Unmapped}           │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Utility Navigation {Unmapped}           │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Important Safety Information {Unmapped} │ ✅   │ ❌   │ ✅   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Footer Section                          │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Hero Banner {Unmapped}                  │ ✅   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Hero Section                            │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


### Template-specific components

```
┌──────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Adverse Reactions Section {Unmapped}     │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ CIC Safety Introduction {Unmapped}       │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Clinical Considerations {Unmapped}       │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Clinical Trial Design {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Dosing Information Columns {Unmapped}    │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Dosing Schedule {Unmapped}               │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Footer                                   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer {Unmapped}                        │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Footer Navigation                        │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global Utility Navigation {Unmapped}     │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global Utility Strip {Unmapped}          │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Hero Banner                              │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Indications Section {Unmapped}           │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Main Content Section {Unmapped}          │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Agent Unassigned (17 pgs)                                                                         │
│ • Downloadable Resources (3 pgs)                                                                    │
│ • Mechanism of Action (2 pgs)                                                                       │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Home Page (1 pgs)                                                                                 │
│ • Dosing Information (1 pgs)                                                                        │
│ • Safety Profile (1 pgs)                                                                            │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Efficacy Data (1 pgs)                                                                             │
│ • Patient Profiles (1 pgs)                                                                          │
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
| tpl_0 | Agent Unassigned | Pages related to unassigned agents. | https://www.linzesshcp.com/linzess-cic-safety, https://www.linzesshcp.com/linzess-additional-resources, https://www.linzesshcp.com/linzess-cic-efficacy | 17 |
| tpl_1 | Downloadable Resources | Pages containing downloadable PDF resources. | https://www.linzesshcp.com/content/dam/linzesshcp/pdf/Tell-Me-About-Your-Gut_FINAL-UNB116522.pdf, https://www.linzesshcp.com/content/dam/linzesshcp/pdf/11216-LINZESSTelemedKit-FINAL.pdf, https://www.linzesshcp.com/content/dam/linzesshcp/pdf/Tell-Me-About-Your-Gut-Intake-Form.pdf | 3 |
| tpl_2 | Mechanism of Action | Details about the mechanism of action. | https://www.linzesshcp.com/ibs-c-moa, https://www.linzesshcp.com/cic-moa | 2 |
| tpl_3 | Home Page | The main landing page of the website. | https://www.linzesshcp.com/ | 1 |
| tpl_4 | Dosing Information | Details about dosage instructions. | https://www.linzesshcp.com/linzess-dosing | 1 |
| tpl_5 | Safety Profile | Safety and risk information. | https://www.linzesshcp.com/linzess-ibs-c-safety | 1 |
| tpl_6 | Efficacy Data | Information about the efficacy of treatments. | https://www.linzesshcp.com/linzess-ibs-c-efficacy | 1 |
| tpl_7 | Patient Profiles | Profiles and case studies of patients. | https://www.linzesshcp.com/ibs-c-patient-profiles | 1 |
