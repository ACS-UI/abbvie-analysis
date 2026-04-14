# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **27** URLs; **8** layout templates were identified (agent (LLM batched assignment + merge)). Highest-traffic templates by page count include **Miscellaneous Pages**, **About Lupron**, **Starting Therapy**. **30** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T15:32:51.777Z
- **Website**: https://www.lupronped.com/
- **Total Pages Analyzed**: 27
- **Total Templates Identified**: 8
- **Total Components Identified**: 30
- **Grouping**: agent (LLM batched assignment + merge)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.LUPRONPED.COM TEMPLATES                                                  │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Miscellaneous Pages                  │    │ About Lupron                         │    │ Starting Therapy                     │
│ (8 pages)                            │    │ (5 pages)                            │    │ (4 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Glossary Navigation                │    │ • About Section {Unmapped}           │    │ • Tips Section {Unmapped}            │
│ • (+2 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Understanding CPP                    │    │ Homepage                             │    │ Site Map                             │
│ (3 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • About CPP Section {Unmapped}       │    │ • Two Column CTA - #1 Prescribed {U… │    │ • Sitemap Links {Unmapped}           │
│ • (+5 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • Important Safety Information {Unm… │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.LUPRONPED.COM — SUB-TEMPLATES TEMPLATES                                  │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Safety Information                   │    │ Search Results                       │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • Important Safety Information {Unm… │    │ • Search Results                     │
│ • Footer Links {Unmapped}            │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Miscellaneous Pages (`tpl_0`) — 8 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Glossary Navigation
- Glossary Content
- Important Safety Information

### About Lupron (`tpl_1`) — 5 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- About Section {Unmapped}
- Long-Term Data Section {Unmapped}
- Dosing Options {Unmapped}
- Side Effects {Unmapped}
- Footer

### Starting Therapy (`tpl_2`) — 4 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Tips Section {Unmapped}
- Tabbed Tips
- Adherence Tips {Unmapped}
- Support CTA Cards
- Footer

### Understanding CPP (`tpl_3`) — 3 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- About CPP Section {Unmapped}
- Common Signs Section {Unmapped}
- Potential Complications Section {Unmapped}
- Importance of Diagnosis Section {Unmapped}
- CTA Cards Section {Unmapped}
- Footer Important Safety Information

### Homepage (`tpl_4`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Two Column CTA - #1 Prescribed {Unmapped}
- Two Column CTA - Long-term Study {Unmapped}
- Two Column CTA - Syringe Options {Unmapped}
- Footer CTA List {Unmapped}
- Important Safety Information {Unmapped}

### Site Map (`tpl_5`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Sitemap Links {Unmapped}
- Important Safety Information {Unmapped}

### Safety Information (`tpl_6`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Important Safety Information {Unmapped}
- Footer Links {Unmapped}

### Search Results (`tpl_7`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Search Results
- Important Safety Information {Unmapped}
- Footer CTA Links


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌─────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                               │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├─────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Primary Navigation {Unmapped}           │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Hero Section                            │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │ ✅   │ ❌   │
│ Global Utility Navigation {Unmapped}    │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Important Safety Information {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │
│ Footer                                  │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Hero Section {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ✅   │
│ Utility Navigation {Unmapped}           │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
└─────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


### Template-specific components

```
┌────────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                  │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├────────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ About CPP Section {Unmapped}               │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ About Section {Unmapped}                   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Adherence Tips {Unmapped}                  │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Common Signs Section {Unmapped}            │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ CTA Cards Section {Unmapped}               │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Dosing Options {Unmapped}                  │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer CTA Links                           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer CTA List {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Footer Important Safety Information        │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Footer Links {Unmapped}                    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Glossary Content                           │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Glossary Navigation                        │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Importance of Diagnosis Section {Unmapped} │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Important Safety Information               │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└────────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T8 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Miscellaneous Pages (8 pgs)                                                                       │
│ • About Lupron (5 pgs)                                                                              │
│ • Starting Therapy (4 pgs)                                                                          │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Understanding CPP (3 pgs)                                                                         │
│ • Homepage (1 pgs)                                                                                  │
│ • Site Map (1 pgs)                                                                                  │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Safety Information (1 pgs)                                                                        │
│ • Search Results (1 pgs)                                                                            │
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
| tpl_0 | Miscellaneous Pages | Pages that do not fit into other specific templates. | https://www.lupronped.com/glossary, https://www.lupronped.com/lupron-support-plus, https://www.lupronped.com/faqs | 8 |
| tpl_1 | About Lupron | This template covers information about Lupron medication. | https://www.lupronped.com/about-lupron-depot-ped?3#flexible-dosing, https://www.lupronped.com/about-lupron-depot-ped, https://www.lupronped.com/about-lupron-depot-ped?2#18year-long | 5 |
| tpl_2 | Starting Therapy | Guidance and information for initiating therapy. | https://www.lupronped.com/starting-therapy?1#expect-atdoctor, https://www.lupronped.com/starting-therapy, https://www.lupronped.com/starting-therapy?2#look-urchild | 4 |
| tpl_3 | Understanding CPP | Educational content about Central Precocious Puberty. | https://www.lupronped.com/understanding-central-precocious-puberty?1#signs-of-cpp, https://www.lupronped.com/understanding-central-precocious-puberty, https://www.lupronped.com/understanding-central-precocious-puberty?2#potential-complications | 3 |
| tpl_4 | Homepage | The main landing page of the website. | https://www.lupronped.com/ | 1 |
| tpl_5 | Site Map | Overview of the site's structure and navigation links. | https://www.lupronped.com/site-map | 1 |
| tpl_6 | Safety Information | Details regarding important safety considerations. | https://www.lupronped.com/isi | 1 |
| tpl_7 | Search Results | Template for displaying search results. | https://www.lupronped.com/search-results | 1 |
