# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **58** URLs; **36** layout templates were identified (signature (DOM fingerprint)). Highest-traffic templates by page count include **Watch — group 12**, **For Your Patients — group 23**, **For Your Practice — group 17**. **130** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T16:15:00.339Z
- **Website**: https://www.identifyepi.com/
- **Total Pages Analyzed**: 58
- **Total Templates Identified**: 36
- **Total Components Identified**: 130
- **Grouping**: signature (DOM fingerprint)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.IDENTIFYEPI.COM TEMPLATES                                                │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Watch — group 12                     │    │ For Your Patients — group 23         │    │ For Your Practice — group 17         │
│ (9 pages)                            │    │ (5 pages)                            │    │ (4 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Section {Unmapped}            │    │ • Hero Section {Unmapped}            │
│ • Video Playlist {Unmapped}          │    │ • Video Playlist                     │    │ • Video Introduction {Unmapped}      │
│ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Underlying Conditions — group 4      │    │ Exocrine Pancreatic Insufficiency S… │    │ Moving Forward With Epi Treatment T… │
│ (2 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Header                     │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Introduction Paragraph {Unmapped}  │    │ • Hero Section                       │    │ • Transcript Content {Unmapped}      │
│ • (+4 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 1                  │    │ Search Results — group 2             │    │ Epi Symptoms — group 3               │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Header                     │    │ • Primary Header                     │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section {Unmapped}            │
│ • Main Navigation                    │    │ • Hero Section                       │    │ • Symptoms Overview {Unmapped}       │
│ • (+6 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+7 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Epi Videos — group 5                 │    │ What Is Epi Transcript — group 6     │    │ Frequently Asked Questions — group 7 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Video Grid {Unmapped}              │    │ • Video Transcript Content {Unmappe… │    │ • FAQ Accordion                      │
│ • (+2 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 8                  │    │ Exocrine Pancreatic Insufficiency D… │    │ What Is Epi — group 10               │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │
│ • Main Header                        │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Primary Navigation                 │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Hero Section                       │    │ • Introduction Text {Unmapped}       │    │ • Introduction Content {Unmapped}    │
│ • (+6 more — see Blocks mapped per … │    │ • (+9 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Talking To Your Doctor — group 13    │    │ Pancreatic Insufficiency Symptoms —… │    │ Search Results — group 15            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Search Bar {Unmapped}              │
│ • Introduction Content {Unmapped}    │    │ • Introduction Column {Unmapped}     │    │ • Hero Section {Unmapped}            │
│ • (+6 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Epi Treatment — group 16             │    │ Epi Clinical Diagnosis — group 18    │    │ Hcp — group 19                       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Global Utility Navigation {Unmapp… │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Header                     │    │ • Primary Header                     │    │ • Primary Header {Unmapped}          │
│ • Primary Navigation                 │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Introduction Columns               │    │ • Hero Section                       │
│ • (+7 more — see Blocks mapped per … │    │ • (+8 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Find An Epi Doctor — group 20        │    │ Site Map — group 22                  │    │ Epi Stories — group 24               │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Utility Navigation {Unmapped}      │    │ • Utility Strip {Unmapped}           │
│ • Primary Header {Unmapped}          │    │ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Practice Videos                    │
│ • (+7 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Pancreatic Disease Resources — grou… │    │ Recognizing Epi Symptoms Transcript… │    │ Epi Underlying Conditions — group 27 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Introduction Text {Unmapped}       │    │ • Video Transcript {Unmapped}        │    │ • Etiology Introduction {Unmapped}   │
│ • (+4 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.IDENTIFYEPI.COM — SUB-TEMPLATES TEMPLATES                                │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Sitemap — group 28                   │    │ Diet And Lifestyle — group 29        │    │ Epi Resources — group 30             │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Navigation {Unmapp… │    │ • Utility Navigation                 │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │    │ • Primary Header {Unmapped}          │
│ • Header Logo {Unmapped}             │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Search Bar {Unmapped}              │    │ • Diet and Lifestyle Intro           │    │ • Hero Section                       │
│ • (+5 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Epi Symptoms — group 31              │    │ Digestive Pancreatic Enzymes — grou… │    │ Treating Epi With Pert — group 33    │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Nav                 │    │ • Utility Navigation {Unmapped}      │    │ • Utility Navigation {Unmapped}      │
│ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Hero Section                       │
│ • Symptoms Overview                  │    │ • Pancreas Roles Section {Unmapped}  │    │ • Introduction Content {Unmapped}    │
│ • (+6 more — see Blocks mapped per … │    │ • (+4 more — see Blocks mapped per … │    │ • (+6 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Epi Diagnosis Challenges — group 34  │    │ Aemform Iframe — group 35            │    │ Site Map — group 36                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • —                                  │    │ • Header Utility Nav {Unmapped}      │
│ • Primary Header                     │    │ • —                                  │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • —                                  │    │ • Hero Section {Unmapped}            │
│ • Below Header Introduction {Unmapp… │    │ • —                                  │    │ • Site Map Content {Unmapped}        │
│ • (+6 more — see Blocks mapped per … │    │ • —                                  │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Watch — group 12 (`tpl_11`) — 9 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Hero Section {Unmapped}
- Video Playlist {Unmapped}
- Individual Videos {Unmapped}
- Resource CTAs {Unmapped}
- Footer
- Back to Top {Unmapped}

### For Your Patients — group 23 (`tpl_22`) — 5 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Video Playlist
- Individual Videos
- Video Highlights
- Call-to-Action Section {Unmapped}
- Footer Links

### For Your Practice — group 17 (`tpl_16`) — 4 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Video Introduction {Unmapped}
- Main Video Player
- Individual Video Players
- Patient Videos Section {Unmapped}
- Video Thumbnails {Unmapped}
- Call to Action Section {Unmapped}
- Footer

### Underlying Conditions — group 4 (`tpl_3`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Paragraph {Unmapped}
- Underlying Conditions Accordion
- Highlight Section {Unmapped}
- Call to Action Section {Unmapped}
- Footer

### Exocrine Pancreatic Insufficiency Symptoms — group 11 (`tpl_10`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Hero Section
- Symptom Checker Introduction {Unmapped}
- Symptom Checker Tool {Unmapped}
- Next Steps {Unmapped}
- Reference Sources {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### Moving Forward With Epi Treatment Transcript — group 21 (`tpl_20`) — 2 pages

- Utility Navigation {Unmapped}
- Primary Header
- Hero Section
- Transcript Content {Unmapped}
- Footer Links
- Back to Top Button {Unmapped}
- Advertising Choices Modal
- Healthcare Professional Warning Modal

### Page layout group 1 (`tpl_0`) — 1 pages

- Utility Navigation
- Primary Header
- Hero Section
- Main Navigation
- Symptoms Icons Grid
- Content Columns
- References Section
- Footer
- Back to Top Button {Unmapped}
- Cookie Consent Modal

### Search Results — group 2 (`tpl_1`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Header
- Primary Navigation {Unmapped}
- Hero Section
- Search Results {Unmapped}
- Footer
- Back to Top Button {Unmapped}
- Cookie Consent Modal {Unmapped}
- Healthcare Professional Modal {Unmapped}

### Epi Symptoms — group 3 (`tpl_2`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Symptoms Overview {Unmapped}
- Symptoms Details {Unmapped}
- Symptoms Advice {Unmapped}
- Video Section
- Symptom Checker CTA {Unmapped}
- Additional Resources {Unmapped}
- References Section {Unmapped}
- Footer

### Epi Videos — group 5 (`tpl_4`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Video Grid {Unmapped}
- CTA Blocks {Unmapped}
- Footer Links {Unmapped}

### What Is Epi Transcript — group 6 (`tpl_5`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Video Transcript Content {Unmapped}
- Footer Links
- Footer Legal Text
- Back to Top Button {Unmapped}
- Advertising Choices Modal
- Healthcare Professional Warning Modal

### Frequently Asked Questions — group 7 (`tpl_6`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- FAQ Accordion
- CTA - Get Updates {Unmapped}
- EPI Resources Section {Unmapped}

### Page layout group 8 (`tpl_7`) — 1 pages

- Utility Navigation
- Main Header
- Primary Navigation
- Hero Section
- Main Heading {Unmapped}
- Sign-Up Form
- Footer Links
- Footer Legal
- Back to Top Button {Unmapped}
- Cookie Settings

### Exocrine Pancreatic Insufficiency Diagnosis — group 9 (`tpl_8`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Text {Unmapped}
- Symptoms Checklist {Unmapped}
- Specialist Information {Unmapped}
- EPI Tests Overview {Unmapped}
- Test Details {Unmapped}
- Treatment Information {Unmapped}
- Additional Resources {Unmapped}
- References Section {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### What Is Epi — group 10 (`tpl_9`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Content {Unmapped}
- PERT Information {Unmapped}
- Pancreas Function {Unmapped}
- Enzymes Information {Unmapped}
- EPI Causes {Unmapped}
- Digestion Carousel
- EPI Resources {Unmapped}

### Talking To Your Doctor — group 13 (`tpl_12`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Content {Unmapped}
- Video Section 1
- Video Section 2
- Symptoms CTA {Unmapped}
- Telemedicine Tips {Unmapped}
- Resources CTA {Unmapped}
- Footer

### Pancreatic Insufficiency Symptoms — group 14 (`tpl_13`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Column {Unmapped}
- Symptoms Highlight {Unmapped}
- Clinical Relevance Section {Unmapped}
- Spotlight Section {Unmapped}
- Footer Form

### Search Results — group 15 (`tpl_14`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Search Bar {Unmapped}
- Hero Section {Unmapped}
- Search Results {Unmapped}
- Footer Navigation {Unmapped}
- Footer Legal Text {Unmapped}
- Back to Top Button {Unmapped}

### Epi Treatment — group 16 (`tpl_15`) — 1 pages

- Utility Navigation
- Primary Header
- Primary Navigation
- Hero Section
- Introduction Section {Unmapped}
- Video Section
- PERT Explanation {Unmapped}
- PERT Guidelines {Unmapped}
- Support Section {Unmapped}
- References Section {Unmapped}
- Footer

### Epi Clinical Diagnosis — group 18 (`tpl_17`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header
- Hero Section
- Introduction Columns
- Symptoms Columns
- Signs and Symptoms {Unmapped}
- Underlying Conditions {Unmapped}
- Video Spotlight
- Patient Questions {Unmapped}
- ICD Code Section {Unmapped}
- Diagnostic Tests {Unmapped}
- Footer References

### Hcp — group 19 (`tpl_18`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Study Highlight {Unmapped}
- Resources Section {Unmapped}
- Form Embed
- References Section {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### Find An Epi Doctor — group 20 (`tpl_19`) — 1 pages

- Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Columns
- Doctor Locator Tool {Unmapped}
- Additional Information {Unmapped}
- Footer Links
- Footer Legal Information {Unmapped}
- Back to Top Button {Unmapped}
- Cookie Consent Modal {Unmapped}

### Site Map — group 22 (`tpl_21`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Site Map Links {Unmapped}
- Footer
- Back to Top {Unmapped}

### Epi Stories — group 24 (`tpl_23`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Practice Videos
- Patient Videos
- Bottom Call-to-Action {Unmapped}
- Footer Links

### Pancreatic Disease Resources — group 25 (`tpl_24`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Text {Unmapped}
- Sign-Up Section {Unmapped}
- General Resources {Unmapped}
- Pancreatic Disease Resources {Unmapped}
- Footer

### Recognizing Epi Symptoms Transcript — group 26 (`tpl_25`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Video Transcript {Unmapped}
- Footer Links
- Footer Legal {Unmapped}
- Back to Top Button {Unmapped}

### Epi Underlying Conditions — group 27 (`tpl_26`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Etiology Introduction {Unmapped}
- Etiology Causes {Unmapped}
- Accordion Conditions

### Sitemap — group 28 (`tpl_27`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Header Logo {Unmapped}
- Search Bar {Unmapped}
- Footer Links
- Footer Legal Text
- Back to Top Button {Unmapped}
- Advertising Choices Modal
- Healthcare Professional Warning Modal

### Diet And Lifestyle — group 29 (`tpl_28`) — 1 pages

- Utility Navigation
- Primary Navigation
- Hero Section
- Diet and Lifestyle Intro
- Digestion Section
- Diet Tips
- Resources Call-to-Actions
- Footer

### Epi Resources — group 30 (`tpl_29`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Header {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introductory Content {Unmapped}
- CF Commitment Section {Unmapped}
- Footer

### Epi Symptoms — group 31 (`tpl_30`) — 1 pages

- Global Utility Nav
- Primary Navigation
- Hero Section
- Symptoms Overview
- Video Section
- Symptom Checker CTA
- Additional Resources
- References Section
- Footer
- Back to Top Button

### Digestive Pancreatic Enzymes — group 32 (`tpl_31`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Pancreas Roles Section {Unmapped}
- Pancreatic Enzymes Section {Unmapped}
- Enzyme Secretion Section {Unmapped}
- Call-to-Action Section {Unmapped}
- Footer

### Treating Epi With Pert — group 33 (`tpl_32`) — 1 pages

- Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Content {Unmapped}
- Management Plan {Unmapped}
- Standard of Care {Unmapped}
- Dosing Guidelines {Unmapped}
- Adjustment Guidelines {Unmapped}
- References Section {Unmapped}
- Footer Links

### Epi Diagnosis Challenges — group 34 (`tpl_33`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header
- Hero Section
- Below Header Introduction {Unmapped}
- Challenge Factors {Unmapped}
- Spotlight Video
- Symptom Timeline {Unmapped}
- Telemedicine Video
- Footer References {Unmapped}
- Bottom CTA {Unmapped}

### Aemform Iframe — group 35 (`tpl_34`) — 1 pages

- —

### Site Map — group 36 (`tpl_35`) — 1 pages

- Header Utility Nav {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Site Map Content {Unmapped}
- Footer Links
- Footer Legal Text
- Back to Top Button {Unmapped}
- Advertising Choices Modal
- HCP Warning Modal


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌───────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                             │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├───────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Hero Section                          │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │
│ Primary Navigation {Unmapped}         │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │
│ Footer                                │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │ ❌   │ ✅   │
│ Back to Top Button {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │ ✅   │
│ Utility Navigation {Unmapped}         │ ❌   │ ✅   │ ✅   │ ❌   │ ✅   │ ✅   │ ❌   │
│ Global Utility Navigation {Unmapped}  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Footer Links                          │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Hero Section {Unmapped}               │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Primary Header                        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ✅   │
│ Primary Header {Unmapped}             │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ References Section {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Advertising Choices Modal             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │
│ Primary Navigation                    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Utility Navigation                    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
└───────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T36 omitted from matrix width; see appendix.*


### Template-specific components

```
┌───────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                             │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├───────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Accordion Conditions                  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Additional Information {Unmapped}     │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Additional Resources                  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Adjustment Guidelines {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Back to Top Button                    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Below Header Introduction {Unmapped}  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Bottom Call-to-Action {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Bottom CTA {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ CF Commitment Section {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Challenge Factors {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Clinical Relevance Section {Unmapped} │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Content Columns                       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Cookie Consent Modal                  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Cookie Settings                       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└───────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T36 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Watch — group 12 (9 pgs)                                                                          │
│ • For Your Patients — group 23 (5 pgs)                                                              │
│ • For Your Practice — group 17 (4 pgs)                                                              │
│ • Underlying Conditions — group 4 (2 pgs)                                                           │
│ • Exocrine Pancreatic Insufficiency Symptoms — group 11 (2 pgs)                                     │
│ • Moving Forward With Epi Treatment Transcript — group 21 (2 pgs)                                   │
│ • Page layout group 1 (1 pgs)                                                                       │
│ • Search Results — group 2 (1 pgs)                                                                  │
│ • Epi Symptoms — group 3 (1 pgs)                                                                    │
│ • Epi Videos — group 5 (1 pgs)                                                                      │
│ • What Is Epi Transcript — group 6 (1 pgs)                                                          │
│ • Frequently Asked Questions — group 7 (1 pgs)                                                      │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Page layout group 8 (1 pgs)                                                                       │
│ • Exocrine Pancreatic Insufficiency Diagnosis — group 9 (1 pgs)                                     │
│ • What Is Epi — group 10 (1 pgs)                                                                    │
│ • Talking To Your Doctor — group 13 (1 pgs)                                                         │
│ • Pancreatic Insufficiency Symptoms — group 14 (1 pgs)                                              │
│ • Search Results — group 15 (1 pgs)                                                                 │
│ • Epi Treatment — group 16 (1 pgs)                                                                  │
│ • Epi Clinical Diagnosis — group 18 (1 pgs)                                                         │
│ • Hcp — group 19 (1 pgs)                                                                            │
│ • Find An Epi Doctor — group 20 (1 pgs)                                                             │
│ • Site Map — group 22 (1 pgs)                                                                       │
│ • Epi Stories — group 24 (1 pgs)                                                                    │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Pancreatic Disease Resources — group 25 (1 pgs)                                                   │
│ • Recognizing Epi Symptoms Transcript — group 26 (1 pgs)                                            │
│ • Epi Underlying Conditions — group 27 (1 pgs)                                                      │
│ • Sitemap — group 28 (1 pgs)                                                                        │
│ • Diet And Lifestyle — group 29 (1 pgs)                                                             │
│ • Epi Resources — group 30 (1 pgs)                                                                  │
│ • Epi Symptoms — group 31 (1 pgs)                                                                   │
│ • Digestive Pancreatic Enzymes — group 32 (1 pgs)                                                   │
│ • Treating Epi With Pert — group 33 (1 pgs)                                                         │
│ • Epi Diagnosis Challenges — group 34 (1 pgs)                                                       │
│ • Aemform Iframe — group 35 (1 pgs)                                                                 │
│ • Site Map — group 36 (1 pgs)                                                                       │
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
| tpl_0 | Page layout group 1 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/ | 1 |
| tpl_1 | Search Results — group 2 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/search-results | 1 |
| tpl_2 | Epi Symptoms — group 3 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/what-is-epi/epi-symptoms | 1 |
| tpl_3 | Underlying Conditions — group 4 | Same structural layout across 2 page(s) in the crawl. | https://www.identifyepi.com/what-is-epi/underlying-conditions, https://www.identifyepi.com/what-is-epi/associated-conditions | 2 |
| tpl_4 | Epi Videos — group 5 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/epi-videos | 1 |
| tpl_5 | What Is Epi Transcript — group 6 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/epi-videos/what-is-epi-transcript | 1 |
| tpl_6 | Frequently Asked Questions — group 7 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/frequently-asked-questions | 1 |
| tpl_7 | Page layout group 8 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/exocrine-pancreatic-insufficiency-information | 1 |
| tpl_8 | Exocrine Pancreatic Insufficiency Diagnosis — group 9 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/what-is-epi/exocrine-pancreatic-insufficiency-diagnosis | 1 |
| tpl_9 | What Is Epi — group 10 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/what-is-epi | 1 |
| tpl_10 | Exocrine Pancreatic Insufficiency Symptoms — group 11 | Same structural layout across 2 page(s) in the crawl. | https://www.identifyepi.com/exocrine-pancreatic-insufficiency-symptoms, https://www.identifyepi.com/identifyepi-symptom-checker | 2 |
| tpl_11 | Watch — group 12 | Same structural layout across 9 page(s) in the crawl. | https://www.identifyepi.com/epi-videos/watch?ftvid=6270803495001, https://www.identifyepi.com/epi-videos/watch?ftvid=6282593880001, https://www.identifyepi.com/epi-videos/watch | 9 |
| tpl_12 | Talking To Your Doctor — group 13 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/talking-to-your-doctor | 1 |
| tpl_13 | Pancreatic Insufficiency Symptoms — group 14 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/hcp/pancreatic-insufficiency-symptoms | 1 |
| tpl_14 | Search Results — group 15 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/hcp/search-results | 1 |
| tpl_15 | Epi Treatment — group 16 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/epi-treatment | 1 |
| tpl_16 | For Your Practice — group 17 | Same structural layout across 4 page(s) in the crawl. | https://www.identifyepi.com/hcp/epi-stories/for-your-practice?ftvid=6258802051001, https://www.identifyepi.com/hcp/epi-stories/for-your-practice?ftvid=6258803133001, https://www.identifyepi.com/hcp/epi-stories/for-your-practice | 4 |
| tpl_17 | Epi Clinical Diagnosis — group 18 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/hcp/epi-clinical-diagnosis | 1 |
| tpl_18 | Hcp — group 19 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/hcp | 1 |
| tpl_19 | Find An Epi Doctor — group 20 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/find-an-epi-doctor | 1 |
| tpl_20 | Moving Forward With Epi Treatment Transcript — group 21 | Same structural layout across 2 page(s) in the crawl. | https://www.identifyepi.com/epi-videos/moving-forward-with-epi-treatment-transcript, https://www.identifyepi.com/epi-videos/opening-up-to-your-doctor-transcript | 2 |
| tpl_21 | Site Map — group 22 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/hcp/site-map | 1 |
| tpl_22 | For Your Patients — group 23 | Same structural layout across 5 page(s) in the crawl. | https://www.identifyepi.com/hcp/epi-stories/for-your-patients?ftvid=6258803495001, https://www.identifyepi.com/hcp/epi-stories/for-your-patients, https://www.identifyepi.com/hcp/epi-stories/for-your-patients?ftvid=6258803767001 | 5 |
| tpl_23 | Epi Stories — group 24 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/hcp/epi-stories | 1 |
| tpl_24 | Pancreatic Disease Resources — group 25 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/pancreatic-disease-resources | 1 |
| tpl_25 | Recognizing Epi Symptoms Transcript — group 26 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/epi-videos/recognizing-epi-symptoms-transcript | 1 |
| tpl_26 | Epi Underlying Conditions — group 27 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/hcp/epi-underlying-conditions | 1 |
| tpl_27 | Sitemap — group 28 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/sitemap | 1 |
| tpl_28 | Diet And Lifestyle — group 29 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/diet-and-lifestyle | 1 |
| tpl_29 | Epi Resources — group 30 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/hcp/epi-resources | 1 |
| tpl_30 | Epi Symptoms — group 31 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/epi-symptoms | 1 |
| tpl_31 | Digestive Pancreatic Enzymes — group 32 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/hcp/digestive-pancreatic-enzymes | 1 |
| tpl_32 | Treating Epi With Pert — group 33 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/hcp/treating-epi-with-pert | 1 |
| tpl_33 | Epi Diagnosis Challenges — group 34 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/hcp/epi-diagnosis-challenges | 1 |
| tpl_34 | Aemform Iframe — group 35 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/content/identifyepi/en-us/exocrine-pancreatic-insufficiency-symptoms/jcr:content/contentpar/aemform.iframe.html?dataRef=&amp;wcmmode=DISABLED | 1 |
| tpl_35 | Site Map — group 36 | Same structural layout across 1 page(s) in the crawl. | https://www.identifyepi.com/site-map | 1 |
