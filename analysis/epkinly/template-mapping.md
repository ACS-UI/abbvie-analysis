# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **50** URLs; **29** layout templates were identified (signature (DOM fingerprint)). Highest-traffic templates by page count include **Fl Patient Brochure Spanish — group 2**, **Folleto Para Pacientes Con Ldcbg — group 3**, **Page layout group 1**. **13** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T12:39:33.157Z
- **Website**: https://www.epkinly.com/
- **Total Pages Analyzed**: 50
- **Total Templates Identified**: 29
- **Total Components Identified**: 13
- **Grouping**: signature (DOM fingerprint)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.EPKINLY.COM TEMPLATES                                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Fl Patient Brochure Spanish — group… │    │ Folleto Para Pacientes Con Ldcbg — … │    │ Page layout group 1                  │
│ (2 pages)                            │    │ (2 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │    │ • Site footer {Unmapped}             │
│ • (+6 more — see Blocks mapped per … │    │ • Site footer {Unmapped}             │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ 2l Fl — group 4                      │    │ Clinical Trial Results — group 5     │    │ Dlbcl — group 6                      │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │
│ • (+2 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ What Is Epkinly — group 7            │    │ Treatment — group 8                  │    │ Terms Conditions — group 9           │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │    │ • Site footer {Unmapped}             │
│ • Site footer {Unmapped}             │    │ • (+3 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Contact Us — group 10                │    │ Patient Stories — group 11           │    │ Register — group 12                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • main region 1 {Unmapped}           │    │ • Site footer {Unmapped}             │
│ • —                                  │    │ • (+2 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Site Map — group 13                  │    │ Treatment With Epkinly — group 14    │    │ Clinical Trial Results — group 15    │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │
│ • —                                  │    │ • (+8 more — see Blocks mapped per … │    │ • Site footer {Unmapped}             │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Site Map — group 16                  │    │ Clinical Trial Results — group 17    │    │ Clinical Trial Results — group 18    │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • Site footer {Unmapped}             │    │ • main region 1 {Unmapped}           │
│ • —                                  │    │ • —                                  │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Site Map — group 19                  │    │ Support — group 20                   │    │ Site Map — group 21                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • Site footer {Unmapped}             │    │ • Site footer {Unmapped}             │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.EPKINLY.COM — SUB-TEMPLATES TEMPLATES                                    │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Care Partner Support — group 22      │    │ Treatment — group 23                 │    │ Treatment — group 24                 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │
│ • (+7 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Patient Support — group 25           │    │ 3l Fl — group 26                     │    │ Care Partner Support — group 27      │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │
│ • (+6 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Search Results — group 28            │    │ Care Partner Support — group 29      │
│ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global utility bar {Unmapped}      │    │ • Global utility bar {Unmapped}      │
│ • Primary site header and navigatio… │    │ • Primary site header and navigatio… │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • main region 1 {Unmapped}           │
│ • —                                  │    │ • (+7 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Fl Patient Brochure Spanish — group 2 (`tpl_1`) — 2 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- main region 5 {Unmapped}
- main region 6 {Unmapped}
- Site footer {Unmapped}

### Folleto Para Pacientes Con Ldcbg — group 3 (`tpl_2`) — 2 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Site footer {Unmapped}

### Page layout group 1 (`tpl_0`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### 2l Fl — group 4 (`tpl_3`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- Site footer {Unmapped}

### Clinical Trial Results — group 5 (`tpl_4`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- Site footer {Unmapped}

### Dlbcl — group 6 (`tpl_5`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- Site footer {Unmapped}

### What Is Epkinly — group 7 (`tpl_6`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Site footer {Unmapped}

### Treatment — group 8 (`tpl_7`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- Site footer {Unmapped}

### Terms Conditions — group 9 (`tpl_8`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Contact Us — group 10 (`tpl_9`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Patient Stories — group 11 (`tpl_10`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- Site footer {Unmapped}

### Register — group 12 (`tpl_11`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Site Map — group 13 (`tpl_12`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Treatment With Epkinly — group 14 (`tpl_13`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- main region 5 {Unmapped}
- main region 6 {Unmapped}
- main region 7 {Unmapped}
- main region 8 {Unmapped}
- Site footer {Unmapped}

### Clinical Trial Results — group 15 (`tpl_14`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Site footer {Unmapped}

### Site Map — group 16 (`tpl_15`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Clinical Trial Results — group 17 (`tpl_16`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Clinical Trial Results — group 18 (`tpl_17`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- Site footer {Unmapped}

### Site Map — group 19 (`tpl_18`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Support — group 20 (`tpl_19`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Site Map — group 21 (`tpl_20`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Care Partner Support — group 22 (`tpl_21`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- main region 5 {Unmapped}
- main region 6 {Unmapped}
- main region 7 {Unmapped}
- Site footer {Unmapped}

### Treatment — group 23 (`tpl_22`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- Site footer {Unmapped}

### Treatment — group 24 (`tpl_23`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- Site footer {Unmapped}

### Patient Support — group 25 (`tpl_24`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- main region 5 {Unmapped}
- main region 6 {Unmapped}
- Site footer {Unmapped}

### 3l Fl — group 26 (`tpl_25`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- Site footer {Unmapped}

### Care Partner Support — group 27 (`tpl_26`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- columns {Unmapped}
- main region 4 {Unmapped}
- Site footer {Unmapped}

### Search Results — group 28 (`tpl_27`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Care Partner Support — group 29 (`tpl_28`) — 1 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- main region 5 {Unmapped}
- main region 6 {Unmapped}
- main region 7 {Unmapped}
- Site footer {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌───────────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                     │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├───────────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Global utility bar {Unmapped}                 │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ main region 0 {Unmapped}                      │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Primary site header and navigation {Unmapped} │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Site footer {Unmapped}                        │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ main region 1 {Unmapped}                      │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │
│ main region 2 {Unmapped}                      │ ✅   │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │
│ main region 3 {Unmapped}                      │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │
│ main region 4 {Unmapped}                      │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ main region 5 {Unmapped}                      │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ main region 6 {Unmapped}                      │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ main region 7 {Unmapped}                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└───────────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T29 omitted from matrix width; see appendix.*


### Template-specific components

```
┌──────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                    │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ columns {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ main region 8 {Unmapped}     │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T29 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Fl Patient Brochure Spanish — group 2 (2 pgs)                                                     │
│ • Folleto Para Pacientes Con Ldcbg — group 3 (2 pgs)                                                │
│ • Page layout group 1 (1 pgs)                                                                       │
│ • 2l Fl — group 4 (1 pgs)                                                                           │
│ • Clinical Trial Results — group 5 (1 pgs)                                                          │
│ • Dlbcl — group 6 (1 pgs)                                                                           │
│ • What Is Epkinly — group 7 (1 pgs)                                                                 │
│ • Treatment — group 8 (1 pgs)                                                                       │
│ • Terms Conditions — group 9 (1 pgs)                                                                │
│ • Contact Us — group 10 (1 pgs)                                                                     │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Patient Stories — group 11 (1 pgs)                                                                │
│ • Register — group 12 (1 pgs)                                                                       │
│ • Site Map — group 13 (1 pgs)                                                                       │
│ • Treatment With Epkinly — group 14 (1 pgs)                                                         │
│ • Clinical Trial Results — group 15 (1 pgs)                                                         │
│ • Site Map — group 16 (1 pgs)                                                                       │
│ • Clinical Trial Results — group 17 (1 pgs)                                                         │
│ • Clinical Trial Results — group 18 (1 pgs)                                                         │
│ • Site Map — group 19 (1 pgs)                                                                       │
│ • Support — group 20 (1 pgs)                                                                        │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Site Map — group 21 (1 pgs)                                                                       │
│ • Care Partner Support — group 22 (1 pgs)                                                           │
│ • Treatment — group 23 (1 pgs)                                                                      │
│ • Treatment — group 24 (1 pgs)                                                                      │
│ • Patient Support — group 25 (1 pgs)                                                                │
│ • 3l Fl — group 26 (1 pgs)                                                                          │
│ • Care Partner Support — group 27 (1 pgs)                                                           │
│ • Search Results — group 28 (1 pgs)                                                                 │
│ • Care Partner Support — group 29 (1 pgs)                                                           │
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
| tpl_0 | Page layout group 1 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/ | 1 |
| tpl_1 | Fl Patient Brochure Spanish — group 2 | Same structural layout across 2 page(s) in the crawl. | https://www.epkinly.com/content/dam/epcoritamab/docs/fl-patient-brochure-spanish.pdf, https://www.epkinly.com/3l-fl/patient-support | 2 |
| tpl_2 | Folleto Para Pacientes Con Ldcbg — group 3 | Same structural layout across 2 page(s) in the crawl. | https://www.epkinly.com/content/dam/epcoritamab/docs/folleto-para-pacientes-con-ldcbg.pdf, https://www.epkinly.com/dlbcl/patient-support | 2 |
| tpl_3 | 2l Fl — group 4 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/2l-fl | 1 |
| tpl_4 | Clinical Trial Results — group 5 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/2l-fl/clinical-trial-results | 1 |
| tpl_5 | Dlbcl — group 6 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/dlbcl | 1 |
| tpl_6 | What Is Epkinly — group 7 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/what-is-epkinly | 1 |
| tpl_7 | Treatment — group 8 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/dlbcl/treatment | 1 |
| tpl_8 | Terms Conditions — group 9 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/terms-conditions | 1 |
| tpl_9 | Contact Us — group 10 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/contact-us | 1 |
| tpl_10 | Patient Stories — group 11 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/dlbcl/patient-stories | 1 |
| tpl_11 | Register — group 12 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/register | 1 |
| tpl_12 | Site Map — group 13 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/site-map | 1 |
| tpl_13 | Treatment With Epkinly — group 14 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/treatment-with-epkinly | 1 |
| tpl_14 | Clinical Trial Results — group 15 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/dlbcl/clinical-trial-results | 1 |
| tpl_15 | Site Map — group 16 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/2l-fl/site-map | 1 |
| tpl_16 | Clinical Trial Results — group 17 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/clinical-trial-results | 1 |
| tpl_17 | Clinical Trial Results — group 18 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/3l-fl/clinical-trial-results | 1 |
| tpl_18 | Site Map — group 19 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/3l-fl/site-map | 1 |
| tpl_19 | Support — group 20 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/support | 1 |
| tpl_20 | Site Map — group 21 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/dlbcl/site-map | 1 |
| tpl_21 | Care Partner Support — group 22 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/3l-fl/care-partner-support | 1 |
| tpl_22 | Treatment — group 23 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/2l-fl/treatment | 1 |
| tpl_23 | Treatment — group 24 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/3l-fl/treatment | 1 |
| tpl_24 | Patient Support — group 25 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/2l-fl/patient-support | 1 |
| tpl_25 | 3l Fl — group 26 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/3l-fl | 1 |
| tpl_26 | Care Partner Support — group 27 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/dlbcl/care-partner-support | 1 |
| tpl_27 | Search Results — group 28 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/search-results | 1 |
| tpl_28 | Care Partner Support — group 29 | Same structural layout across 1 page(s) in the crawl. | https://www.epkinly.com/2l-fl/care-partner-support | 1 |
