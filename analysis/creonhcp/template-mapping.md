# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **71** URLs; **34** layout templates were identified (signature (DOM fingerprint)). Highest-traffic templates by page count include **Dosing Administration — group 4**, **Dosing Cp Py Patient Transcript — group 16**, **Creon Patient Support — group 34**. **19** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T12:31:53.202Z
- **Website**: https://www.creonhcp.com/
- **Total Pages Analyzed**: 71
- **Total Templates Identified**: 34
- **Total Components Identified**: 19
- **Grouping**: signature (DOM fingerprint)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.CREONHCP.COM TEMPLATES                                                   │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Dosing Administration — group 4      │    │ Dosing Cp Py Patient Transcript — g… │    │ Creon Patient Support — group 34     │
│ (3 pages)                            │    │ (3 pages)                            │    │ (3 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │    │ • Global utility bar {Unmapped}      │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • Primary site header and navigatio… │
│ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │    │ • content {Unmapped}                 │
│ • main region 2 {Unmapped}           │    │ • main region 2 {Unmapped}           │    │ • Site footer {Unmapped}             │
│ • (+3 more — see Blocks mapped per … │    │ • Site footer {Unmapped}             │    │ • Cookie / consent entry {Unmapped}  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Dosing 160 315lb Patients Transcrip… │    │ Formulary Lookup — group 9           │    │ Symptoms Features Epi Transcript — … │
│ (2 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • Site footer {Unmapped}             │    │ • Site footer {Unmapped}             │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 1                  │    │ Symptoms Of Epi — group 2            │    │ Managing Epi — group 3               │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │
│ • main region 2 {Unmapped}           │    │ • main region 2 {Unmapped}           │    │ • Site footer {Unmapped}             │
│ • Site footer {Unmapped}             │    │ • Site footer {Unmapped}             │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Understanding Epi — group 5          │    │ Patient Support — group 6            │    │ Site Map — group 8                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │    │ • Site footer {Unmapped}             │
│ • main region 2 {Unmapped}           │    │ • Site footer {Unmapped}             │    │ • —                                  │
│ • (+3 more — see Blocks mapped per … │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Sitemap — group 10                   │    │ Epi Differential Diagnosis Transcri… │    │ Mechanism Of Action — group 12       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │
│ • Site footer {Unmapped}             │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • —                                  │    │ • Site footer {Unmapped}             │    │ • main region 1 {Unmapped}           │
│ • —                                  │    │ • —                                  │    │ • Carousel / spotlight {Unmapped}    │
│ • —                                  │    │ • —                                  │    │ • Site footer {Unmapped}             │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Access Coverage — group 13           │    │ Resources — group 15                 │    │ Search Results — group 17            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • search results coveo {Unmapped}    │
│ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │    │ • Site footer {Unmapped}             │
│ • main region 2 {Unmapped}           │    │ • Site footer {Unmapped}             │    │ • —                                  │
│ • (+2 more — see Blocks mapped per … │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Cp Or Pancreatectomy — group 18      │    │ Safety Data — group 19               │    │ Discussion Guide — group 20          │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │    │ • main region 1 {Unmapped}           │    │ • Site footer {Unmapped}             │
│ • main region 2 {Unmapped}           │    │ • main region 2 {Unmapped}           │    │ • —                                  │
│ • (+8 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Diagnosing Epi — group 21            │    │ Underlying Conditions — group 22     │    │ Efficacy — group 23                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │    │ • Site footer {Unmapped}             │    │ • main region 1 {Unmapped}           │
│ • main region 2 {Unmapped}           │    │ • —                                  │    │ • main region 2 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • —                                  │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ About Creon — group 24               │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Site header {Unmapped}             │
│ • main region 0 {Unmapped}           │
│ • columns {Unmapped}                 │
│ • main region 2 {Unmapped}           │
│ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.CREONHCP.COM — SUB-TEMPLATES TEMPLATES                                   │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Dosing Calculator — group 25         │    │ Contact A Rep — group 26             │    │ Collaborative Epi Management Transc… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • main region 1 {Unmapped}           │    │ • Site footer {Unmapped}             │    │ • Site footer {Unmapped}             │
│ • main region 2 {Unmapped}           │    │ • —                                  │    │ • —                                  │
│ • (+3 more — see Blocks mapped per … │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Optimizing Epi Management Transcrip… │    │ Dosing Epi — group 29                │    │ Creon Starting Dose — group 30       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • main region 1 {Unmapped}           │    │ • Site footer {Unmapped}             │
│ • —                                  │    │ • main region 2 {Unmapped}           │    │ • —                                  │
│ • —                                  │    │ • Site footer {Unmapped}             │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Treatment Tracker — group 31         │    │ Communication Diagnosing Epi Transc… │    │ Challenges To Diagnosis — group 33   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │    │ • Site header {Unmapped}             │
│ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │    │ • main region 0 {Unmapped}           │
│ • Site footer {Unmapped}             │    │ • Site footer {Unmapped}             │    │ • main region 1 {Unmapped}           │
│ • —                                  │    │ • —                                  │    │ • main region 2 {Unmapped}           │
│ • —                                  │    │ • —                                  │    │ • Site footer {Unmapped}             │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Dosing Administration — group 4 (`tpl_3`) — 3 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- Site footer {Unmapped}

### Dosing Cp Py Patient Transcript — group 16 (`tpl_15`) — 3 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- Site footer {Unmapped}

### Creon Patient Support — group 34 (`tpl_33`) — 3 pages

- Global utility bar {Unmapped}
- Primary site header and navigation {Unmapped}
- content {Unmapped}
- Site footer {Unmapped}
- Cookie / consent entry {Unmapped}

### Dosing 160 315lb Patients Transcript — group 7 (`tpl_6`) — 2 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Formulary Lookup — group 9 (`tpl_8`) — 2 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Symptoms Features Epi Transcript — group 14 (`tpl_13`) — 2 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Page layout group 1 (`tpl_0`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- Site footer {Unmapped}

### Symptoms Of Epi — group 2 (`tpl_1`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- Site footer {Unmapped}

### Managing Epi — group 3 (`tpl_2`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Site footer {Unmapped}

### Understanding Epi — group 5 (`tpl_4`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- Site footer {Unmapped}

### Patient Support — group 6 (`tpl_5`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Site footer {Unmapped}

### Site Map — group 8 (`tpl_7`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Sitemap — group 10 (`tpl_9`) — 1 pages

- Site header {Unmapped}
- Site footer {Unmapped}

### Epi Differential Diagnosis Transcript — group 11 (`tpl_10`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Mechanism Of Action — group 12 (`tpl_11`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Carousel / spotlight {Unmapped}
- Site footer {Unmapped}

### Access Coverage — group 13 (`tpl_12`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- Site footer {Unmapped}

### Resources — group 15 (`tpl_14`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- Site footer {Unmapped}

### Search Results — group 17 (`tpl_16`) — 1 pages

- Site header {Unmapped}
- search results coveo {Unmapped}
- Site footer {Unmapped}

### Cp Or Pancreatectomy — group 18 (`tpl_17`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- main region 5 {Unmapped}
- main region 6 {Unmapped}
- main region 7 {Unmapped}
- main region 8 {Unmapped}
- main region 9 {Unmapped}
- Site footer {Unmapped}

### Safety Data — group 19 (`tpl_18`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- Site footer {Unmapped}

### Discussion Guide — group 20 (`tpl_19`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Diagnosing Epi — group 21 (`tpl_20`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- Site footer {Unmapped}

### Underlying Conditions — group 22 (`tpl_21`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Efficacy — group 23 (`tpl_22`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- Site footer {Unmapped}

### About Creon — group 24 (`tpl_23`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- columns {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- main region 5 {Unmapped}
- Site footer {Unmapped}

### Dosing Calculator — group 25 (`tpl_24`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- main region 3 {Unmapped}
- main region 4 {Unmapped}
- Site footer {Unmapped}

### Contact A Rep — group 26 (`tpl_25`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Collaborative Epi Management Transcript — group 27 (`tpl_26`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Optimizing Epi Management Transcript — group 28 (`tpl_27`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Dosing Epi — group 29 (`tpl_28`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- Site footer {Unmapped}

### Creon Starting Dose — group 30 (`tpl_29`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Treatment Tracker — group 31 (`tpl_30`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Communication Diagnosing Epi Transcript — group 32 (`tpl_31`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- Site footer {Unmapped}

### Challenges To Diagnosis — group 33 (`tpl_32`) — 1 pages

- Site header {Unmapped}
- main region 0 {Unmapped}
- main region 1 {Unmapped}
- main region 2 {Unmapped}
- Site footer {Unmapped}


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                    │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Site footer {Unmapped}       │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Site header {Unmapped}       │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │
│ main region 0 {Unmapped}     │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │
│ main region 1 {Unmapped}     │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ main region 2 {Unmapped}     │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ main region 3 {Unmapped}     │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ main region 4 {Unmapped}     │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ main region 5 {Unmapped}     │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T34 omitted from matrix width; see appendix.*


### Template-specific components

```
┌───────────────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                                     │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├───────────────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Carousel / spotlight {Unmapped}               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ columns {Unmapped}                            │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ content {Unmapped}                            │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Cookie / consent entry {Unmapped}             │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global utility bar {Unmapped}                 │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ main region 6 {Unmapped}                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ main region 7 {Unmapped}                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ main region 8 {Unmapped}                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ main region 9 {Unmapped}                      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Primary site header and navigation {Unmapped} │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ search results coveo {Unmapped}               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└───────────────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T34 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Dosing Administration — group 4 (3 pgs)                                                           │
│ • Dosing Cp Py Patient Transcript — group 16 (3 pgs)                                                │
│ • Creon Patient Support — group 34 (3 pgs)                                                          │
│ • Dosing 160 315lb Patients Transcript — group 7 (2 pgs)                                            │
│ • Formulary Lookup — group 9 (2 pgs)                                                                │
│ • Symptoms Features Epi Transcript — group 14 (2 pgs)                                               │
│ • Page layout group 1 (1 pgs)                                                                       │
│ • Symptoms Of Epi — group 2 (1 pgs)                                                                 │
│ • Managing Epi — group 3 (1 pgs)                                                                    │
│ • Understanding Epi — group 5 (1 pgs)                                                               │
│ • Patient Support — group 6 (1 pgs)                                                                 │
│ • Site Map — group 8 (1 pgs)                                                                        │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Sitemap — group 10 (1 pgs)                                                                        │
│ • Epi Differential Diagnosis Transcript — group 11 (1 pgs)                                          │
│ • Mechanism Of Action — group 12 (1 pgs)                                                            │
│ • Access Coverage — group 13 (1 pgs)                                                                │
│ • Resources — group 15 (1 pgs)                                                                      │
│ • Search Results — group 17 (1 pgs)                                                                 │
│ • Cp Or Pancreatectomy — group 18 (1 pgs)                                                           │
│ • Safety Data — group 19 (1 pgs)                                                                    │
│ • Discussion Guide — group 20 (1 pgs)                                                               │
│ • Diagnosing Epi — group 21 (1 pgs)                                                                 │
│ • Underlying Conditions — group 22 (1 pgs)                                                          │
│ • Efficacy — group 23 (1 pgs)                                                                       │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • About Creon — group 24 (1 pgs)                                                                    │
│ • Dosing Calculator — group 25 (1 pgs)                                                              │
│ • Contact A Rep — group 26 (1 pgs)                                                                  │
│ • Collaborative Epi Management Transcript — group 27 (1 pgs)                                        │
│ • Optimizing Epi Management Transcript — group 28 (1 pgs)                                           │
│ • Dosing Epi — group 29 (1 pgs)                                                                     │
│ • Creon Starting Dose — group 30 (1 pgs)                                                            │
│ • Treatment Tracker — group 31 (1 pgs)                                                              │
│ • Communication Diagnosing Epi Transcript — group 32 (1 pgs)                                        │
│ • Challenges To Diagnosis — group 33 (1 pgs)                                                        │
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
| tpl_0 | Page layout group 1 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/ | 1 |
| tpl_1 | Symptoms Of Epi — group 2 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/symptoms-of-epi | 1 |
| tpl_2 | Managing Epi — group 3 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/managing-epi | 1 |
| tpl_3 | Dosing Administration — group 4 | Same structural layout across 3 page(s) in the crawl. | https://www.creonhcp.com/dosing-administration, https://www.creonhcp.com/cystic-fibrosis-dosing, https://www.creonhcp.com/dosing-other-epi-conditions | 3 |
| tpl_4 | Understanding Epi — group 5 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/understanding-epi | 1 |
| tpl_5 | Patient Support — group 6 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/patient-support | 1 |
| tpl_6 | Dosing 160 315lb Patients Transcript — group 7 | Same structural layout across 2 page(s) in the crawl. | https://www.creonhcp.com/creon-videos/dosing-160-315lb-patients-transcript, https://www.creonhcp.com/creon-videos/dosing-110-160lb-patients-transcript | 2 |
| tpl_7 | Site Map — group 8 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/site-map | 1 |
| tpl_8 | Formulary Lookup — group 9 | Same structural layout across 2 page(s) in the crawl. | https://www.creonhcp.com/formulary-lookup, https://www.creonhcp.com/access-coverage/formulary-lookup | 2 |
| tpl_9 | Sitemap — group 10 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/sitemap | 1 |
| tpl_10 | Epi Differential Diagnosis Transcript — group 11 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/creon-videos/epi-differential-diagnosis-transcript | 1 |
| tpl_11 | Mechanism Of Action — group 12 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/mechanism-of-action | 1 |
| tpl_12 | Access Coverage — group 13 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/access-coverage | 1 |
| tpl_13 | Symptoms Features Epi Transcript — group 14 | Same structural layout across 2 page(s) in the crawl. | https://www.creonhcp.com/creon-videos/symptoms-features-epi-transcript, https://www.creonhcp.com/creon-videos/why-creon-transcript | 2 |
| tpl_14 | Resources — group 15 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/resources | 1 |
| tpl_15 | Dosing Cp Py Patient Transcript — group 16 | Same structural layout across 3 page(s) in the crawl. | https://www.creonhcp.com/creon-videos/dosing-cp-py-patient-transcript, https://www.creonhcp.com/creon-videos/tips-newly-diagnosed-transcript, https://www.creonhcp.com/creon-videos | 3 |
| tpl_16 | Search Results — group 17 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/search-results | 1 |
| tpl_17 | Cp Or Pancreatectomy — group 18 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/cp-or-pancreatectomy | 1 |
| tpl_18 | Safety Data — group 19 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/safety-data | 1 |
| tpl_19 | Discussion Guide — group 20 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/discussion-guide | 1 |
| tpl_20 | Diagnosing Epi — group 21 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/diagnosing-epi | 1 |
| tpl_21 | Underlying Conditions — group 22 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/underlying-conditions | 1 |
| tpl_22 | Efficacy — group 23 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/efficacy | 1 |
| tpl_23 | About Creon — group 24 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/about-creon | 1 |
| tpl_24 | Dosing Calculator — group 25 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/dosing-calculator | 1 |
| tpl_25 | Contact A Rep — group 26 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/contact-a-rep | 1 |
| tpl_26 | Collaborative Epi Management Transcript — group 27 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/creon-videos/collaborative-epi-management-transcript | 1 |
| tpl_27 | Optimizing Epi Management Transcript — group 28 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/creon-videos/optimizing-epi-management-transcript | 1 |
| tpl_28 | Dosing Epi — group 29 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/dosing-epi | 1 |
| tpl_29 | Creon Starting Dose — group 30 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/creon-starting-dose | 1 |
| tpl_30 | Treatment Tracker — group 31 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/treatment-tracker | 1 |
| tpl_31 | Communication Diagnosing Epi Transcript — group 32 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/creon-videos/communication-diagnosing-epi-transcript | 1 |
| tpl_32 | Challenges To Diagnosis — group 33 | Same structural layout across 1 page(s) in the crawl. | https://www.creonhcp.com/challenges-to-diagnosis | 1 |
| tpl_33 | Creon Patient Support — group 34 | Same structural layout across 3 page(s) in the crawl. | https://www.creonhcp.com/creon-patient-support, https://www.creonhcp.com/on-course, https://www.creonhcp.com/cfcareforward | 3 |
