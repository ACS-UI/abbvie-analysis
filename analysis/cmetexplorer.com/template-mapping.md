# Website Analysis Summary Report

## Executive Summary
Automated crawl recorded **355** URLs; **313** layout templates were identified (signature (DOM fingerprint)). Highest-traffic templates by page count include **Abbvie Foundation — group 115**, **Our Leaders — group 10**, **Page layout group 2**. **162** mapped UI block(s) were aligned to the Adobe AEM block catalog (see matrices and `block-mapping.csv`).

## Project Information
- **Analysis Date**: 2026-04-13T18:31:31.294Z
- **Website**: https://www.abbvie.com/science/areas-of-focus/oncology.html
- **Total Pages Analyzed**: 355
- **Total Templates Identified**: 313
- **Total Components Identified**: 162
- **Grouping**: signature (DOM fingerprint)

# Website Template Mapping Diagram

## Template Hierarchy and Component Relationships

```
┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.ABBVIE.COM TEMPLATES                                                     │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Abbvie Foundation — group 115        │    │ Our Leaders — group 10               │    │ Page layout group 2                  │
│ (5 pages)                            │    │ (4 pages)                            │    │ (3 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Primary Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Leaders Grid {Unmapped}            │    │ • Hero Section                       │
│ • Main Content {Unmapped}            │    │ • Call-to-Action Section {Unmapped}  │    │ • Multi-Column CTAs {Unmapped}       │
│ • —                                  │    │ • —                                  │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Major League Baseball — group 4      │    │ Our Rd Leaders — group 5             │    │ Science — group 28                   │
│ (2 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │    │ • Primary Navigation {Unmapped}      │
│ • Back to Top Button {Unmapped}      │    │ • Hero Section {Unmapped}            │    │ • —                                  │
│ • —                                  │    │ • Card Grid {Unmapped}               │    │ • —                                  │
│ • —                                  │    │ • Prose Columns {Unmapped}           │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Patient Assistance — group 36        │    │ Pipeline — group 46                  │    │ Ai And Data Convergence — group 53   │
│ (2 pages)                            │    │ (2 pages)                            │    │ (2 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │    │ • Global Header {Unmapped}           │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Primary Content {Unmapped}         │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • CTA Button {Unmapped}              │    │ • —                                  │    │ • Content Section {Unmapped}         │
│ • Card Grid                          │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Terms Of Use — group 73              │    │ Abbvie Research Collaborative Endom… │    │ Oncology — group 1                   │
│ (2 pages)                            │    │ (2 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site Header                        │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Content {Unmapped}         │    │ • —                                  │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • —                                  │    │ • Hero Section                       │
│ • —                                  │    │ • —                                  │    │ • Multi-Column CTAs {Unmapped}       │
│ • —                                  │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Policies Disclosures — group 3       │    │ Partnering Days — group 6            │    │ Patient Focused Drug Development — … │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Content Grid {Unmapped}            │    │ • Hero Section                       │    │ • Hero Section                       │
│ • —                                  │    │ • Main Call-to-Action {Unmapped}     │    │ • Main Content {Unmapped}            │
│ • —                                  │    │ • (+2 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Independent Educational Grants — gr… │    │ Commercial — group 9                 │    │ Cubs — group 11                      │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Header {Unmapped}           │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section {Unmapped}            │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Content Introduction {Unmapped}    │    │ • CTA Columns {Unmapped}             │    │ • CTA Grid {Unmapped}                │
│ • (+2 more — see Blocks mapped per … │    │ • Card Grid                          │    │ • Content Section {Unmapped}         │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Eye Care — group 12                  │    │ Abbvies Code Of Conduct — group 13   │    │ Research And Development — group 14  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Bar {Unmapped}             │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Main Navigation {Unmapped}         │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Back to Top Button {Unmapped}      │    │ • Card Grid Section                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Product Quality And Safety — group … │    │ Publications — group 16              │    │ Areas Of Innovation — group 17       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Navigation                  │
│ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │    │ • Hero Section                       │
│ • Hero Section {Unmapped}            │    │ • Hero Section {Unmapped}            │    │ • Content Introduction {Unmapped}    │
│ • Content Grid {Unmapped}            │    │ • Content Columns {Unmapped}         │    │ • Featured Links {Unmapped}          │
│ • (+2 more — see Blocks mapped per … │    │ • Card Grid {Unmapped}               │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Operating With Integrity — group 18  │    │ Clinical Trials — group 19           │    │ Our People — group 20                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │    │ • Utility Strip {Unmapped}           │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Site Footer                        │
│ • Content Cards                      │    │ • Science Section {Unmapped}         │    │ • Back to Top Button {Unmapped}      │
│ • —                                  │    │ • Footer                             │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Neuroscience — group 21              │    │ Who We Are — group 22                │    │ Operations — group 23                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Science Section {Unmapped}         │    │ • Who We Are Text {Unmapped}         │    │ • Hero Section {Unmapped}            │
│ • Who We Are Section {Unmapped}      │    │ • Who We Are Button {Unmapped}       │    │ • Call-to-Action Columns {Unmapped}  │
│ • Footer                             │    │ • (+3 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Patient Support — group 24           │    │ Immunology — group 25                │    │ Abbvie Ventures — group 26           │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Primary Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Card Grid {Unmapped}               │    │ • Who We Are Section {Unmapped}      │    │ • Hero Section                       │
│ • —                                  │    │ • Science Section {Unmapped}         │    │ • Content Section 1 {Unmapped}       │
│ • —                                  │    │ • Back to Top Button {Unmapped}      │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Key Facts — group 27                 │    │ Positions Views — group 29           │    │ Other Specialties — group 30         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Primary Navigation {Unmapped}      │    │ • Global Navigation Bar {Unmapped}   │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Primary Navigation {Unmapped}      │
│ • Key Facts Section {Unmapped}       │    │ • Primary Content Area {Unmapped}    │    │ • —                                  │
│ • Related Links {Unmapped}           │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Corporate — group 31                 │    │ Rd Sites — group 32                  │    │ Patients — group 33                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip               │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Main Content Area {Unmapped}       │
│ • Call-to-Action Grid {Unmapped}     │    │ • Content Columns                    │    │ • —                                  │
│ • Card Grid                          │    │ • Card Grid                          │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Opportunities — group 34             │    │ Partner With Us — group 35           │    │ Our Stories — group 37               │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site Navigation                    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │
│ • Hero Banner                        │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Who We Are                         │    │ • CTA Grid {Unmapped}                │    │ • Main Content {Unmapped}            │
│ • Science Overview                   │    │ • Card Teasers {Unmapped}            │    │ • Card Grid                          │
│ • Patient Resources                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ The Persistence Lab Podcasts — grou… │    │ Community Of Science — group 39      │    │ Our Principles — group 40            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section {Unmapped}            │
│ • Main Content {Unmapped}            │    │ • Multi-Column CTA {Unmapped}        │    │ • Call-to-Action Grid {Unmapped}     │
│ • —                                  │    │ • Card Grid                          │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Responsible Supply Chain — group 41  │    │ Protecting Human Rights And Workpla… │    │ Precision Medicine — group 43        │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Content Card Grid                  │    │ • Content Introduction {Unmapped}    │    │ • Card Grid                          │
│ • —                                  │    │ • (+2 more — see Blocks mapped per … │    │ • Footer                             │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ A History Of Impact — group 44       │    │ Life At Abbvie — group 45            │    │ Transparency In Payment — group 47   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Milestones Timeline {Unmapped}     │    │ • —                                  │    │ • Hero Section                       │
│ • Footer                             │    │ • —                                  │    │ • CTA Grid {Unmapped}                │
│ • —                                  │    │ • —                                  │    │ • Content Columns {Unmapped}         │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Benefits — group 48                  │    │ Aesthetics — group 49                │    │ Products — group 50                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header                      │    │ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • —                                  │
│ • Benefits Overview {Unmapped}       │    │ • Hero Section                       │    │ • —                                  │
│ • Featured Story {Unmapped}          │    │ • Content Columns                    │    │ • —                                  │
│ • Recognition Highlight {Unmapped}   │    │ • Card Grid                          │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Equity Equality Inclusion Diversity… │    │ Grants And Contribution Disclosures… │    │ How To Apply — group 54              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Primary Navigation {Unmapped}      │    │ • Footer Links                       │
│ • Main Content Columns {Unmapped}    │    │ • Content Section {Unmapped}         │    │ • —                                  │
│ • (+2 more — see Blocks mapped per … │    │ • Footer                             │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Brand Partnerships — group 55        │    │ Areas Of Focus — group 56            │    │ Genomics — group 57                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Header {Unmapped}           │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Content Column One {Unmapped}      │    │ • Areas of Focus Section {Unmapped}  │    │ • Content Introduction {Unmapped}    │
│ • Content Column Two {Unmapped}      │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Requestor Training Guide — group 58  │    │ Allergan Aesthetics — group 59       │    │ Living With An Illness — group 60    │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • —                                  │    │ • Main Content Introduction {Unmapp… │
│ • —                                  │    │ • —                                  │    │ • Main CTA Button {Unmapped}         │
│ • —                                  │    │ • —                                  │    │ • Featured Card Grid {Unmapped}      │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 61                 │    │ Investigator Initiated Studies — gr… │    │ Learning And Development — group 63  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Strip {Unmapped}           │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Main Navigation {Unmapped}         │
│ • Hero Section                       │    │ • Card Grid {Unmapped}               │    │ • Hero Section                       │
│ • Main Content {Unmapped}            │    │ • —                                  │    │ • Call to Action Section {Unmapped}  │
│ • —                                  │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Request Types — group 64             │    │ Therapeutic Modalities And Platform… │    │ Contact Center — group 66            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Site Header                        │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Hero Banner                        │    │ • Primary Navigation {Unmapped}      │
│ • Main Content Section {Unmapped}    │    │ • Main Navigation {Unmapped}         │    │ • Hero Section                       │
│ • —                                  │    │ • Content Area {Unmapped}            │    │ • Who We Are CTA {Unmapped}          │
│ • —                                  │    │ • Back to Top Button {Unmapped}      │    │ • Science CTA {Unmapped}             │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Abbvie Inquiry — group 67            │    │ Jag Dosanjh — group 68               │    │ Join Us — group 69                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Main Content {Unmapped}            │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Footer                             │    │ • —                                  │
│ • Main Content {Unmapped}            │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Student And New Graduates — group 70 │    │ Sustainability — group 71            │    │ Environmental Social And Governance… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Back to Top Button {Unmapped}      │    │ • —                                  │
│ • Who We Are Section {Unmapped}      │    │ • —                                  │    │ • —                                  │
│ • (+2 more — see Blocks mapped per … │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ United States — group 74             │    │ Latif Akintade — group 75            │    │ Robert Michael — group 76            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header                      │    │ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Hero Banner                        │
│ • Who We Are Section {Unmapped}      │    │ • Content Introduction {Unmapped}    │    │ • About Section {Unmapped}           │
│ • Science Section {Unmapped}         │    │ • Call-to-Action Buttons {Unmapped}  │    │ • Call-to-Action Button {Unmapped}   │
│ • Patients Section {Unmapped}        │    │ • —                                  │    │ • Featured Card                      │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Why Abbvie — group 77                │    │ Liz Shea — group 78                  │    │ New Graduates And Entry Level Posit… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Global Header {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section {Unmapped}            │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • —                                  │    │ • Main Content Area {Unmapped}       │    │ • Who We Are Section {Unmapped}      │
│ • —                                  │    │ • Back to Top Button {Unmapped}      │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Nicholas Donoghoe — group 80         │    │ Page layout group 81                 │    │ Algeria — group 82                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header {Unmapped}           │    │ • Global Header {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Primary Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Main Navigation {Unmapped}         │    │ • Hero Section {Unmapped}            │
│ • Content Introduction {Unmapped}    │    │ • Content Introduction {Unmapped}    │    │ • Who We Are Section {Unmapped}      │
│ • (+2 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Supplier Resources — group 83        │    │ Internships — group 84               │    │ Croatia — group 85                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • —                                  │    │ • Hero Section                       │
│ • Card Grid Highlights               │    │ • —                                  │    │ • Content Introduction {Unmapped}    │
│ • Dashboard Facts {Unmapped}         │    │ • —                                  │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Jeffrey Stewart — group 86           │    │ Page layout group 87                 │    │ Lebanon — group 88                   │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Primary Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Content Introduction {Unmapped}    │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Call to Action Buttons {Unmapped}  │    │ • Card Grid Section                  │    │ • Call-to-Action Grid {Unmapped}     │
│ • (+3 more — see Blocks mapped per … │    │ • —                                  │    │ • Card Grid                          │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Lithuania — group 89                 │    │ Nicole Mowad Nassar — group 90       │    │ Disaster Relief — group 91           │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Main Content {Unmapped}            │    │ • —                                  │
│ • Content Section: Who We Are {Unma… │    │ • —                                  │    │ • —                                  │
│ • (+3 more — see Blocks mapped per … │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Estonia — group 92                   │    │ Student Programs — group 93          │    │ Page layout group 94                 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Strip {Unmapped}           │    │ • Global Navigation {Unmapped}       │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Hero Section                       │    │ • Prose Content Columns {Unmapped}   │    │ • Story Cards                        │
│ • Who We Are Section {Unmapped}      │    │ • Back to Top Button {Unmapped}      │    │ • Footer                             │
│ • (+2 more — see Blocks mapped per … │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Bosnia And Herzegovina — group 95    │    │ Allergan Ous Disclosures — group 96  │    │ Serbia — group 97                    │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site Navigation Header             │    │ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │
│ • Hero Banner                        │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Who We Are Section {Unmapped}      │    │ • —                                  │    │ • Primary Navigation {Unmapped}      │
│ • Science Section {Unmapped}         │    │ • —                                  │    │ • Content Section 1 {Unmapped}       │
│ • Patients Section {Unmapped}        │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Roopal Thakkar — group 98            │    │ Page layout group 99                 │    │ Well Being In The Workplace — group… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site Header                        │    │ • Utility Strip {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Banner                        │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Main Navigation {Unmapped}         │    │ • —                                  │    │ • —                                  │
│ • Content Introduction {Unmapped}    │    │ • —                                  │    │ • —                                  │
│ • Content Cards                      │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Timothy Richmond — group 101         │    │ Resources — group 102                │    │ Alberto Colzi — group 103            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │
│ • Footer                             │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • —                                  │    │ • Hero Section                       │    │ • Main Navigation {Unmapped}         │
│ • —                                  │    │ • Content Cards Grid                 │    │ • Footer                             │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Accessibility Statement — group 104  │    │ Saudi Arabia — group 105             │    │ Perry Siatis — group 106             │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header {Unmapped}           │    │ • Primary Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │
│ • Main Navigation {Unmapped}         │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Content Columns {Unmapped}         │    │ • Footer Section                     │
│ • Content Grid {Unmapped}            │    │ • Card Grid                          │    │ • —                                  │
│ • —                                  │    │ • Footer                             │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Impact Through Inclusion — group 107 │    │ Slovenia — group 108                 │    │ Tunisia — group 109                  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Bar                        │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Site Search                        │
│ • Main Content Area {Unmapped}       │    │ • Content Cards                      │    │ • Cookie Preferences {Unmapped}      │
│ • Footer Section                     │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Romania — group 110                  │    │ Azita Saleki Gerhardt — group 111    │    │ South Africa And Sub Saharan Africa… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │    │ • Primary Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Content Introduction {Unmapped}    │
│ • Content Grid {Unmapped}            │    │ • Main Content {Unmapped}            │    │ • Call-to-Action Buttons {Unmapped}  │
│ • —                                  │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Latvia — group 113                   │    │ Scott Reents — group 114             │    │ United Arab Emirates — group 116     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Bar {Unmapped}      │    │ • Primary Navigation                 │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Content Section                    │    │ • Content Section {Unmapped}         │
│ • Content Call-to-Actions {Unmapped} │    │ • Card Grid                          │    │ • Card Grid                          │
│ • Grid of Cards {Unmapped}           │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Addressing Systemic Barriers — grou… │    │ Postdoctoral Program — group 118     │    │ Page layout group 119                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Story Cards Grid                   │
│ • Content Section 1 {Unmapped}       │    │ • Content Highlight {Unmapped}       │    │ • Dashboard Cards {Unmapped}         │
│ • Content Section 2 {Unmapped}       │    │ • Call-to-Action Grid {Unmapped}     │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Innovative Impact — group 120        │    │ Employee Resource Groups — group 121 │    │ Site Map — group 122                 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Strip {Unmapped}           │    │ • Global Header                      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Main Content {Unmapped}            │    │ • Hero Section                       │    │ • Main Navigation {Unmapped}         │
│ • Card Grid {Unmapped}               │    │ • Content Introduction {Unmapped}    │    │ • Primary Content {Unmapped}         │
│ • Back to Top {Unmapped}             │    │ • (+4 more — see Blocks mapped per … │    │ • Footer Section                     │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Wulff Erik Von Borcke — group 123    │    │ Page layout group 124                │    │ Tracie Haas — group 125              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • —                                  │    │ • Footer Navigation                  │    │ • Main Content {Unmapped}            │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 126                │    │ Page layout group 127                │    │ Demetris Crum — group 128            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header {Unmapped}           │    │ • Utility Strip                      │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section {Unmapped}            │    │ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Main Content {Unmapped}            │    │ • Introductory Content {Unmapped}    │    │ • Call to Action Section {Unmapped}  │
│ • —                                  │    │ • (+3 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Abbvie Volunteers Return To Serving… │    │ Btk Protein Good Bad And Ugly — gro… │    │ Jerome Bouyer — group 131            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Bar {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Content Introduction {Unmapped}    │    │ • Footer Navigation {Unmapped}       │
│ • Main Content Area {Unmapped}       │    │ • Main Story {Unmapped}              │    │ • Back to Top Button {Unmapped}      │
│ • Card Grid                          │    │ • Additional Links {Unmapped}        │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Linda Ray — group 132                │    │ Everyones Talking About Data Scienc… │    │ The Power Love In Ibd — group 134    │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site-wide Navigation {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │
│ • Hero Banner                        │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Page Content {Unmapped}            │    │ • Hero Section                       │    │ • Content Introduction {Unmapped}    │
│ • Footer Section                     │    │ • Content Cards                      │    │ • Call to Action {Unmapped}          │
│ • —                                  │    │ • —                                  │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 135                │    │ Magnified Featuring Linda Scarazzin… │    │ How Patient Voices Are Changing Med… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Strip {Unmapped}           │    │ • Primary Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Main Content {Unmapped}            │
│ • —                                  │    │ • Main Content {Unmapped}            │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Inside Dream Initiative — group 138  │    │ Dave Purdue — group 139              │    │ Page layout group 140                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Links {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Main Navigation {Unmapped}         │
│ • Hero Section                       │    │ • Lead Content {Unmapped}            │    │ • Multi-Column Call-to-Actions {Unm… │
│ • Content Introduction {Unmapped}    │    │ • —                                  │    │ • Card Grid Teasers {Unmapped}       │
│ • (+3 more — see Blocks mapped per … │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 141                │    │ Page layout group 142                │    │ Page layout group 143                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Main Content Area {Unmapped}       │    │ • —                                  │    │ • Hero Section {Unmapped}            │
│ • Card Grid                          │    │ • —                                  │    │ • Content Cards {Unmapped}           │
│ • Back to Top Button {Unmapped}      │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Can Unlocking One Million Genomes —… │    │ They Wont Back Down — group 145      │    │ Page layout group 146                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header                      │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Main Article {Unmapped}            │
│ • —                                  │    │ • Main Content Section {Unmapped}    │    │ • Footer                             │
│ • —                                  │    │ • (+2 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 147                │    │ Page layout group 148                │    │ Page layout group 149                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Global Utility Strip {Unmapped}    │    │ • Primary Navigation {Unmapped}      │
│ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Introductory Content {Unmapped}    │    │ • Content Cards                      │    │ • Story Highlights {Unmapped}        │
│ • Call-to-Action Button {Unmapped}   │    │ • —                                  │    │ • Call-to-Action Grid {Unmapped}     │
│ • (+9 more — see Blocks mapped per … │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 150                │    │ Living With Unknowns Alzheimers Dis… │    │ Page layout group 152                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Strip {Unmapped}           │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Main Content {Unmapped}            │    │ • Back to Top Button {Unmapped}      │
│ • Story Cards Grid                   │    │ • —                                  │    │ • —                                  │
│ • Dashboard Cards                    │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Magnified Featuring Matt Widman — g… │    │ Jason Smith — group 154              │    │ Page layout group 155                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Primary Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Card Grid Section                  │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • —                                  │    │ • Footer Links {Unmapped}            │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Magnified Featuring Jonathon Sedgwi… │    │ Page layout group 157                │    │ Page layout group 158                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Main Content {Unmapped}            │    │ • Story Highlight {Unmapped}         │    │ • —                                  │
│ • —                                  │    │ • Content Cards                      │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 159                │    │ Trapped In Your Own Skin — group 160 │    │ Why Isnt Medicine One Size Fits All… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Global Header {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │
│ • Main Content {Unmapped}            │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section                       │    │ • Hero Section                       │
│ • —                                  │    │ • —                                  │    │ • Content Introduction {Unmapped}    │
│ • —                                  │    │ • —                                  │    │ • Card Grid                          │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 162                │    │ Page layout group 163                │    │ Page layout group 164                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │    │ • Global Header                      │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Main Content {Unmapped}            │
│ • Hero Section                       │    │ • Primary Call to Action {Unmapped}  │    │ • Footer                             │
│ • Content Teaser Cards               │    │ • Card Grid                          │    │ • —                                  │
│ • Prose Columns {Unmapped}           │    │ • Footer                             │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Magnified Featuring Shuhong Zhang —… │    │ Page layout group 166                │    │ The Math Of Migraine — group 167     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Primary Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Bar {Unmapped}      │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Site Navigation {Unmapped}         │
│ • Content Cards                      │    │ • Hero Section                       │    │ • Story Cards                        │
│ • —                                  │    │ • Content Teasers {Unmapped}         │    │ • Data Cards                         │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Magnified Featuring Darin Messina —… │    │ Magnified Featuring Sean Mcewen — g… │    │ A Journey Of Sight Progress — group… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │    │ • Global Header {Unmapped}           │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Main Content {Unmapped}            │    │ • Story Highlight {Unmapped}         │
│ • —                                  │    │ • —                                  │    │ • Dashboard Cards {Unmapped}         │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ What Does It Take To Discover A New… │    │ Shining Light On Glaucoma And Eye H… │    │ Page layout group 173                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │    │ • Global Header                      │
│ • Primary Navigation {Unmapped}      │    │ • Main Content {Unmapped}            │    │ • Main Navigation {Unmapped}         │
│ • Hero Section {Unmapped}            │    │ • Footer                             │    │ • Content Section {Unmapped}         │
│ • Content Introduction {Unmapped}    │    │ • —                                  │    │ • Footer                             │
│ • (+4 more — see Blocks mapped per … │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 174                │    │ Navigating Ulcerative Colitis As A … │    │ Page layout group 176                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Strip {Unmapped}           │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Story Content {Unmapped}           │    │ • Main Content {Unmapped}            │    │ • Content Introduction {Unmapped}    │
│ • Related Articles {Unmapped}        │    │ • —                                  │    │ • Content Cards {Unmapped}           │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 177                │    │ Page layout group 178                │    │ Page layout group 179                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Site Header                 │    │ • Global Navigation {Unmapped}       │    │ • Global Header                      │
│ • Hero Image Section                 │    │ • Main Content {Unmapped}            │    │ • Hero Section                       │
│ • Primary Navigation {Unmapped}      │    │ • —                                  │    │ • Main Navigation {Unmapped}         │
│ • Main Content Area {Unmapped}       │    │ • —                                  │    │ • Content Introduction {Unmapped}    │
│ • Site Footer                        │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 180                │    │ Stronger Together Convergence Minds… │    │ Page layout group 182                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Site Header                        │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Banner                        │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Main Content Area {Unmapped}       │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Chasing The Value Of A Walk Down Th… │    │ Page layout group 184                │    │ Page layout group 185                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Hero Section                       │    │ • —                                  │    │ • Main Content Area {Unmapped}       │
│ • Content Cards                      │    │ • —                                  │    │ • Footer                             │
│ • Dashboard Cards {Unmapped}         │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 186                │    │ Nisha Patel Burns — group 187        │    │ Injecting Hope One Vaccine At A Tim… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Utility Strip {Unmapped}           │    │ • Global Navigation {Unmapped}       │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • —                                  │    │ • Lead Content {Unmapped}            │    │ • Main Content Introduction {Unmapp… │
│ • —                                  │    │ • Back to Top {Unmapped}             │    │ • Related Content Cards {Unmapped}   │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Profile Stories — group 189          │    │ Magnified Featuring Edrice Simmons … │    │ Company Stories — group 191          │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Utility Strip {Unmapped}           │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • —                                  │    │ • Hero Section                       │
│ • Profile Stories Grid {Unmapped}    │    │ • —                                  │    │ • Card Grid                          │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Eedi Stories — group 192             │    │ Sustainability Stories — group 193   │    │ Abbvie Research Collaborative — gro… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip               │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Story Cards                        │    │ • Featured Story Card                │    │ • Multi-Column Call to Actions {Unm… │
│ • Dashboard Cards                    │    │ • (+3 more — see Blocks mapped per … │    │ • Card Grid {Unmapped}               │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 195                │    │ A Legacy Of Leadership In Mental He… │    │ Magnified Featuring Johanna Corbin … │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Global Utility Strip               │    │ • Global Navigation {Unmapped}       │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation                 │    │ • Main Content {Unmapped}            │
│ • —                                  │    │ • Hero Section                       │    │ • —                                  │
│ • —                                  │    │ • Main Content {Unmapped}            │    │ • —                                  │
│ • —                                  │    │ • (+2 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 198                │    │ Voices Abbvie Reflecting On Decade … │    │ Page layout group 200                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Multi-Column CTAs {Unmapped}       │    │ • Main Content Area {Unmapped}       │    │ • Main Content Area {Unmapped}       │
│ • Card Grid                          │    │ • Footer                             │    │ • —                                  │
│ • Back to Top Button {Unmapped}      │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 201                │    │ Science Stories — group 202          │    │ Why You Cant Wait With Rheumatoid A… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Related Links {Unmapped}           │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Back to Top Button {Unmapped}      │    │ • Science Story Card {Unmapped}      │    │ • Footer                             │
│ • —                                  │    │ • Dashboard Facts {Unmapped}         │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 204                │    │ Page layout group 205                │    │ Page layout group 206                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │
│ • Content Introduction {Unmapped}    │    │ • Hero Section {Unmapped}            │    │ • Back to Top Button {Unmapped}      │
│ • Card Grid {Unmapped}               │    │ • Story Highlights {Unmapped}        │    │ • —                                  │
│ • Footer {Unmapped}                  │    │ • (+3 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 207                │    │ Page layout group 208                │    │ Digital Science Lab — group 209      │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Main Story Content {Unmapped}      │    │ • Footer Navigation                  │    │ • Hero Section                       │
│ • Related Links {Unmapped}           │    │ • Back to Top Button {Unmapped}      │    │ • Content Grid {Unmapped}            │
│ • —                                  │    │ • —                                  │    │ • Call-to-Action Section {Unmapped}  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Immunologys Next Frontier — group 2… │    │ Magnified Featuring Nicholas Donogh… │    │ Eye Care Stories — group 212         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Primary Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Card Grid                          │
│ • Hero Section                       │    │ • Card Grid Stories {Unmapped}       │    │ • —                                  │
│ • Content Grid {Unmapped}            │    │ • Dashboard Cards {Unmapped}         │    │ • —                                  │
│ • —                                  │    │ • Back to Top Button {Unmapped}      │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Time Is Hours — group 213            │    │ Page layout group 214                │    │ Neuroscience Stories — group 215     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip               │    │ • Global Navigation {Unmapped}       │    │ • Global Header {Unmapped}           │
│ • Primary Navigation                 │    │ • Hero Section                       │    │ • Hero Section {Unmapped}            │
│ • Hero Section                       │    │ • Main Content {Unmapped}            │    │ • Primary Navigation {Unmapped}      │
│ • Story Card Grid                    │    │ • Footer Section                     │    │ • Content Card Grid {Unmapped}       │
│ • (+3 more — see Blocks mapped per … │    │ • —                                  │    │ • Content Columns {Unmapped}         │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 216                │    │ Immunology Stories — group 217       │    │ Page layout group 218                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Main Content {Unmapped}            │    │ • Back to Top Button {Unmapped}      │    │ • Hero Section                       │
│ • —                                  │    │ • —                                  │    │ • Story Content {Unmapped}           │
│ • —                                  │    │ • —                                  │    │ • Related Links {Unmapped}           │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 219                │    │ Page layout group 220                │    │ Page layout group 221                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Header {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation Bar {Unmapped}  │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Main Content Area {Unmapped}       │    │ • Main Content {Unmapped}            │    │ • —                                  │
│ • —                                  │    │ • Footer                             │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 222                │    │ Page layout group 223                │    │ Oncology Stories — group 224         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Utility Links {Unmapped}           │    │ • Global Navigation {Unmapped}       │
│ • Hero Section                       │    │ • Main Navigation {Unmapped}         │    │ • Hero Section                       │
│ • Main Content {Unmapped}            │    │ • Hero Banner                        │    │ • Content Cards                      │
│ • Story Cards {Unmapped}             │    │ • Card Grid                          │    │ • —                                  │
│ • Footer                             │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 225                │    │ Page layout group 226                │    │ Transforming Cancer Care From The I… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Links {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation Bar {Unmapped}  │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Banner {Unmapped}             │    │ • Content Grid {Unmapped}            │    │ • Hero Section                       │
│ • Page Main Content {Unmapped}       │    │ • —                                  │    │ • Main Content CTA {Unmapped}        │
│ • —                                  │    │ • —                                  │    │ • Card Grid                          │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Aesthetics Stories — group 228       │    │ Can We Find Cures Faster — group 229 │    │ Navigating The Hidden Side Of Cance… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Content Grid {Unmapped}            │    │ • Content Cards                      │    │ • Primary Call-to-Action {Unmapped}  │
│ • —                                  │    │ • —                                  │    │ • Content Cards                      │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Ambassadors In Action — group 231    │    │ Working At Abbvie Stories — group 2… │    │ Page layout group 233                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Main Content Introduction {Unmapp… │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Card Grid {Unmapped}               │    │ • Card Grid - Stories                │    │ • Card Grid                          │
│ • —                                  │    │ • Dashboard Facts {Unmapped}         │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────┐
│WWW.ABBVIE.COM — SUB-TEMPLATES TEMPLATES                                     │
└─────────────────────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 234                │    │ Elevating Health Care For All — gro… │    │ Page layout group 236                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Hero Section                       │    │ • —                                  │
│ • Content Cards {Unmapped}           │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 237                │    │ Page layout group 238                │    │ Page layout group 239                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Utility Strip {Unmapped}           │    │ • Global Navigation {Unmapped}       │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • —                                  │
│ • Main Story Content {Unmapped}      │    │ • Main Content {Unmapped}            │    │ • —                                  │
│ • Footer Navigation                  │    │ • —                                  │    │ • —                                  │
│ • Back to Top Button {Unmapped}      │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Real People Real Inspiration Joes S… │    │ Page layout group 241                │    │ Philanthropy Stories — group 242     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Links {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │    │ • Global Header {Unmapped}           │
│ • Main Navigation {Unmapped}         │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Hero Banner                        │    │ • Back to Top Button {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Content Layout {Unmapped}          │    │ • —                                  │    │ • Content Cards                      │
│ • (+2 more — see Blocks mapped per … │    │ • —                                  │    │ • Back to Top Button {Unmapped}      │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Serving Communities Stories — group… │    │ Virology Stories — group 244         │    │ Synthetic Control Arm End Placebos … │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Main Navigation {Unmapped}         │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Card Grid                          │    │ • Main Content Area {Unmapped}       │
│ • —                                  │    │ • —                                  │    │ • Card Grid {Unmapped}               │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Little Patients Big Impact — group … │    │ Page layout group 247                │    │ Patient Support Stories — group 248  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Header {Unmapped}           │    │ • Utility Strip {Unmapped}           │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section {Unmapped}            │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section {Unmapped}            │    │ • Main Navigation {Unmapped}         │    │ • Card Grid {Unmapped}               │
│ • Content Highlight {Unmapped}       │    │ • Content Introduction {Unmapped}    │    │ • —                                  │
│ • Call-to-Action Buttons {Unmapped}  │    │ • (+2 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 249                │    │ Change From Within — group 250       │    │ Partnerships Stories — group 251     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Main Content {Unmapped}            │    │ • Main Content {Unmapped}            │    │ • Main Navigation {Unmapped}         │
│ • —                                  │    │ • Footer                             │    │ • Primary Story Card                 │
│ • —                                  │    │ • —                                  │    │ • Secondary Story Grid               │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 252                │    │ Bay Area Opportunities — group 253   │    │ Social Media Community Guidelines —… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Main Content {Unmapped}            │    │ • Introduction Content {Unmapped}    │    │ • Content Section {Unmapped}         │
│ • —                                  │    │ • (+3 more — see Blocks mapped per … │    │ • Footer Section                     │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Cerevel — group 255                  │    │ Mitokinin — group 256                │    │ Celsius Therapeutics — group 257     │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Header                      │    │ • Global Utility Navigation {Unmapp… │
│ • Main Navigation {Unmapped}         │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Hero Banner {Unmapped}             │    │ • Introductory Content {Unmapped}    │    │ • Hero Area {Unmapped}               │
│ • Intro Text Block {Unmapped}        │    │ • Neuroscience Section {Unmapped}    │    │ • Lead Content Area {Unmapped}       │
│ • (+2 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │    │ • (+5 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Immunogen — group 258                │    │ Discovery Files — group 259          │    │ Allergan — group 260                 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Header {Unmapped}           │    │ • Site Header                        │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Site Search                        │
│ • Introduction Text {Unmapped}       │    │ • Primary Navigation {Unmapped}      │    │ • Cookie Preferences {Unmapped}      │
│ • Oncology Section {Unmapped}        │    │ • Content Section 1 {Unmapped}       │    │ • —                                  │
│ • (+2 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Behind The Science — group 261       │    │ Linda Scarazzini — group 262         │    │ Equal Employment Opportunity Employ… │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • Hero Section {Unmapped}            │    │ • Multi-Column CTAs {Unmapped}       │
│ • Main Content {Unmapped}            │    │ • Content Columns {Unmapped}         │    │ • Card Grid {Unmapped}               │
│ • Card Grid                          │    │ • Footer Links {Unmapped}            │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Capstan Therapeutics — group 264     │    │ Savings Card — group 265             │    │ Available Programs — group 266       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │    │ • Global Navigation {Unmapped}       │
│ • Main Navigation {Unmapped}         │    │ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │
│ • Hero Section {Unmapped}            │    │ • Hero Section {Unmapped}            │    │ • Programs List {Unmapped}           │
│ • Announcement Section {Unmapped}    │    │ • Card Grid Section {Unmapped}       │    │ • Featured Story {Unmapped}          │
│ • (+5 more — see Blocks mapped per … │    │ • —                                  │    │ • Recognition Facts {Unmapped}       │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Eligibility Criteria — group 267     │    │ Science In 60 Seconds — group 268    │    │ Aliada Therapeutics — group 269      │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Utility Links {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Site Navigation {Unmapped}         │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Banner                        │    │ • Hero Section                       │
│ • —                                  │    │ • Content Cards                      │    │ • Who We Are Section {Unmapped}      │
│ • —                                  │    │ • —                                  │    │ • (+2 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Contactus — group 270                │    │ Online Application Overview — group… │    │ Locations — group 272                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Card Grid                          │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Daejin Abidoye — group 273           │    │ Wolfram Nothaft — group 274          │    │ Eleni Lagkadinou — group 275         │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Primary Content {Unmapped}         │    │ • Content Introduction {Unmapped}    │    │ • Footer Links                       │
│ • —                                  │    │ • Card Grid                          │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Raymond Votzmeyer — group 276        │    │ Abbvie Pride — group 277             │    │ Income Criteria — group 278          │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Primary Navigation {Unmapped}      │    │ • Global Header {Unmapped}           │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Hero Section                       │
│ • Main Content {Unmapped}            │    │ • Call-to-Action Grid {Unmapped}     │    │ • Navigation Menu {Unmapped}         │
│ • Footer                             │    │ • —                                  │    │ • Content Introduction {Unmapped}    │
│ • —                                  │    │ • —                                  │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Philip Hajduk — group 279            │    │ Access To Investigational Drugs Pol… │    │ Michael Foley — group 281            │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip {Unmapped}           │    │ • Global Header {Unmapped}           │    │ • Global Navigation {Unmapped}       │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section {Unmapped}            │    │ • —                                  │
│ • Main Content {Unmapped}            │    │ • Primary Navigation {Unmapped}      │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Page layout group 282                │    │ Asian Leadership Network — group 283 │    │ Veterans — group 284                 │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header {Unmapped}           │    │ • Utility Strip {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Primary Header {Unmapped}          │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Card Grid {Unmapped}               │
│ • Content Introduction {Unmapped}    │    │ • Call-to-Action Section {Unmapped}  │    │ • Back to Top Button {Unmapped}      │
│ • (+2 more — see Blocks mapped per … │    │ • (+2 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Human Capital Management — group 285 │    │ Declaracion De Accessibilidad — gro… │    │ Page layout group 287                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • —                                  │    │ • Hero Section                       │    │ • Hero Section                       │
│ • —                                  │    │ • Content Cards                      │    │ • Call-to-Action Section {Unmapped}  │
│ • —                                  │    │ • —                                  │    │ • Card Grid                          │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Patents — group 288                  │    │ Page layout group 289                │    │ Primal Kaur — group 290              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │    │ • Primary Navigation {Unmapped}      │
│ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │    │ • —                                  │
│ • Hero Section                       │    │ • Hero Section                       │    │ • —                                  │
│ • Call-to-Action Grid {Unmapped}     │    │ • —                                  │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Reasonable Accommodations — group 2… │    │ Page layout group 292                │    │ Ahora Hispanic Latino — group 293    │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Header                      │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Primary Navigation                 │    │ • Footer Links {Unmapped}            │    │ • —                                  │
│ • Content Section 1                  │    │ • —                                  │    │ • —                                  │
│ • (+3 more — see Blocks mapped per … │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Abbvie Ventures Portfolio — group 2… │    │ Environmental Sustainability — grou… │    │ Lab To Life — group 296              │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Header {Unmapped}           │    │ • Global Utility Strip {Unmapped}    │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Primary Navigation {Unmapped}      │
│ • Call-to-Action Grid {Unmapped}     │    │ • Primary Navigation {Unmapped}      │    │ • Back to Top Button {Unmapped}      │
│ • Card Teasers {Unmapped}            │    │ • Content Section {Unmapped}         │    │ • —                                  │
│ • —                                  │    │ • Card Grid                          │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Jonathon Sedgwick — group 297        │    │ Andrew Campbell — group 298          │    │ Page layout group 299                │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Utility Strip {Unmapped}    │    │ • Global Header                      │    │ • Utility Links {Unmapped}           │
│ • Primary Navigation {Unmapped}      │    │ • Hero Section                       │    │ • Main Navigation {Unmapped}         │
│ • Hero Section                       │    │ • Navigation Menu {Unmapped}         │    │ • Hero Image Section                 │
│ • —                                  │    │ • Main Content {Unmapped}            │    │ • —                                  │
│ • —                                  │    │ • —                                  │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Lab Of The Future — group 300        │    │ Darin Messina — group 301            │    │ Ability At Abbvie — group 302        │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Navigation                 │    │ • Global Navigation {Unmapped}       │    │ • Global Utility Strip               │
│ • Main Navigation                    │    │ • Hero Section {Unmapped}            │    │ • Primary Navigation                 │
│ • Hero Section                       │    │ • Main Content {Unmapped}            │    │ • Hero Section                       │
│ • Call-to-Action Columns             │    │ • Footer {Unmapped}                  │    │ • Main Content {Unmapped}            │
│ • Card Grid                          │    │ • —                                  │    │ • Footer                             │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Shuhong Zhang — group 303            │    │ Black Business Network — group 304   │    │ Women Leaders In Action — group 305  │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section {Unmapped}            │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Footer                             │    │ • Hero Section {Unmapped}            │    │ • —                                  │
│ • —                                  │    │ • Content Introduction {Unmapped}    │    │ • —                                  │
│ • —                                  │    │ • (+3 more — see Blocks mapped per … │    │ • —                                  │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Allergan Labeling — group 306        │    │ Page layout group 307                │    │ Nimbletherapeutics — group 309       │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Global Navigation {Unmapped}       │    │ • Primary Navigation {Unmapped}      │    │ • Global Utility Strip {Unmapped}    │
│ • Hero Section                       │    │ • Hero Section                       │    │ • Primary Header {Unmapped}          │
│ • Main Content {Unmapped}            │    │ • —                                  │    │ • Hero Section                       │
│ • —                                  │    │ • —                                  │    │ • Lead Content {Unmapped}            │
│ • —                                  │    │ • —                                  │    │ • (+3 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ Privacy — group 310                  │    │ Partnerships Chicago Cubs — group 3… │    │ Latest Earnings — group 312          │
│ (1 pages)                            │    │ (1 pages)                            │    │ (1 pages)                            │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

                       ▼                       ▼                       ▼
┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐    ┌──────────────────────────────────────┐
│ • Utility Strip                      │    │ • Global Utility Strip {Unmapped}    │    │ • Global Utility Navigation {Unmapp… │
│ • Primary Navigation                 │    │ • Primary Navigation {Unmapped}      │    │ • Primary Navigation {Unmapped}      │
│ • Hero Section                       │    │ • CTA Columns {Unmapped}             │    │ • Site Search {Unmapped}             │
│ • Introduction Paragraph {Unmapped}  │    │ • Card Grid {Unmapped}               │    │ • Breadcrumb Navigation {Unmapped}   │
│ • (+6 more — see Blocks mapped per … │    │ • —                                  │    │ • (+9 more — see Blocks mapped per … │
└──────────────────────────────────────┘    └──────────────────────────────────────┘    └──────────────────────────────────────┘

┌──────────────────────────────────────┐
│ Privacy Inquiry — group 313          │
│ (1 pages)                            │
└──────────────────────────────────────┘

                       ▼
┌──────────────────────────────────────┐
│ • Global Header                      │
│ • Hero Section                       │
│ • Content Form                       │
│ • Footer Section                     │
│ • —                                  │
└──────────────────────────────────────┘

```

## Blocks mapped per template (full names)

Primary component names per layout bucket (same strings as the Component Reuse Matrix). Unmapped catalog rows show `{Unmapped}`. Diagram boxes above are width-limited.

### Abbvie Foundation — group 115 (`tpl_114`) — 5 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Our Leaders — group 10 (`tpl_9`) — 4 pages

- Primary Navigation {Unmapped}
- Hero Section
- Leaders Grid {Unmapped}
- Call-to-Action Section {Unmapped}

### Page layout group 2 (`tpl_1`) — 3 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Multi-Column CTAs {Unmapped}
- Card Grid
- Latest News Listing {Unmapped}
- Back to Top Button {Unmapped}

### Major League Baseball — group 4 (`tpl_3`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top Button {Unmapped}

### Our Rd Leaders — group 5 (`tpl_4`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Hero Section {Unmapped}
- Card Grid {Unmapped}
- Prose Columns {Unmapped}

### Science — group 28 (`tpl_27`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Patient Assistance — group 36 (`tpl_35`) — 2 pages

- Global Navigation {Unmapped}
- Hero Section
- Primary Content {Unmapped}
- CTA Button {Unmapped}
- Card Grid

### Pipeline — group 46 (`tpl_45`) — 2 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section

### Ai And Data Convergence — group 53 (`tpl_52`) — 2 pages

- Global Header {Unmapped}
- Hero Section
- Primary Navigation {Unmapped}
- Content Section {Unmapped}
- Card Grid
- Footer

### Terms Of Use — group 73 (`tpl_72`) — 2 pages

- Site Header
- Primary Content {Unmapped}

### Abbvie Research Collaborative Endometrosis — group 308 (`tpl_307`) — 2 pages

- Global Utility Strip {Unmapped}

### Oncology — group 1 (`tpl_0`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Multi-Column CTAs {Unmapped}
- Card Grid
- Back to Top Button {Unmapped}

### Policies Disclosures — group 3 (`tpl_2`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Grid {Unmapped}

### Partnering Days — group 6 (`tpl_5`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Call-to-Action {Unmapped}
- Card Grid
- Dashboard Cards {Unmapped}

### Patient Focused Drug Development — group 7 (`tpl_6`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}
- Card Grid
- Call-to-Action Buttons {Unmapped}
- Back to Top Button {Unmapped}

### Independent Educational Grants — group 8 (`tpl_7`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Introduction {Unmapped}
- Card Grid {Unmapped}
- Footer

### Commercial — group 9 (`tpl_8`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- CTA Columns {Unmapped}
- Card Grid

### Cubs — group 11 (`tpl_10`) — 1 pages

- Global Header {Unmapped}
- Hero Section {Unmapped}
- Primary Navigation {Unmapped}
- CTA Grid {Unmapped}
- Content Section {Unmapped}

### Eye Care — group 12 (`tpl_11`) — 1 pages

- Utility Bar {Unmapped}
- Main Navigation {Unmapped}

### Abbvies Code Of Conduct — group 13 (`tpl_12`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top Button {Unmapped}

### Research And Development — group 14 (`tpl_13`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Card Grid Section

### Product Quality And Safety — group 15 (`tpl_14`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Grid {Unmapped}
- Card Grid {Unmapped}
- Footer

### Publications — group 16 (`tpl_15`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Hero Section {Unmapped}
- Content Columns {Unmapped}
- Card Grid {Unmapped}

### Areas Of Innovation — group 17 (`tpl_16`) — 1 pages

- Global Navigation
- Hero Section
- Content Introduction {Unmapped}
- Featured Links {Unmapped}
- Featured Card
- Statistics Section {Unmapped}
- Footer

### Operating With Integrity — group 18 (`tpl_17`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Cards

### Clinical Trials — group 19 (`tpl_18`) — 1 pages

- Global Header
- Primary Navigation {Unmapped}
- Hero Section
- Science Section {Unmapped}
- Footer

### Our People — group 20 (`tpl_19`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Site Footer
- Back to Top Button {Unmapped}

### Neuroscience — group 21 (`tpl_20`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Science Section {Unmapped}
- Who We Are Section {Unmapped}
- Footer

### Who We Are — group 22 (`tpl_21`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Who We Are Text {Unmapped}
- Who We Are Button {Unmapped}
- Link List {Unmapped}
- Featured Card
- Recognition Dashboard {Unmapped}

### Operations — group 23 (`tpl_22`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Call-to-Action Columns {Unmapped}
- Card Grid {Unmapped}
- Footer

### Patient Support — group 24 (`tpl_23`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Card Grid {Unmapped}

### Immunology — group 25 (`tpl_24`) — 1 pages

- Primary Navigation {Unmapped}
- Hero Section
- Who We Are Section {Unmapped}
- Science Section {Unmapped}
- Back to Top Button {Unmapped}

### Abbvie Ventures — group 26 (`tpl_25`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Section 1 {Unmapped}
- Content Section 2 {Unmapped}
- Back to Top Button {Unmapped}

### Key Facts — group 27 (`tpl_26`) — 1 pages

- Primary Navigation {Unmapped}
- Hero Section
- Key Facts Section {Unmapped}
- Related Links {Unmapped}

### Positions Views — group 29 (`tpl_28`) — 1 pages

- Global Navigation Bar {Unmapped}
- Hero Section {Unmapped}
- Primary Content Area {Unmapped}

### Other Specialties — group 30 (`tpl_29`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Corporate — group 31 (`tpl_30`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Grid {Unmapped}
- Card Grid

### Rd Sites — group 32 (`tpl_31`) — 1 pages

- Global Utility Strip
- Primary Navigation
- Hero Section
- Content Columns
- Card Grid

### Patients — group 33 (`tpl_32`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content Area {Unmapped}

### Opportunities — group 34 (`tpl_33`) — 1 pages

- Site Navigation
- Hero Banner
- Who We Are
- Science Overview
- Patient Resources

### Partner With Us — group 35 (`tpl_34`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- CTA Grid {Unmapped}
- Card Teasers {Unmapped}

### Our Stories — group 37 (`tpl_36`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}
- Card Grid

### The Persistence Lab Podcasts — group 38 (`tpl_37`) — 1 pages

- Global Header {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Community Of Science — group 39 (`tpl_38`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Multi-Column CTA {Unmapped}
- Card Grid

### Our Principles — group 40 (`tpl_39`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Call-to-Action Grid {Unmapped}
- Content Section {Unmapped}
- Card Grid {Unmapped}

### Responsible Supply Chain — group 41 (`tpl_40`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Card Grid

### Protecting Human Rights And Workplace Safety — group 42 (`tpl_41`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Introduction {Unmapped}
- Featured Story Card
- Recognition Stats {Unmapped}

### Precision Medicine — group 43 (`tpl_42`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Card Grid
- Footer

### A History Of Impact — group 44 (`tpl_43`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Milestones Timeline {Unmapped}
- Footer

### Life At Abbvie — group 45 (`tpl_44`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Transparency In Payment — group 47 (`tpl_46`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- CTA Grid {Unmapped}
- Content Columns {Unmapped}

### Benefits — group 48 (`tpl_47`) — 1 pages

- Global Header
- Hero Section
- Benefits Overview {Unmapped}
- Featured Story {Unmapped}
- Recognition Highlight {Unmapped}

### Aesthetics — group 49 (`tpl_48`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Columns
- Card Grid

### Products — group 50 (`tpl_49`) — 1 pages

- Global Header

### Equity Equality Inclusion Diversity — group 51 (`tpl_50`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Content Columns {Unmapped}
- Card Grid {Unmapped}
- Back to Top Button {Unmapped}

### Grants And Contribution Disclosures — group 52 (`tpl_51`) — 1 pages

- Global Header
- Hero Section
- Primary Navigation {Unmapped}
- Content Section {Unmapped}
- Footer

### How To Apply — group 54 (`tpl_53`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer Links

### Brand Partnerships — group 55 (`tpl_54`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Column One {Unmapped}
- Content Column Two {Unmapped}

### Areas Of Focus — group 56 (`tpl_55`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Areas of Focus Section {Unmapped}

### Genomics — group 57 (`tpl_56`) — 1 pages

- Global Header {Unmapped}
- Hero Section
- Primary Navigation {Unmapped}
- Content Introduction {Unmapped}
- Card Grid
- Back to Top Button {Unmapped}

### Requestor Training Guide — group 58 (`tpl_57`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Allergan Aesthetics — group 59 (`tpl_58`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Living With An Illness — group 60 (`tpl_59`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content Introduction {Unmapped}
- Main CTA Button {Unmapped}
- Featured Card Grid {Unmapped}

### Page layout group 61 (`tpl_60`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Investigator Initiated Studies — group 62 (`tpl_61`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Card Grid {Unmapped}

### Learning And Development — group 63 (`tpl_62`) — 1 pages

- Utility Strip {Unmapped}
- Main Navigation {Unmapped}
- Hero Section
- Call to Action Section {Unmapped}
- Card Grid
- Back to Top Button {Unmapped}

### Request Types — group 64 (`tpl_63`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content Section {Unmapped}

### Therapeutic Modalities And Platforms — group 65 (`tpl_64`) — 1 pages

- Site Header
- Hero Banner
- Main Navigation {Unmapped}
- Content Area {Unmapped}
- Back to Top Button {Unmapped}

### Contact Center — group 66 (`tpl_65`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Who We Are CTA {Unmapped}
- Science CTA {Unmapped}

### Abbvie Inquiry — group 67 (`tpl_66`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Jag Dosanjh — group 68 (`tpl_67`) — 1 pages

- Global Navigation {Unmapped}
- Main Content {Unmapped}
- Footer

### Join Us — group 69 (`tpl_68`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Student And New Graduates — group 70 (`tpl_69`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Who We Are Section {Unmapped}
- Science Section {Unmapped}
- Patients Section {Unmapped}

### Sustainability — group 71 (`tpl_70`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top Button {Unmapped}

### Environmental Social And Governance — group 72 (`tpl_71`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### United States — group 74 (`tpl_73`) — 1 pages

- Global Header
- Hero Section
- Who We Are Section {Unmapped}
- Science Section {Unmapped}
- Patients Section {Unmapped}

### Latif Akintade — group 75 (`tpl_74`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Introduction {Unmapped}
- Call-to-Action Buttons {Unmapped}

### Robert Michael — group 76 (`tpl_75`) — 1 pages

- Global Navigation {Unmapped}
- Hero Banner
- About Section {Unmapped}
- Call-to-Action Button {Unmapped}
- Featured Card

### Why Abbvie — group 77 (`tpl_76`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Liz Shea — group 78 (`tpl_77`) — 1 pages

- Global Header {Unmapped}
- Hero Section {Unmapped}
- Primary Navigation {Unmapped}
- Main Content Area {Unmapped}
- Back to Top Button {Unmapped}

### New Graduates And Entry Level Positions — group 79 (`tpl_78`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Who We Are Section {Unmapped}
- Science Section {Unmapped}
- Patients Section {Unmapped}

### Nicholas Donoghoe — group 80 (`tpl_79`) — 1 pages

- Global Header {Unmapped}
- Hero Section
- Primary Navigation {Unmapped}
- Content Introduction {Unmapped}
- Call-to-Action Button {Unmapped}
- Card Grid

### Page layout group 81 (`tpl_80`) — 1 pages

- Global Header {Unmapped}
- Hero Section {Unmapped}
- Main Navigation {Unmapped}
- Content Introduction {Unmapped}
- Related Links {Unmapped}
- Featured Card {Unmapped}
- Footer {Unmapped}

### Algeria — group 82 (`tpl_81`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Who We Are Section {Unmapped}
- Science Section {Unmapped}
- Patients Section {Unmapped}
- Card Grid {Unmapped}

### Supplier Resources — group 83 (`tpl_82`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Card Grid Highlights
- Dashboard Facts {Unmapped}

### Internships — group 84 (`tpl_83`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Croatia — group 85 (`tpl_84`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Introduction {Unmapped}
- Call-to-Action Buttons {Unmapped}
- Link List {Unmapped}
- Card Grid {Unmapped}

### Jeffrey Stewart — group 86 (`tpl_85`) — 1 pages

- Primary Navigation {Unmapped}
- Hero Section
- Content Introduction {Unmapped}
- Call to Action Buttons {Unmapped}
- Link List {Unmapped}
- Profile Card
- Data Highlight {Unmapped}

### Page layout group 87 (`tpl_86`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Card Grid Section

### Lebanon — group 88 (`tpl_87`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Grid {Unmapped}
- Card Grid

### Lithuania — group 89 (`tpl_88`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Section: Who We Are {Unmapped}
- Content Section: Science {Unmapped}
- Content Section: Patients {Unmapped}
- Footer Navigation {Unmapped}

### Nicole Mowad Nassar — group 90 (`tpl_89`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Disaster Relief — group 91 (`tpl_90`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Estonia — group 92 (`tpl_91`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Who We Are Section {Unmapped}
- Science Section {Unmapped}
- Patients Section {Unmapped}

### Student Programs — group 93 (`tpl_92`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Prose Content Columns {Unmapped}
- Back to Top Button {Unmapped}

### Page layout group 94 (`tpl_93`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Story Cards
- Footer

### Bosnia And Herzegovina — group 95 (`tpl_94`) — 1 pages

- Site Navigation Header
- Hero Banner
- Who We Are Section {Unmapped}
- Science Section {Unmapped}
- Patients Section {Unmapped}

### Allergan Ous Disclosures — group 96 (`tpl_95`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Serbia — group 97 (`tpl_96`) — 1 pages

- Global Header
- Hero Section
- Primary Navigation {Unmapped}
- Content Section 1 {Unmapped}
- Content Section 2 {Unmapped}
- Content Section 3 {Unmapped}

### Roopal Thakkar — group 98 (`tpl_97`) — 1 pages

- Site Header
- Hero Banner
- Main Navigation {Unmapped}
- Content Introduction {Unmapped}
- Content Cards

### Page layout group 99 (`tpl_98`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Well Being In The Workplace — group 100 (`tpl_99`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Timothy Richmond — group 101 (`tpl_100`) — 1 pages

- Global Header {Unmapped}
- Footer

### Resources — group 102 (`tpl_101`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Cards Grid

### Alberto Colzi — group 103 (`tpl_102`) — 1 pages

- Global Header
- Hero Section
- Main Navigation {Unmapped}
- Footer

### Accessibility Statement — group 104 (`tpl_103`) — 1 pages

- Global Header {Unmapped}
- Main Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Grid {Unmapped}

### Saudi Arabia — group 105 (`tpl_104`) — 1 pages

- Primary Navigation {Unmapped}
- Hero Section
- Content Columns {Unmapped}
- Card Grid
- Footer

### Perry Siatis — group 106 (`tpl_105`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer Section

### Impact Through Inclusion — group 107 (`tpl_106`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content Area {Unmapped}
- Footer Section

### Slovenia — group 108 (`tpl_107`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Cards

### Tunisia — group 109 (`tpl_108`) — 1 pages

- Utility Bar
- Primary Navigation
- Site Search
- Cookie Preferences {Unmapped}

### Romania — group 110 (`tpl_109`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Grid {Unmapped}

### Azita Saleki Gerhardt — group 111 (`tpl_110`) — 1 pages

- Global Header
- Hero Section
- Primary Navigation {Unmapped}
- Main Content {Unmapped}

### South Africa And Sub Saharan Africa — group 112 (`tpl_111`) — 1 pages

- Primary Navigation {Unmapped}
- Hero Section
- Content Introduction {Unmapped}
- Call-to-Action Buttons {Unmapped}
- Card Grid
- Back to Top Button {Unmapped}

### Latvia — group 113 (`tpl_112`) — 1 pages

- Global Utility Bar {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Call-to-Actions {Unmapped}
- Grid of Cards {Unmapped}

### Scott Reents — group 114 (`tpl_113`) — 1 pages

- Primary Navigation
- Hero Section
- Content Section
- Card Grid

### United Arab Emirates — group 116 (`tpl_115`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Section {Unmapped}
- Card Grid

### Addressing Systemic Barriers — group 117 (`tpl_116`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Section 1 {Unmapped}
- Content Section 2 {Unmapped}

### Postdoctoral Program — group 118 (`tpl_117`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Highlight {Unmapped}
- Call-to-Action Grid {Unmapped}

### Page layout group 119 (`tpl_118`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Story Cards Grid
- Dashboard Cards {Unmapped}

### Innovative Impact — group 120 (`tpl_119`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content {Unmapped}
- Card Grid {Unmapped}
- Back to Top {Unmapped}

### Employee Resource Groups — group 121 (`tpl_120`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Introduction {Unmapped}
- Call to Action Button {Unmapped}
- Link List {Unmapped}
- Card Grid
- Dashboard Cards {Unmapped}

### Site Map — group 122 (`tpl_121`) — 1 pages

- Global Header
- Hero Section
- Main Navigation {Unmapped}
- Primary Content {Unmapped}
- Footer Section

### Wulff Erik Von Borcke — group 123 (`tpl_122`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Page layout group 124 (`tpl_123`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer Navigation

### Tracie Haas — group 125 (`tpl_124`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Page layout group 126 (`tpl_125`) — 1 pages

- Global Header {Unmapped}
- Hero Section {Unmapped}
- Primary Navigation {Unmapped}
- Main Content {Unmapped}

### Page layout group 127 (`tpl_126`) — 1 pages

- Utility Strip
- Primary Navigation
- Hero Section
- Introductory Content {Unmapped}
- Call-to-Action {Unmapped}
- Card Grid
- Back-to-Top Button {Unmapped}

### Demetris Crum — group 128 (`tpl_127`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call to Action Section {Unmapped}
- Profiles Card Grid
- Dashboard Facts {Unmapped}

### Abbvie Volunteers Return To Serving — group 129 (`tpl_128`) — 1 pages

- Global Utility Bar {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content Area {Unmapped}
- Card Grid

### Btk Protein Good Bad And Ugly — group 130 (`tpl_129`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Introduction {Unmapped}
- Main Story {Unmapped}
- Additional Links {Unmapped}

### Jerome Bouyer — group 131 (`tpl_130`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer Navigation {Unmapped}
- Back to Top Button {Unmapped}

### Linda Ray — group 132 (`tpl_131`) — 1 pages

- Site-wide Navigation {Unmapped}
- Hero Banner
- Page Content {Unmapped}
- Footer Section

### Everyones Talking About Data Science — group 133 (`tpl_132`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Cards

### The Power Love In Ibd — group 134 (`tpl_133`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Content Introduction {Unmapped}
- Call to Action {Unmapped}
- Related Links {Unmapped}
- Featured Story Card
- Dashboard Card {Unmapped}

### Page layout group 135 (`tpl_134`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Magnified Featuring Linda Scarazzini — group 136 (`tpl_135`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content {Unmapped}

### How Patient Voices Are Changing Medicine — group 137 (`tpl_136`) — 1 pages

- Primary Navigation {Unmapped}
- Main Content {Unmapped}

### Inside Dream Initiative — group 138 (`tpl_137`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Introduction {Unmapped}
- Featured Story {Unmapped}
- Data Highlight {Unmapped}
- Footer Section

### Dave Purdue — group 139 (`tpl_138`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Lead Content {Unmapped}

### Page layout group 140 (`tpl_139`) — 1 pages

- Global Utility Links {Unmapped}
- Main Navigation {Unmapped}
- Multi-Column Call-to-Actions {Unmapped}
- Card Grid Teasers {Unmapped}
- Prose Content Columns {Unmapped}
- Back to Top Button {Unmapped}

### Page layout group 141 (`tpl_140`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content Area {Unmapped}
- Card Grid
- Back to Top Button {Unmapped}

### Page layout group 142 (`tpl_141`) — 1 pages

- Global Header
- Primary Navigation {Unmapped}

### Page layout group 143 (`tpl_142`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Cards {Unmapped}
- Call-to-Action Buttons {Unmapped}
- Back to Top Button {Unmapped}

### Can Unlocking One Million Genomes — group 144 (`tpl_143`) — 1 pages

- Global Header
- Hero Section
- Primary Navigation {Unmapped}

### They Wont Back Down — group 145 (`tpl_144`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content Section {Unmapped}
- Story Highlight {Unmapped}
- Footer Section

### Page layout group 146 (`tpl_145`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Article {Unmapped}
- Footer

### Page layout group 147 (`tpl_146`) — 1 pages

- Utility Navigation
- Primary Navigation
- Introductory Content {Unmapped}
- Call-to-Action Button {Unmapped}
- Related Links {Unmapped}
- Featured Story Card
- Dashboard Metrics Card
- Secondary Navigation
- Science Section Introduction {Unmapped}
- Science Call-to-Action {Unmapped}
- Science Related Links {Unmapped}
- Science Story Card
- Science Metrics Card

### Page layout group 148 (`tpl_147`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Cards

### Page layout group 149 (`tpl_148`) — 1 pages

- Primary Navigation {Unmapped}
- Hero Section
- Story Highlights {Unmapped}
- Call-to-Action Grid {Unmapped}

### Page layout group 150 (`tpl_149`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Story Cards Grid
- Dashboard Cards

### Living With Unknowns Alzheimers Disease — group 151 (`tpl_150`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content {Unmapped}

### Page layout group 152 (`tpl_151`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top Button {Unmapped}

### Magnified Featuring Matt Widman — group 153 (`tpl_152`) — 1 pages

- Primary Navigation {Unmapped}
- Card Grid Section

### Jason Smith — group 154 (`tpl_153`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Page layout group 155 (`tpl_154`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer Links {Unmapped}

### Magnified Featuring Jonathon Sedgwick — group 156 (`tpl_155`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Page layout group 157 (`tpl_156`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Story Highlight {Unmapped}
- Content Cards

### Page layout group 158 (`tpl_157`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Page layout group 159 (`tpl_158`) — 1 pages

- Global Navigation {Unmapped}
- Main Content {Unmapped}

### Trapped In Your Own Skin — group 160 (`tpl_159`) — 1 pages

- Global Header {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section

### Why Isnt Medicine One Size Fits All — group 161 (`tpl_160`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Introduction {Unmapped}
- Card Grid

### Page layout group 162 (`tpl_161`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Teaser Cards
- Prose Columns {Unmapped}

### Page layout group 163 (`tpl_162`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Primary Call to Action {Unmapped}
- Card Grid
- Footer

### Page layout group 164 (`tpl_163`) — 1 pages

- Global Header
- Main Content {Unmapped}
- Footer

### Magnified Featuring Shuhong Zhang — group 165 (`tpl_164`) — 1 pages

- Primary Navigation {Unmapped}
- Hero Section
- Content Cards

### Page layout group 166 (`tpl_165`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Teasers {Unmapped}

### The Math Of Migraine — group 167 (`tpl_166`) — 1 pages

- Global Utility Bar {Unmapped}
- Site Navigation {Unmapped}
- Story Cards
- Data Cards

### Magnified Featuring Darin Messina — group 168 (`tpl_167`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Magnified Featuring Sean Mcewen — group 169 (`tpl_168`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content {Unmapped}

### A Journey Of Sight Progress — group 170 (`tpl_169`) — 1 pages

- Global Header {Unmapped}
- Primary Navigation {Unmapped}
- Story Highlight {Unmapped}
- Dashboard Cards {Unmapped}

### What Does It Take To Discover A New Medicine — group 171 (`tpl_170`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Introduction {Unmapped}
- Main Call to Action {Unmapped}
- Link List {Unmapped}
- Featured Story Card {Unmapped}
- Data Highlight Card {Unmapped}

### Shining Light On Glaucoma And Eye Health — group 172 (`tpl_171`) — 1 pages

- Global Navigation {Unmapped}
- Main Content {Unmapped}
- Footer

### Page layout group 173 (`tpl_172`) — 1 pages

- Global Header
- Main Navigation {Unmapped}
- Content Section {Unmapped}
- Footer

### Page layout group 174 (`tpl_173`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Story Content {Unmapped}
- Related Articles {Unmapped}

### Navigating Ulcerative Colitis As A Child — group 175 (`tpl_174`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content {Unmapped}

### Page layout group 176 (`tpl_175`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Introduction {Unmapped}
- Content Cards {Unmapped}

### Page layout group 177 (`tpl_176`) — 1 pages

- Global Site Header
- Hero Image Section
- Primary Navigation {Unmapped}
- Main Content Area {Unmapped}
- Site Footer

### Page layout group 178 (`tpl_177`) — 1 pages

- Global Navigation {Unmapped}
- Main Content {Unmapped}

### Page layout group 179 (`tpl_178`) — 1 pages

- Global Header
- Hero Section
- Main Navigation {Unmapped}
- Content Introduction {Unmapped}
- Call to Action Button {Unmapped}
- Featured Cards

### Page layout group 180 (`tpl_179`) — 1 pages

- Site Header
- Hero Banner
- Main Content Area {Unmapped}

### Stronger Together Convergence Minds And Data — group 181 (`tpl_180`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Page layout group 182 (`tpl_181`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Chasing The Value Of A Walk Down The Aisle — group 183 (`tpl_182`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Cards
- Dashboard Cards {Unmapped}

### Page layout group 184 (`tpl_183`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Page layout group 185 (`tpl_184`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content Area {Unmapped}
- Footer

### Page layout group 186 (`tpl_185`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Nisha Patel Burns — group 187 (`tpl_186`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Lead Content {Unmapped}
- Back to Top {Unmapped}

### Injecting Hope One Vaccine At A Time — group 188 (`tpl_187`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content Introduction {Unmapped}
- Related Content Cards {Unmapped}

### Profile Stories — group 189 (`tpl_188`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Profile Stories Grid {Unmapped}

### Magnified Featuring Edrice Simmons — group 190 (`tpl_189`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Company Stories — group 191 (`tpl_190`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Card Grid

### Eedi Stories — group 192 (`tpl_191`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Story Cards
- Dashboard Cards

### Sustainability Stories — group 193 (`tpl_192`) — 1 pages

- Global Utility Strip
- Primary Navigation
- Hero Section
- Featured Story Card
- Card Grid
- Footer Navigation
- Back to Top Button {Unmapped}

### Abbvie Research Collaborative — group 194 (`tpl_193`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Multi-Column Call to Actions {Unmapped}
- Card Grid {Unmapped}

### Page layout group 195 (`tpl_194`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### A Legacy Of Leadership In Mental Health — group 196 (`tpl_195`) — 1 pages

- Global Utility Strip
- Primary Navigation
- Hero Section
- Main Content {Unmapped}
- Card Grid
- Back to Top Button {Unmapped}

### Magnified Featuring Johanna Corbin — group 197 (`tpl_196`) — 1 pages

- Global Navigation {Unmapped}
- Main Content {Unmapped}

### Page layout group 198 (`tpl_197`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Multi-Column CTAs {Unmapped}
- Card Grid
- Back to Top Button {Unmapped}

### Voices Abbvie Reflecting On Decade Impact — group 199 (`tpl_198`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content Area {Unmapped}
- Footer

### Page layout group 200 (`tpl_199`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content Area {Unmapped}

### Page layout group 201 (`tpl_200`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Related Links {Unmapped}
- Back to Top Button {Unmapped}

### Science Stories — group 202 (`tpl_201`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Science Story Card {Unmapped}
- Dashboard Facts {Unmapped}

### Why You Cant Wait With Rheumatoid Arthritis — group 203 (`tpl_202`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Footer

### Page layout group 204 (`tpl_203`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Introduction {Unmapped}
- Card Grid {Unmapped}
- Footer {Unmapped}

### Page layout group 205 (`tpl_204`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Story Highlights {Unmapped}
- Recognition Facts {Unmapped}
- Science Section {Unmapped}
- Science Highlights {Unmapped}

### Page layout group 206 (`tpl_205`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Back to Top Button {Unmapped}

### Page layout group 207 (`tpl_206`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Story Content {Unmapped}
- Related Links {Unmapped}

### Page layout group 208 (`tpl_207`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer Navigation
- Back to Top Button {Unmapped}

### Digital Science Lab — group 209 (`tpl_208`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Grid {Unmapped}
- Call-to-Action Section {Unmapped}

### Immunologys Next Frontier — group 210 (`tpl_209`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Grid {Unmapped}

### Magnified Featuring Nicholas Donoghoe — group 211 (`tpl_210`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Card Grid Stories {Unmapped}
- Dashboard Cards {Unmapped}
- Back to Top Button {Unmapped}

### Eye Care Stories — group 212 (`tpl_211`) — 1 pages

- Primary Navigation {Unmapped}
- Card Grid

### Time Is Hours — group 213 (`tpl_212`) — 1 pages

- Global Utility Strip
- Primary Navigation
- Hero Section
- Story Card Grid
- Dashboard Cards
- Footer Navigation
- Back to Top Button {Unmapped}

### Page layout group 214 (`tpl_213`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}
- Footer Section

### Neuroscience Stories — group 215 (`tpl_214`) — 1 pages

- Global Header {Unmapped}
- Hero Section {Unmapped}
- Primary Navigation {Unmapped}
- Content Card Grid {Unmapped}
- Content Columns {Unmapped}

### Page layout group 216 (`tpl_215`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content {Unmapped}

### Immunology Stories — group 217 (`tpl_216`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top Button {Unmapped}

### Page layout group 218 (`tpl_217`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Story Content {Unmapped}
- Related Links {Unmapped}

### Page layout group 219 (`tpl_218`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation Bar {Unmapped}
- Main Content Area {Unmapped}

### Page layout group 220 (`tpl_219`) — 1 pages

- Global Header {Unmapped}
- Primary Navigation {Unmapped}
- Main Content {Unmapped}
- Footer

### Page layout group 221 (`tpl_220`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Page layout group 222 (`tpl_221`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}
- Story Cards {Unmapped}
- Footer

### Page layout group 223 (`tpl_222`) — 1 pages

- Utility Links {Unmapped}
- Main Navigation {Unmapped}
- Hero Banner
- Card Grid

### Oncology Stories — group 224 (`tpl_223`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Content Cards

### Page layout group 225 (`tpl_224`) — 1 pages

- Global Utility Links {Unmapped}
- Primary Navigation Bar {Unmapped}
- Hero Banner {Unmapped}
- Page Main Content {Unmapped}

### Page layout group 226 (`tpl_225`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Grid {Unmapped}

### Transforming Cancer Care From The Inside Out — group 227 (`tpl_226`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content CTA {Unmapped}
- Card Grid

### Aesthetics Stories — group 228 (`tpl_227`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Content Grid {Unmapped}

### Can We Find Cures Faster — group 229 (`tpl_228`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Content Cards

### Navigating The Hidden Side Of Cancer — group 230 (`tpl_229`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Primary Call-to-Action {Unmapped}
- Content Cards

### Ambassadors In Action — group 231 (`tpl_230`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content Introduction {Unmapped}
- Card Grid {Unmapped}

### Working At Abbvie Stories — group 232 (`tpl_231`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Card Grid - Stories
- Dashboard Facts {Unmapped}

### Page layout group 233 (`tpl_232`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Card Grid

### Page layout group 234 (`tpl_233`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Cards {Unmapped}

### Elevating Health Care For All — group 235 (`tpl_234`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section

### Page layout group 236 (`tpl_235`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Page layout group 237 (`tpl_236`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Story Content {Unmapped}
- Footer Navigation
- Back to Top Button {Unmapped}

### Page layout group 238 (`tpl_237`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content {Unmapped}

### Page layout group 239 (`tpl_238`) — 1 pages

- Global Navigation {Unmapped}

### Real People Real Inspiration Joes Story — group 240 (`tpl_239`) — 1 pages

- Utility Links {Unmapped}
- Main Navigation {Unmapped}
- Hero Banner
- Content Layout {Unmapped}
- Action Buttons {Unmapped}
- Card Grid

### Page layout group 241 (`tpl_240`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top Button {Unmapped}

### Philanthropy Stories — group 242 (`tpl_241`) — 1 pages

- Global Header {Unmapped}
- Hero Section
- Primary Navigation {Unmapped}
- Content Cards
- Back to Top Button {Unmapped}

### Serving Communities Stories — group 243 (`tpl_242`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Virology Stories — group 244 (`tpl_243`) — 1 pages

- Main Navigation {Unmapped}
- Hero Section
- Card Grid

### Synthetic Control Arm End Placebos — group 245 (`tpl_244`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content Area {Unmapped}
- Card Grid {Unmapped}

### Little Patients Big Impact — group 246 (`tpl_245`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Highlight {Unmapped}
- Call-to-Action Buttons {Unmapped}

### Page layout group 247 (`tpl_246`) — 1 pages

- Global Header {Unmapped}
- Hero Section {Unmapped}
- Main Navigation {Unmapped}
- Content Introduction {Unmapped}
- Featured Card {Unmapped}
- Dashboard Cards {Unmapped}

### Patient Support Stories — group 248 (`tpl_247`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Card Grid {Unmapped}

### Page layout group 249 (`tpl_248`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content {Unmapped}

### Change From Within — group 250 (`tpl_249`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content {Unmapped}
- Footer

### Partnerships Stories — group 251 (`tpl_250`) — 1 pages

- Global Header
- Hero Section
- Main Navigation {Unmapped}
- Primary Story Card
- Secondary Story Grid

### Page layout group 252 (`tpl_251`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Bay Area Opportunities — group 253 (`tpl_252`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Introduction Content {Unmapped}
- Carousel Gallery
- Focus Areas {Unmapped}
- Campus Tour CTA {Unmapped}

### Social Media Community Guidelines — group 254 (`tpl_253`) — 1 pages

- Global Header
- Primary Navigation {Unmapped}
- Hero Section
- Content Section {Unmapped}
- Footer Section

### Cerevel — group 255 (`tpl_254`) — 1 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Hero Banner {Unmapped}
- Intro Text Block {Unmapped}
- Neuroscience Info {Unmapped}
- Page Footer

### Mitokinin — group 256 (`tpl_255`) — 1 pages

- Global Header
- Hero Section
- Introductory Content {Unmapped}
- Neuroscience Section {Unmapped}
- Footer
- Back to Top Button {Unmapped}

### Celsius Therapeutics — group 257 (`tpl_256`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Hero Area {Unmapped}
- Lead Content Area {Unmapped}
- Immunology Feature {Unmapped}
- Footer Navigation {Unmapped}
- Footer Social Links {Unmapped}
- Footer Legal Links {Unmapped}
- Back to Top Button {Unmapped}

### Immunogen — group 258 (`tpl_257`) — 1 pages

- Global Utility Strip {Unmapped}
- Hero Section
- Introduction Text {Unmapped}
- Oncology Section {Unmapped}
- Clinical Trials Section {Unmapped}
- Footer

### Discovery Files — group 259 (`tpl_258`) — 1 pages

- Global Header {Unmapped}
- Hero Section
- Primary Navigation {Unmapped}
- Content Section 1 {Unmapped}
- Content Section 2 {Unmapped}
- Card Grid {Unmapped}

### Allergan — group 260 (`tpl_259`) — 1 pages

- Site Header
- Site Search
- Cookie Preferences {Unmapped}

### Behind The Science — group 261 (`tpl_260`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}
- Card Grid

### Linda Scarazzini — group 262 (`tpl_261`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Columns {Unmapped}
- Footer Links {Unmapped}

### Equal Employment Opportunity Employer — group 263 (`tpl_262`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Multi-Column CTAs {Unmapped}
- Card Grid {Unmapped}

### Capstan Therapeutics — group 264 (`tpl_263`) — 1 pages

- Utility Navigation {Unmapped}
- Main Navigation {Unmapped}
- Hero Section {Unmapped}
- Announcement Section {Unmapped}
- Immunology Section {Unmapped}
- Footer Links
- Social Links
- Legal Links
- Back to Top {Unmapped}

### Savings Card — group 265 (`tpl_264`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Card Grid Section {Unmapped}

### Available Programs — group 266 (`tpl_265`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Programs List {Unmapped}
- Featured Story {Unmapped}
- Recognition Facts {Unmapped}

### Eligibility Criteria — group 267 (`tpl_266`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Science In 60 Seconds — group 268 (`tpl_267`) — 1 pages

- Utility Links {Unmapped}
- Site Navigation {Unmapped}
- Hero Banner
- Content Cards

### Aliada Therapeutics — group 269 (`tpl_268`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Who We Are Section {Unmapped}
- Science Section {Unmapped}
- Science Card

### Contactus — group 270 (`tpl_269`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Online Application Overview — group 271 (`tpl_270`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Card Grid

### Locations — group 272 (`tpl_271`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Daejin Abidoye — group 273 (`tpl_272`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Primary Content {Unmapped}

### Wolfram Nothaft — group 274 (`tpl_273`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Content Introduction {Unmapped}
- Card Grid

### Eleni Lagkadinou — group 275 (`tpl_274`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer Links

### Raymond Votzmeyer — group 276 (`tpl_275`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}
- Footer

### Abbvie Pride — group 277 (`tpl_276`) — 1 pages

- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Grid {Unmapped}

### Income Criteria — group 278 (`tpl_277`) — 1 pages

- Global Header {Unmapped}
- Hero Section
- Navigation Menu {Unmapped}
- Content Introduction {Unmapped}
- Call-to-Action Button {Unmapped}
- Link List {Unmapped}
- Card Section

### Philip Hajduk — group 279 (`tpl_278`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Main Content {Unmapped}

### Access To Investigational Drugs Policy — group 280 (`tpl_279`) — 1 pages

- Global Header {Unmapped}
- Hero Section {Unmapped}
- Primary Navigation {Unmapped}

### Michael Foley — group 281 (`tpl_280`) — 1 pages

- Global Navigation {Unmapped}

### Page layout group 282 (`tpl_281`) — 1 pages

- Global Header {Unmapped}
- Hero Section
- Primary Navigation {Unmapped}
- Content Introduction {Unmapped}
- Feature Card One
- Feature Card Two

### Asian Leadership Network — group 283 (`tpl_282`) — 1 pages

- Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Section {Unmapped}
- Card Grid
- Cookie Consent Banner {Unmapped}

### Veterans — group 284 (`tpl_283`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Card Grid {Unmapped}
- Back to Top Button {Unmapped}

### Human Capital Management — group 285 (`tpl_284`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Declaracion De Accessibilidad — group 286 (`tpl_285`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Content Cards

### Page layout group 287 (`tpl_286`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Section {Unmapped}
- Card Grid

### Patents — group 288 (`tpl_287`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section
- Call-to-Action Grid {Unmapped}

### Page layout group 289 (`tpl_288`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section

### Primal Kaur — group 290 (`tpl_289`) — 1 pages

- Primary Navigation {Unmapped}

### Reasonable Accommodations — group 291 (`tpl_290`) — 1 pages

- Global Header
- Hero Section
- Primary Navigation
- Content Section 1
- Content Section 2
- Content Section 3
- Footer

### Page layout group 292 (`tpl_291`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Footer Links {Unmapped}

### Ahora Hispanic Latino — group 293 (`tpl_292`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Abbvie Ventures Portfolio — group 294 (`tpl_293`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Call-to-Action Grid {Unmapped}
- Card Teasers {Unmapped}

### Environmental Sustainability — group 295 (`tpl_294`) — 1 pages

- Global Header {Unmapped}
- Hero Section
- Primary Navigation {Unmapped}
- Content Section {Unmapped}
- Card Grid

### Lab To Life — group 296 (`tpl_295`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Back to Top Button {Unmapped}

### Jonathon Sedgwick — group 297 (`tpl_296`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section

### Andrew Campbell — group 298 (`tpl_297`) — 1 pages

- Global Header
- Hero Section
- Navigation Menu {Unmapped}
- Main Content {Unmapped}

### Page layout group 299 (`tpl_298`) — 1 pages

- Utility Links {Unmapped}
- Main Navigation {Unmapped}
- Hero Image Section

### Lab Of The Future — group 300 (`tpl_299`) — 1 pages

- Utility Navigation
- Main Navigation
- Hero Section
- Call-to-Action Columns
- Card Grid

### Darin Messina — group 301 (`tpl_300`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section {Unmapped}
- Main Content {Unmapped}
- Footer {Unmapped}

### Ability At Abbvie — group 302 (`tpl_301`) — 1 pages

- Global Utility Strip
- Primary Navigation
- Hero Section
- Main Content {Unmapped}
- Footer

### Shuhong Zhang — group 303 (`tpl_302`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section {Unmapped}
- Footer

### Black Business Network — group 304 (`tpl_303`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- Hero Section {Unmapped}
- Content Introduction {Unmapped}
- Call-to-Action Button {Unmapped}
- Link List {Unmapped}
- Card Grid {Unmapped}

### Women Leaders In Action — group 305 (`tpl_304`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}

### Allergan Labeling — group 306 (`tpl_305`) — 1 pages

- Global Navigation {Unmapped}
- Hero Section
- Main Content {Unmapped}

### Page layout group 307 (`tpl_306`) — 1 pages

- Primary Navigation {Unmapped}
- Hero Section

### Nimbletherapeutics — group 309 (`tpl_308`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Header {Unmapped}
- Hero Section
- Lead Content {Unmapped}
- Immunology Section {Unmapped}
- Footer Section
- Back to Top Button {Unmapped}

### Privacy — group 310 (`tpl_309`) — 1 pages

- Utility Strip
- Primary Navigation
- Hero Section
- Introduction Paragraph {Unmapped}
- Three Column CTA
- Footer Navigation
- Cookie Settings
- Back to Top {Unmapped}
- Search Functionality
- Modal Disclaimer

### Partnerships Chicago Cubs — group 311 (`tpl_310`) — 1 pages

- Global Utility Strip {Unmapped}
- Primary Navigation {Unmapped}
- CTA Columns {Unmapped}
- Card Grid {Unmapped}

### Latest Earnings — group 312 (`tpl_311`) — 1 pages

- Global Utility Navigation {Unmapped}
- Primary Navigation {Unmapped}
- Site Search {Unmapped}
- Breadcrumb Navigation {Unmapped}
- Hero Banner {Unmapped}
- News Header {Unmapped}
- News Content {Unmapped}
- News Category Links {Unmapped}
- News Date {Unmapped}
- News Title {Unmapped}
- News Toolbar {Unmapped}
- News Body {Unmapped}
- Footer Contacts {Unmapped}

### Privacy Inquiry — group 313 (`tpl_312`) — 1 pages

- Global Header
- Hero Section
- Content Form
- Footer Section


## Component Reuse Matrix

*Rows use the same labels as **Blocks mapped per template**: primary UI/component name; items without an AEM catalog match include `{Unmapped}`.*

### High reuse components (used in 2+ templates)

```
┌──────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                            │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├──────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ Primary Navigation {Unmapped}        │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │ ✅   │ ❌   │
│ Global Utility Strip {Unmapped}      │ ✅   │ ❌   │ ✅   │ ✅   │ ✅   │ ✅   │ ❌   │
│ Hero Section                         │ ✅   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Card Grid                            │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Main Content {Unmapped}              │ ✅   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Back to Top Button {Unmapped}        │ ❌   │ ❌   │ ✅   │ ✅   │ ❌   │ ❌   │ ❌   │
│ Global Navigation {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │
│ Footer                               │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Hero Section {Unmapped}              │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Content Introduction {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Card Grid {Unmapped}                 │ ❌   │ ❌   │ ❌   │ ❌   │ ✅   │ ❌   │ ❌   │
│ Global Header {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Utility Strip {Unmapped}             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Global Header                        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└──────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T313 omitted from matrix width; see appendix.*


### Template-specific components

```
┌────────────────────────────────────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┐
│ Component                          │ T1  │ T2  │ T3  │ T4  │ T5  │ T6  │ T7  │
├────────────────────────────────────┼─────┼─────┼─────┼─────┼─────┼─────┼─────┤
│ About Section {Unmapped}           │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Action Buttons {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Additional Links {Unmapped}        │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Announcement Section {Unmapped}    │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Areas of Focus Section {Unmapped}  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Back-to-Top Button {Unmapped}      │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Benefits Overview {Unmapped}       │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Breadcrumb Navigation {Unmapped}   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call to Action {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call to Action Buttons {Unmapped}  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action {Unmapped}          │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Columns             │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Call-to-Action Columns {Unmapped}  │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
│ Campus Tour CTA {Unmapped}         │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │ ❌   │
└────────────────────────────────────┴─────┴─────┴─────┴─────┴─────┴─────┴─────┘
```
*T8…T313 omitted from matrix width; see appendix.*


## Development Priority Matrix

### Phase 1: Core templates (by page volume)

```
Priority: HIGH TRAFFIC / CORE
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Abbvie Foundation — group 115 (5 pgs)                                                             │
│ • Our Leaders — group 10 (4 pgs)                                                                    │
│ • Page layout group 2 (3 pgs)                                                                       │
│ • Major League Baseball — group 4 (2 pgs)                                                           │
│ • Our Rd Leaders — group 5 (2 pgs)                                                                  │
│ • Science — group 28 (2 pgs)                                                                        │
│ • Patient Assistance — group 36 (2 pgs)                                                             │
│ • Pipeline — group 46 (2 pgs)                                                                       │
│ • Ai And Data Convergence — group 53 (2 pgs)                                                        │
│ • Terms Of Use — group 73 (2 pgs)                                                                   │
│ • Abbvie Research Collaborative Endometrosis — group 308 (2 pgs)                                    │
│ • Oncology — group 1 (1 pgs)                                                                        │
│ • Policies Disclosures — group 3 (1 pgs)                                                            │
│ • Partnering Days — group 6 (1 pgs)                                                                 │
│ • Patient Focused Drug Development — group 7 (1 pgs)                                                │
│ • Independent Educational Grants — group 8 (1 pgs)                                                  │
│ • Commercial — group 9 (1 pgs)                                                                      │
│ • Cubs — group 11 (1 pgs)                                                                           │
│ • Eye Care — group 12 (1 pgs)                                                                       │
│ • Abbvies Code Of Conduct — group 13 (1 pgs)                                                        │
│ • Research And Development — group 14 (1 pgs)                                                       │
│ • Product Quality And Safety — group 15 (1 pgs)                                                     │
│ • Publications — group 16 (1 pgs)                                                                   │
│ • Areas Of Innovation — group 17 (1 pgs)                                                            │
│ • Operating With Integrity — group 18 (1 pgs)                                                       │
│ • Clinical Trials — group 19 (1 pgs)                                                                │
│ • Our People — group 20 (1 pgs)                                                                     │
│ • Neuroscience — group 21 (1 pgs)                                                                   │
│ • Who We Are — group 22 (1 pgs)                                                                     │
│ • Operations — group 23 (1 pgs)                                                                     │
│ • Patient Support — group 24 (1 pgs)                                                                │
│ • Immunology — group 25 (1 pgs)                                                                     │
│ • Abbvie Ventures — group 26 (1 pgs)                                                                │
│ • Key Facts — group 27 (1 pgs)                                                                      │
│ • Positions Views — group 29 (1 pgs)                                                                │
│ • Other Specialties — group 30 (1 pgs)                                                              │
│ • Corporate — group 31 (1 pgs)                                                                      │
│ • Rd Sites — group 32 (1 pgs)                                                                       │
│ • Patients — group 33 (1 pgs)                                                                       │
│ • Opportunities — group 34 (1 pgs)                                                                  │
│ • Partner With Us — group 35 (1 pgs)                                                                │
│ • Our Stories — group 37 (1 pgs)                                                                    │
│ • The Persistence Lab Podcasts — group 38 (1 pgs)                                                   │
│ • Community Of Science — group 39 (1 pgs)                                                           │
│ • Our Principles — group 40 (1 pgs)                                                                 │
│ • Responsible Supply Chain — group 41 (1 pgs)                                                       │
│ • Protecting Human Rights And Workplace Safety — group 42 (1 pgs)                                   │
│ • Precision Medicine — group 43 (1 pgs)                                                             │
│ • A History Of Impact — group 44 (1 pgs)                                                            │
│ • Life At Abbvie — group 45 (1 pgs)                                                                 │
│ • Transparency In Payment — group 47 (1 pgs)                                                        │
│ • Benefits — group 48 (1 pgs)                                                                       │
│ • Aesthetics — group 49 (1 pgs)                                                                     │
│ • Products — group 50 (1 pgs)                                                                       │
│ • Equity Equality Inclusion Diversity — group 51 (1 pgs)                                            │
│ • Grants And Contribution Disclosures — group 52 (1 pgs)                                            │
│ • How To Apply — group 54 (1 pgs)                                                                   │
│ • Brand Partnerships — group 55 (1 pgs)                                                             │
│ • Areas Of Focus — group 56 (1 pgs)                                                                 │
│ • Genomics — group 57 (1 pgs)                                                                       │
│ • Requestor Training Guide — group 58 (1 pgs)                                                       │
│ • Allergan Aesthetics — group 59 (1 pgs)                                                            │
│ • Living With An Illness — group 60 (1 pgs)                                                         │
│ • Page layout group 61 (1 pgs)                                                                      │
│ • Investigator Initiated Studies — group 62 (1 pgs)                                                 │
│ • Learning And Development — group 63 (1 pgs)                                                       │
│ • Request Types — group 64 (1 pgs)                                                                  │
│ • Therapeutic Modalities And Platforms — group 65 (1 pgs)                                           │
│ • Contact Center — group 66 (1 pgs)                                                                 │
│ • Abbvie Inquiry — group 67 (1 pgs)                                                                 │
│ • Jag Dosanjh — group 68 (1 pgs)                                                                    │
│ • Join Us — group 69 (1 pgs)                                                                        │
│ • Student And New Graduates — group 70 (1 pgs)                                                      │
│ • Sustainability — group 71 (1 pgs)                                                                 │
│ • Environmental Social And Governance — group 72 (1 pgs)                                            │
│ • United States — group 74 (1 pgs)                                                                  │
│ • Latif Akintade — group 75 (1 pgs)                                                                 │
│ • Robert Michael — group 76 (1 pgs)                                                                 │
│ • Why Abbvie — group 77 (1 pgs)                                                                     │
│ • Liz Shea — group 78 (1 pgs)                                                                       │
│ • New Graduates And Entry Level Positions — group 79 (1 pgs)                                        │
│ • Nicholas Donoghoe — group 80 (1 pgs)                                                              │
│ • Page layout group 81 (1 pgs)                                                                      │
│ • Algeria — group 82 (1 pgs)                                                                        │
│ • Supplier Resources — group 83 (1 pgs)                                                             │
│ • Internships — group 84 (1 pgs)                                                                    │
│ • Croatia — group 85 (1 pgs)                                                                        │
│ • Jeffrey Stewart — group 86 (1 pgs)                                                                │
│ • Page layout group 87 (1 pgs)                                                                      │
│ • Lebanon — group 88 (1 pgs)                                                                        │
│ • Lithuania — group 89 (1 pgs)                                                                      │
│ • Nicole Mowad Nassar — group 90 (1 pgs)                                                            │
│ • Disaster Relief — group 91 (1 pgs)                                                                │
│ • Estonia — group 92 (1 pgs)                                                                        │
│ • Student Programs — group 93 (1 pgs)                                                               │
│ • Page layout group 94 (1 pgs)                                                                      │
│ • Bosnia And Herzegovina — group 95 (1 pgs)                                                         │
│ • Allergan Ous Disclosures — group 96 (1 pgs)                                                       │
│ • Serbia — group 97 (1 pgs)                                                                         │
│ • Roopal Thakkar — group 98 (1 pgs)                                                                 │
│ • Page layout group 99 (1 pgs)                                                                      │
│ • Well Being In The Workplace — group 100 (1 pgs)                                                   │
│ • Timothy Richmond — group 101 (1 pgs)                                                              │
│ • Resources — group 102 (1 pgs)                                                                     │
│ • Alberto Colzi — group 103 (1 pgs)                                                                 │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 2: Secondary templates

```
Priority: MEDIUM TRAFFIC
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Accessibility Statement — group 104 (1 pgs)                                                       │
│ • Saudi Arabia — group 105 (1 pgs)                                                                  │
│ • Perry Siatis — group 106 (1 pgs)                                                                  │
│ • Impact Through Inclusion — group 107 (1 pgs)                                                      │
│ • Slovenia — group 108 (1 pgs)                                                                      │
│ • Tunisia — group 109 (1 pgs)                                                                       │
│ • Romania — group 110 (1 pgs)                                                                       │
│ • Azita Saleki Gerhardt — group 111 (1 pgs)                                                         │
│ • South Africa And Sub Saharan Africa — group 112 (1 pgs)                                           │
│ • Latvia — group 113 (1 pgs)                                                                        │
│ • Scott Reents — group 114 (1 pgs)                                                                  │
│ • United Arab Emirates — group 116 (1 pgs)                                                          │
│ • Addressing Systemic Barriers — group 117 (1 pgs)                                                  │
│ • Postdoctoral Program — group 118 (1 pgs)                                                          │
│ • Page layout group 119 (1 pgs)                                                                     │
│ • Innovative Impact — group 120 (1 pgs)                                                             │
│ • Employee Resource Groups — group 121 (1 pgs)                                                      │
│ • Site Map — group 122 (1 pgs)                                                                      │
│ • Wulff Erik Von Borcke — group 123 (1 pgs)                                                         │
│ • Page layout group 124 (1 pgs)                                                                     │
│ • Tracie Haas — group 125 (1 pgs)                                                                   │
│ • Page layout group 126 (1 pgs)                                                                     │
│ • Page layout group 127 (1 pgs)                                                                     │
│ • Demetris Crum — group 128 (1 pgs)                                                                 │
│ • Abbvie Volunteers Return To Serving — group 129 (1 pgs)                                           │
│ • Btk Protein Good Bad And Ugly — group 130 (1 pgs)                                                 │
│ • Jerome Bouyer — group 131 (1 pgs)                                                                 │
│ • Linda Ray — group 132 (1 pgs)                                                                     │
│ • Everyones Talking About Data Science — group 133 (1 pgs)                                          │
│ • The Power Love In Ibd — group 134 (1 pgs)                                                         │
│ • Page layout group 135 (1 pgs)                                                                     │
│ • Magnified Featuring Linda Scarazzini — group 136 (1 pgs)                                          │
│ • How Patient Voices Are Changing Medicine — group 137 (1 pgs)                                      │
│ • Inside Dream Initiative — group 138 (1 pgs)                                                       │
│ • Dave Purdue — group 139 (1 pgs)                                                                   │
│ • Page layout group 140 (1 pgs)                                                                     │
│ • Page layout group 141 (1 pgs)                                                                     │
│ • Page layout group 142 (1 pgs)                                                                     │
│ • Page layout group 143 (1 pgs)                                                                     │
│ • Can Unlocking One Million Genomes — group 144 (1 pgs)                                             │
│ • They Wont Back Down — group 145 (1 pgs)                                                           │
│ • Page layout group 146 (1 pgs)                                                                     │
│ • Page layout group 147 (1 pgs)                                                                     │
│ • Page layout group 148 (1 pgs)                                                                     │
│ • Page layout group 149 (1 pgs)                                                                     │
│ • Page layout group 150 (1 pgs)                                                                     │
│ • Living With Unknowns Alzheimers Disease — group 151 (1 pgs)                                       │
│ • Page layout group 152 (1 pgs)                                                                     │
│ • Magnified Featuring Matt Widman — group 153 (1 pgs)                                               │
│ • Jason Smith — group 154 (1 pgs)                                                                   │
│ • Page layout group 155 (1 pgs)                                                                     │
│ • Magnified Featuring Jonathon Sedgwick — group 156 (1 pgs)                                         │
│ • Page layout group 157 (1 pgs)                                                                     │
│ • Page layout group 158 (1 pgs)                                                                     │
│ • Page layout group 159 (1 pgs)                                                                     │
│ • Trapped In Your Own Skin — group 160 (1 pgs)                                                      │
│ • Why Isnt Medicine One Size Fits All — group 161 (1 pgs)                                           │
│ • Page layout group 162 (1 pgs)                                                                     │
│ • Page layout group 163 (1 pgs)                                                                     │
│ • Page layout group 164 (1 pgs)                                                                     │
│ • Magnified Featuring Shuhong Zhang — group 165 (1 pgs)                                             │
│ • Page layout group 166 (1 pgs)                                                                     │
│ • The Math Of Migraine — group 167 (1 pgs)                                                          │
│ • Magnified Featuring Darin Messina — group 168 (1 pgs)                                             │
│ • Magnified Featuring Sean Mcewen — group 169 (1 pgs)                                               │
│ • A Journey Of Sight Progress — group 170 (1 pgs)                                                   │
│ • What Does It Take To Discover A New Medicine — group 171 (1 pgs)                                  │
│ • Shining Light On Glaucoma And Eye Health — group 172 (1 pgs)                                      │
│ • Page layout group 173 (1 pgs)                                                                     │
│ • Page layout group 174 (1 pgs)                                                                     │
│ • Navigating Ulcerative Colitis As A Child — group 175 (1 pgs)                                      │
│ • Page layout group 176 (1 pgs)                                                                     │
│ • Page layout group 177 (1 pgs)                                                                     │
│ • Page layout group 178 (1 pgs)                                                                     │
│ • Page layout group 179 (1 pgs)                                                                     │
│ • Page layout group 180 (1 pgs)                                                                     │
│ • Stronger Together Convergence Minds And Data — group 181 (1 pgs)                                  │
│ • Page layout group 182 (1 pgs)                                                                     │
│ • Chasing The Value Of A Walk Down The Aisle — group 183 (1 pgs)                                    │
│ • Page layout group 184 (1 pgs)                                                                     │
│ • Page layout group 185 (1 pgs)                                                                     │
│ • Page layout group 186 (1 pgs)                                                                     │
│ • Nisha Patel Burns — group 187 (1 pgs)                                                             │
│ • Injecting Hope One Vaccine At A Time — group 188 (1 pgs)                                          │
│ • Profile Stories — group 189 (1 pgs)                                                               │
│ • Magnified Featuring Edrice Simmons — group 190 (1 pgs)                                            │
│ • Company Stories — group 191 (1 pgs)                                                               │
│ • Eedi Stories — group 192 (1 pgs)                                                                  │
│ • Sustainability Stories — group 193 (1 pgs)                                                        │
│ • Abbvie Research Collaborative — group 194 (1 pgs)                                                 │
│ • Page layout group 195 (1 pgs)                                                                     │
│ • A Legacy Of Leadership In Mental Health — group 196 (1 pgs)                                       │
│ • Magnified Featuring Johanna Corbin — group 197 (1 pgs)                                            │
│ • Page layout group 198 (1 pgs)                                                                     │
│ • Voices Abbvie Reflecting On Decade Impact — group 199 (1 pgs)                                     │
│ • Page layout group 200 (1 pgs)                                                                     │
│ • Page layout group 201 (1 pgs)                                                                     │
│ • Science Stories — group 202 (1 pgs)                                                               │
│ • Why You Cant Wait With Rheumatoid Arthritis — group 203 (1 pgs)                                   │
│ • Page layout group 204 (1 pgs)                                                                     │
│ • Page layout group 205 (1 pgs)                                                                     │
│ • Page layout group 206 (1 pgs)                                                                     │
│ • Page layout group 207 (1 pgs)                                                                     │
│ • Page layout group 208 (1 pgs)                                                                     │
│ • Digital Science Lab — group 209 (1 pgs)                                                           │
└──────────────────────────────────────────────────────────────────────────────────────────────────────┘
```


### Phase 3: Long-tail templates

```
Priority: LOWER TRAFFIC OR VARIANTS
┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ • Immunologys Next Frontier — group 210 (1 pgs)                                                     │
│ • Magnified Featuring Nicholas Donoghoe — group 211 (1 pgs)                                         │
│ • Eye Care Stories — group 212 (1 pgs)                                                              │
│ • Time Is Hours — group 213 (1 pgs)                                                                 │
│ • Page layout group 214 (1 pgs)                                                                     │
│ • Neuroscience Stories — group 215 (1 pgs)                                                          │
│ • Page layout group 216 (1 pgs)                                                                     │
│ • Immunology Stories — group 217 (1 pgs)                                                            │
│ • Page layout group 218 (1 pgs)                                                                     │
│ • Page layout group 219 (1 pgs)                                                                     │
│ • Page layout group 220 (1 pgs)                                                                     │
│ • Page layout group 221 (1 pgs)                                                                     │
│ • Page layout group 222 (1 pgs)                                                                     │
│ • Page layout group 223 (1 pgs)                                                                     │
│ • Oncology Stories — group 224 (1 pgs)                                                              │
│ • Page layout group 225 (1 pgs)                                                                     │
│ • Page layout group 226 (1 pgs)                                                                     │
│ • Transforming Cancer Care From The Inside Out — group 227 (1 pgs)                                  │
│ • Aesthetics Stories — group 228 (1 pgs)                                                            │
│ • Can We Find Cures Faster — group 229 (1 pgs)                                                      │
│ • Navigating The Hidden Side Of Cancer — group 230 (1 pgs)                                          │
│ • Ambassadors In Action — group 231 (1 pgs)                                                         │
│ • Working At Abbvie Stories — group 232 (1 pgs)                                                     │
│ • Page layout group 233 (1 pgs)                                                                     │
│ • Page layout group 234 (1 pgs)                                                                     │
│ • Elevating Health Care For All — group 235 (1 pgs)                                                 │
│ • Page layout group 236 (1 pgs)                                                                     │
│ • Page layout group 237 (1 pgs)                                                                     │
│ • Page layout group 238 (1 pgs)                                                                     │
│ • Page layout group 239 (1 pgs)                                                                     │
│ • Real People Real Inspiration Joes Story — group 240 (1 pgs)                                       │
│ • Page layout group 241 (1 pgs)                                                                     │
│ • Philanthropy Stories — group 242 (1 pgs)                                                          │
│ • Serving Communities Stories — group 243 (1 pgs)                                                   │
│ • Virology Stories — group 244 (1 pgs)                                                              │
│ • Synthetic Control Arm End Placebos — group 245 (1 pgs)                                            │
│ • Little Patients Big Impact — group 246 (1 pgs)                                                    │
│ • Page layout group 247 (1 pgs)                                                                     │
│ • Patient Support Stories — group 248 (1 pgs)                                                       │
│ • Page layout group 249 (1 pgs)                                                                     │
│ • Change From Within — group 250 (1 pgs)                                                            │
│ • Partnerships Stories — group 251 (1 pgs)                                                          │
│ • Page layout group 252 (1 pgs)                                                                     │
│ • Bay Area Opportunities — group 253 (1 pgs)                                                        │
│ • Social Media Community Guidelines — group 254 (1 pgs)                                             │
│ • Cerevel — group 255 (1 pgs)                                                                       │
│ • Mitokinin — group 256 (1 pgs)                                                                     │
│ • Celsius Therapeutics — group 257 (1 pgs)                                                          │
│ • Immunogen — group 258 (1 pgs)                                                                     │
│ • Discovery Files — group 259 (1 pgs)                                                               │
│ • Allergan — group 260 (1 pgs)                                                                      │
│ • Behind The Science — group 261 (1 pgs)                                                            │
│ • Linda Scarazzini — group 262 (1 pgs)                                                              │
│ • Equal Employment Opportunity Employer — group 263 (1 pgs)                                         │
│ • Capstan Therapeutics — group 264 (1 pgs)                                                          │
│ • Savings Card — group 265 (1 pgs)                                                                  │
│ • Available Programs — group 266 (1 pgs)                                                            │
│ • Eligibility Criteria — group 267 (1 pgs)                                                          │
│ • Science In 60 Seconds — group 268 (1 pgs)                                                         │
│ • Aliada Therapeutics — group 269 (1 pgs)                                                           │
│ • Contactus — group 270 (1 pgs)                                                                     │
│ • Online Application Overview — group 271 (1 pgs)                                                   │
│ • Locations — group 272 (1 pgs)                                                                     │
│ • Daejin Abidoye — group 273 (1 pgs)                                                                │
│ • Wolfram Nothaft — group 274 (1 pgs)                                                               │
│ • Eleni Lagkadinou — group 275 (1 pgs)                                                              │
│ • Raymond Votzmeyer — group 276 (1 pgs)                                                             │
│ • Abbvie Pride — group 277 (1 pgs)                                                                  │
│ • Income Criteria — group 278 (1 pgs)                                                               │
│ • Philip Hajduk — group 279 (1 pgs)                                                                 │
│ • Access To Investigational Drugs Policy — group 280 (1 pgs)                                        │
│ • Michael Foley — group 281 (1 pgs)                                                                 │
│ • Page layout group 282 (1 pgs)                                                                     │
│ • Asian Leadership Network — group 283 (1 pgs)                                                      │
│ • Veterans — group 284 (1 pgs)                                                                      │
│ • Human Capital Management — group 285 (1 pgs)                                                      │
│ • Declaracion De Accessibilidad — group 286 (1 pgs)                                                 │
│ • Page layout group 287 (1 pgs)                                                                     │
│ • Patents — group 288 (1 pgs)                                                                       │
│ • Page layout group 289 (1 pgs)                                                                     │
│ • Primal Kaur — group 290 (1 pgs)                                                                   │
│ • Reasonable Accommodations — group 291 (1 pgs)                                                     │
│ • Page layout group 292 (1 pgs)                                                                     │
│ • Ahora Hispanic Latino — group 293 (1 pgs)                                                         │
│ • Abbvie Ventures Portfolio — group 294 (1 pgs)                                                     │
│ • Environmental Sustainability — group 295 (1 pgs)                                                  │
│ • Lab To Life — group 296 (1 pgs)                                                                   │
│ • Jonathon Sedgwick — group 297 (1 pgs)                                                             │
│ • Andrew Campbell — group 298 (1 pgs)                                                               │
│ • Page layout group 299 (1 pgs)                                                                     │
│ • Lab Of The Future — group 300 (1 pgs)                                                             │
│ • Darin Messina — group 301 (1 pgs)                                                                 │
│ • Ability At Abbvie — group 302 (1 pgs)                                                             │
│ • Shuhong Zhang — group 303 (1 pgs)                                                                 │
│ • Black Business Network — group 304 (1 pgs)                                                        │
│ • Women Leaders In Action — group 305 (1 pgs)                                                       │
│ • Allergan Labeling — group 306 (1 pgs)                                                             │
│ • Page layout group 307 (1 pgs)                                                                     │
│ • Nimbletherapeutics — group 309 (1 pgs)                                                            │
│ • Privacy — group 310 (1 pgs)                                                                       │
│ • Partnerships Chicago Cubs — group 311 (1 pgs)                                                     │
│ • Latest Earnings — group 312 (1 pgs)                                                               │
│ • Privacy Inquiry — group 313 (1 pgs)                                                               │
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
| tpl_0 | Oncology — group 1 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/areas-of-focus/oncology.html | 1 |
| tpl_1 | Page layout group 2 | Same structural layout across 3 page(s) in the crawl. | https://www.abbvie.com/, https://www.abbvie.com/coronavirus.html, https://www.abbvie.com/covid-19crf.html | 3 |
| tpl_2 | Policies Disclosures — group 3 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/policies-disclosures.html | 1 |
| tpl_3 | Major League Baseball — group 4 | Same structural layout across 2 page(s) in the crawl. | https://www.abbvie.com/who-we-are/brand-partnerships/major-league-baseball.html, https://www.abbvie.com/MLB.html | 2 |
| tpl_4 | Our Rd Leaders — group 5 | Same structural layout across 2 page(s) in the crawl. | https://www.abbvie.com/science/our-people/our-rd-leaders.html, https://www.abbvie.com/science/our-people/our-rd-leaders/christopher-boone.html | 2 |
| tpl_5 | Partnering Days — group 6 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/partner-with-us/partnering-days.html | 1 |
| tpl_6 | Patient Focused Drug Development — group 7 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/areas-of-innovation/patient-focused-drug-development.html | 1 |
| tpl_7 | Independent Educational Grants — group 8 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/independent-educational-grants.html | 1 |
| tpl_8 | Commercial — group 9 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/opportunities/commercial.html | 1 |
| tpl_9 | Our Leaders — group 10 | Same structural layout across 4 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders.html, https://www.abbvie.com/who-we-are/our-leaders/thomas-hudson.html, https://www.abbvie.com/who-we-are/our-leaders/rae-livingston.html | 4 |
| tpl_10 | Cubs — group 11 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/brand-partnerships/cubs.html | 1 |
| tpl_11 | Eye Care — group 12 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/areas-of-focus/eye-care.html | 1 |
| tpl_12 | Abbvies Code Of Conduct — group 13 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/operating-with-integrity/abbvies-code-of-conduct.html | 1 |
| tpl_13 | Research And Development — group 14 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/opportunities/research-and-development.html | 1 |
| tpl_14 | Product Quality And Safety — group 15 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/patients/product-quality-and-safety.html | 1 |
| tpl_15 | Publications — group 16 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/publications.html | 1 |
| tpl_16 | Areas Of Innovation — group 17 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/areas-of-innovation.html | 1 |
| tpl_17 | Operating With Integrity — group 18 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/operating-with-integrity.html | 1 |
| tpl_18 | Clinical Trials — group 19 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/clinical-trials.html | 1 |
| tpl_19 | Our People — group 20 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people.html | 1 |
| tpl_20 | Neuroscience — group 21 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/areas-of-focus/neuroscience.html | 1 |
| tpl_21 | Who We Are — group 22 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are.html | 1 |
| tpl_22 | Operations — group 23 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/opportunities/operations.html | 1 |
| tpl_23 | Patient Support — group 24 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/patients/patient-support.html | 1 |
| tpl_24 | Immunology — group 25 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/areas-of-focus/immunology.html | 1 |
| tpl_25 | Abbvie Ventures — group 26 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/partner-with-us/abbvie-ventures.html | 1 |
| tpl_26 | Key Facts — group 27 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/key-facts.html | 1 |
| tpl_27 | Science — group 28 | Same structural layout across 2 page(s) in the crawl. | https://www.abbvie.com/science.html, https://www.abbvie.com/science/the-case-for-big-bets.html | 2 |
| tpl_28 | Positions Views — group 29 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-principles/positions-views.html | 1 |
| tpl_29 | Other Specialties — group 30 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/areas-of-focus/other-specialties.html | 1 |
| tpl_30 | Corporate — group 31 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/opportunities/corporate.html | 1 |
| tpl_31 | Rd Sites — group 32 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/rd-sites.html | 1 |
| tpl_32 | Patients — group 33 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/patients.html | 1 |
| tpl_33 | Opportunities — group 34 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/opportunities.html | 1 |
| tpl_34 | Partner With Us — group 35 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/partner-with-us.html | 1 |
| tpl_35 | Patient Assistance — group 36 | Same structural layout across 2 page(s) in the crawl. | https://www.abbvie.com/patients/patient-support/patient-assistance.html, https://www.abbvie.com/patients/patient-assistance.html | 2 |
| tpl_36 | Our Stories — group 37 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories.html | 1 |
| tpl_37 | The Persistence Lab Podcasts — group 38 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/the-persistence-lab-podcasts.html | 1 |
| tpl_38 | Community Of Science — group 39 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people/community-of-science.html | 1 |
| tpl_39 | Our Principles — group 40 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-principles.html | 1 |
| tpl_40 | Responsible Supply Chain — group 41 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/operating-with-integrity/responsible-supply-chain.html | 1 |
| tpl_41 | Protecting Human Rights And Workplace Safety — group 42 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/operating-with-integrity/protecting-human-rights-and-workplace-safety.html | 1 |
| tpl_42 | Precision Medicine — group 43 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/areas-of-innovation/precision-medicine.html | 1 |
| tpl_43 | A History Of Impact — group 44 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/landing/a-history-of-impact.html | 1 |
| tpl_44 | Life At Abbvie — group 45 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/life-at-abbvie.html | 1 |
| tpl_45 | Pipeline — group 46 | Same structural layout across 2 page(s) in the crawl. | https://www.abbvie.com/science/pipeline.html, https://www.abbvie.com/science/pipeline.html?utm_medium=psearch&amp;utm_campaign=corprepppp_2023&amp;utm_source=google&amp;utm_content=igp&amp;utm_term=research-dev&amp;cid=ppc_CV388fdb1654d244169c71e7b4f7ff04c4&amp;gclid=CjwKCAiAmZGrBhAnEiwAo9qHiRTJmfLpf-WzbqgcZlNiwz2UdRnluEZxPLyuGDeX0dpeP5qTxHPTMRoCdLAQAvD_BwE&amp;gclsrc=aw.ds | 2 |
| tpl_46 | Transparency In Payment — group 47 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/operating-with-integrity/transparency-in-payment.html | 1 |
| tpl_47 | Benefits — group 48 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/life-at-abbvie/benefits.html | 1 |
| tpl_48 | Aesthetics — group 49 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/areas-of-focus/aesthetics.html | 1 |
| tpl_49 | Products — group 50 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/patients/products.html | 1 |
| tpl_50 | Equity Equality Inclusion Diversity — group 51 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-principles/equity-equality-inclusion-diversity.html | 1 |
| tpl_51 | Grants And Contribution Disclosures — group 52 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/independent-educational-grants/grants-and-contribution-disclosures.html | 1 |
| tpl_52 | Ai And Data Convergence — group 53 | Same structural layout across 2 page(s) in the crawl. | https://www.abbvie.com/science/areas-of-innovation/ai-and-data-convergence.html, https://www.abbvie.com/science/areas-of-innovation/data-convergence.html | 2 |
| tpl_53 | How To Apply — group 54 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/independent-educational-grants/how-to-apply.html | 1 |
| tpl_54 | Brand Partnerships — group 55 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/brand-partnerships.html | 1 |
| tpl_55 | Areas Of Focus — group 56 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/areas-of-focus.html | 1 |
| tpl_56 | Genomics — group 57 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/areas-of-innovation/genomics.html | 1 |
| tpl_57 | Requestor Training Guide — group 58 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/independent-educational-grants/requestor-training-guide.html | 1 |
| tpl_58 | Allergan Aesthetics — group 59 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/opportunities/allergan-aesthetics.html | 1 |
| tpl_59 | Living With An Illness — group 60 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/living-with-an-illness.html | 1 |
| tpl_60 | Page layout group 61 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/abbvies-2024-working-parents-finding-purpose-in-adversity.html | 1 |
| tpl_61 | Investigator Initiated Studies — group 62 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/clinical-trials/investigator-initiated-studies.html | 1 |
| tpl_62 | Learning And Development — group 63 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/life-at-abbvie/learning-and-development.html | 1 |
| tpl_63 | Request Types — group 64 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/independent-educational-grants/request-types.html | 1 |
| tpl_64 | Therapeutic Modalities And Platforms — group 65 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/areas-of-innovation/therapeutic-modalities-and-platforms.html | 1 |
| tpl_65 | Contact Center — group 66 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/contact-center.html | 1 |
| tpl_66 | Abbvie Inquiry — group 67 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/operating-with-integrity/transparency-in-payment/abbvie-inquiry.html | 1 |
| tpl_67 | Jag Dosanjh — group 68 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/jag-dosanjh.html | 1 |
| tpl_68 | Join Us — group 69 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us.html | 1 |
| tpl_69 | Student And New Graduates — group 70 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/student-and-new-graduates.html | 1 |
| tpl_70 | Sustainability — group 71 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/sustainability.html | 1 |
| tpl_71 | Environmental Social And Governance — group 72 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/sustainability/environmental-social-and-governance.html | 1 |
| tpl_72 | Terms Of Use — group 73 | Same structural layout across 2 page(s) in the crawl. | https://www.abbvie.com/terms-of-use.html, https://www.abbvie.com/termsofuse.html | 2 |
| tpl_73 | United States — group 74 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/contact-center/locations/united-states.html | 1 |
| tpl_74 | Latif Akintade — group 75 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/latif-akintade.html | 1 |
| tpl_75 | Robert Michael — group 76 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/robert-michael.html | 1 |
| tpl_76 | Why Abbvie — group 77 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/why-abbvie.html | 1 |
| tpl_77 | Liz Shea — group 78 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/liz-shea.html | 1 |
| tpl_78 | New Graduates And Entry Level Positions — group 79 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/student-and-new-graduates/new-graduates-and-entry-level-positions.html | 1 |
| tpl_79 | Nicholas Donoghoe — group 80 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/nicholas-donoghoe.html | 1 |
| tpl_80 | Page layout group 81 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-principles/positions-views/our-commitment-to-ethical-and-responsible-use-of-animals-in-research.html | 1 |
| tpl_81 | Algeria — group 82 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/contact-center/locations/algeria.html | 1 |
| tpl_82 | Supplier Resources — group 83 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/operating-with-integrity/responsible-supply-chain/supplier-resources.html | 1 |
| tpl_83 | Internships — group 84 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/internships.html | 1 |
| tpl_84 | Croatia — group 85 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/contact-center/locations/croatia.html | 1 |
| tpl_85 | Jeffrey Stewart — group 86 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/jeffrey-stewart.html | 1 |
| tpl_86 | Page layout group 87 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/breaking-the-rules-of-science-to-treat-cancer.html | 1 |
| tpl_87 | Lebanon — group 88 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/contact-center/locations/lebanon.html | 1 |
| tpl_88 | Lithuania — group 89 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/contact-center/locations/lithuania.html | 1 |
| tpl_89 | Nicole Mowad Nassar — group 90 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/nicole-mowad-nassar.html | 1 |
| tpl_90 | Disaster Relief — group 91 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/sustainability/disaster-relief.html | 1 |
| tpl_91 | Estonia — group 92 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/contact-center/locations/estonia.html | 1 |
| tpl_92 | Student Programs — group 93 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/student-programs.html | 1 |
| tpl_93 | Page layout group 94 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/an-innovative-approach-to-improve-maternal-health.html | 1 |
| tpl_94 | Bosnia And Herzegovina — group 95 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/contact-center/locations/bosnia-and-herzegovina.html | 1 |
| tpl_95 | Allergan Ous Disclosures — group 96 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/operating-with-integrity/transparency-in-payment/allergan-ous-disclosures.html | 1 |
| tpl_96 | Serbia — group 97 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/contact-center/locations/serbia.html | 1 |
| tpl_97 | Roopal Thakkar — group 98 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/roopal-thakkar.html | 1 |
| tpl_98 | Page layout group 99 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/operating-with-integrity/transparency-in-payment/frequently-asked-questions-physician-and-other-payments.html | 1 |
| tpl_99 | Well Being In The Workplace — group 100 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/life-at-abbvie/well-being-in-the-workplace.html | 1 |
| tpl_100 | Timothy Richmond — group 101 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/timothy-richmond.html | 1 |
| tpl_101 | Resources — group 102 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/sustainability/environmental-social-and-governance/resources.html | 1 |
| tpl_102 | Alberto Colzi — group 103 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/alberto-colzi.html | 1 |
| tpl_103 | Accessibility Statement — group 104 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/accessibility-statement.html | 1 |
| tpl_104 | Saudi Arabia — group 105 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/contact-center/locations/saudi-arabia.html | 1 |
| tpl_105 | Perry Siatis — group 106 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/perry-siatis.html | 1 |
| tpl_106 | Impact Through Inclusion — group 107 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-principles/equity-equality-inclusion-diversity/impact-through-inclusion.html | 1 |
| tpl_107 | Slovenia — group 108 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/contact-center/locations/slovenia.html | 1 |
| tpl_108 | Tunisia — group 109 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/contact-center/locations/tunisia.html | 1 |
| tpl_109 | Romania — group 110 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/contact-center/locations/romania.html | 1 |
| tpl_110 | Azita Saleki Gerhardt — group 111 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/azita-saleki-gerhardt.html | 1 |
| tpl_111 | South Africa And Sub Saharan Africa — group 112 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/contact-center/locations/south-africa-and-sub-saharan-africa.html | 1 |
| tpl_112 | Latvia — group 113 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/contact-center/locations/latvia.html | 1 |
| tpl_113 | Scott Reents — group 114 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/scott-reents.html | 1 |
| tpl_114 | Abbvie Foundation — group 115 | Same structural layout across 5 page(s) in the crawl. | https://www.abbvie.com/sustainability/abbvie-foundation.html, https://www.abbvie.com/sustainability/philanthropy.html, https://www.abbvie.com/sustainability/philanthropy/philanthropic-programs.html | 5 |
| tpl_115 | United Arab Emirates — group 116 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/contact-center/locations/united-arab-emirates.html | 1 |
| tpl_116 | Addressing Systemic Barriers — group 117 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/sustainability/abbvie-foundation/addressing-systemic-barriers.html | 1 |
| tpl_117 | Postdoctoral Program — group 118 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/postdoctoral-program.html | 1 |
| tpl_118 | Page layout group 119 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/not-good-enough-behind-the-drive-to-give-cancer-patients-more-time.html | 1 |
| tpl_119 | Innovative Impact — group 120 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/sustainability/abbvie-foundation/innovative-impact.html | 1 |
| tpl_120 | Employee Resource Groups — group 121 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/life-at-abbvie/employee-resource-groups.html | 1 |
| tpl_121 | Site Map — group 122 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/site-map.html | 1 |
| tpl_122 | Wulff Erik Von Borcke — group 123 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/wulff-erik-von-borcke.html | 1 |
| tpl_123 | Page layout group 124 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/discovery-files-vision-for-blood-cancer-patients.html | 1 |
| tpl_124 | Tracie Haas — group 125 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/tracie-haas.html | 1 |
| tpl_125 | Page layout group 126 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/day-in-life-meet-engineer-promoting-diversity-within-manufacturing.html | 1 |
| tpl_126 | Page layout group 127 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/why-delivering-science-based-targets-are-key-to-sustainable-grow.html | 1 |
| tpl_127 | Demetris Crum — group 128 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/demetris-crum.html | 1 |
| tpl_128 | Abbvie Volunteers Return To Serving — group 129 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/abbvie-volunteers-return-to-serving.html | 1 |
| tpl_129 | Btk Protein Good Bad And Ugly — group 130 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/btk-protein-good-bad-and-ugly.html | 1 |
| tpl_130 | Jerome Bouyer — group 131 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/jerome-bouyer.html | 1 |
| tpl_131 | Linda Ray — group 132 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/linda-ray.html | 1 |
| tpl_132 | Everyones Talking About Data Science — group 133 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/everyones-talking-about-data-science.html | 1 |
| tpl_133 | The Power Love In Ibd — group 134 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/the-power-love-in-ibd.html | 1 |
| tpl_134 | Page layout group 135 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/striving-for-patient-centricity-down-to-the-packaging.html | 1 |
| tpl_135 | Magnified Featuring Linda Scarazzini — group 136 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/magnified-featuring-linda-scarazzini.html | 1 |
| tpl_136 | How Patient Voices Are Changing Medicine — group 137 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/how-patient-voices-are-changing-medicine.html | 1 |
| tpl_137 | Inside Dream Initiative — group 138 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/inside-dream-initiative.html | 1 |
| tpl_138 | Dave Purdue — group 139 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/dave-purdue.html | 1 |
| tpl_139 | Page layout group 140 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/hepatitis-c-mysterious-virus-that-met-its-match.html | 1 |
| tpl_140 | Page layout group 141 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/day-in-life-meet-director-clearing-path-for-patient-access.html | 1 |
| tpl_141 | Page layout group 142 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/starting-with-a-spark-an-inside-look-at-environmental-sustainability.html | 1 |
| tpl_142 | Page layout group 143 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/the-hardest-hit-how-nonprofits-rise-to-challenge-covid-19.html | 1 |
| tpl_143 | Can Unlocking One Million Genomes — group 144 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/can-unlocking-one-million-genomes.html | 1 |
| tpl_144 | They Wont Back Down — group 145 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/they-wont-back-down.html | 1 |
| tpl_145 | Page layout group 146 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/green-chemistry-cleaner-faster-chemical-reactions.html | 1 |
| tpl_146 | Page layout group 147 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/lessons-from-a-lifelong-journey-with-psoriasis.html | 1 |
| tpl_147 | Page layout group 148 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/precision-medicine-its-not-just-for-oncology-anymore.html | 1 |
| tpl_148 | Page layout group 149 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/the-story-behind-our-50-billion-rd-investment.html | 1 |
| tpl_149 | Page layout group 150 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/make-complicated-simple-inside-world-human-factors-engineers.html | 1 |
| tpl_150 | Living With Unknowns Alzheimers Disease — group 151 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/living-with-unknowns-alzheimers-disease.html | 1 |
| tpl_151 | Page layout group 152 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/how-uterine-fibroids-feel-to-patient-who-is-also-doctor.html | 1 |
| tpl_152 | Magnified Featuring Matt Widman — group 153 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/magnified-featuring-matt-widman.html | 1 |
| tpl_153 | Jason Smith — group 154 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/jason-smith.html | 1 |
| tpl_154 | Page layout group 155 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/unlocking-the-next-level-of-protein-degradation.html | 1 |
| tpl_155 | Magnified Featuring Jonathon Sedgwick — group 156 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/magnified-featuring-jonathon-sedgwick.html | 1 |
| tpl_156 | Page layout group 157 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/abbvie-rebuilds-north-chicagos-middle-school-inspiring-students-to-reach-higher.html | 1 |
| tpl_157 | Page layout group 158 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/finding-hope-in-a-pandemic--a-conversation-with-two-hepatitis-c-.html | 1 |
| tpl_158 | Page layout group 159 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/then-and-now-renaissance-in-blood-cancer-treatment.html | 1 |
| tpl_159 | Trapped In Your Own Skin — group 160 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/trapped-in-your-own-skin.html | 1 |
| tpl_160 | Why Isnt Medicine One Size Fits All — group 161 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/why-isnt-medicine-one-size-fits-all.html | 1 |
| tpl_161 | Page layout group 162 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/real-world-data-rounds-out-value-picture-drugs.html | 1 |
| tpl_162 | Page layout group 163 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/a-history-discovery-why-we-focus-on-eye-cares-toughest-diseases.html | 1 |
| tpl_163 | Page layout group 164 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/rebuilding-puerto-rico-one-community-health-center-at-a-time.html | 1 |
| tpl_164 | Magnified Featuring Shuhong Zhang — group 165 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/magnified-featuring-shuhong-zhang.html | 1 |
| tpl_165 | Page layout group 166 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/the-blueprint-of-you-unlocking-potential-whole-genome-sequencing.html | 1 |
| tpl_166 | The Math Of Migraine — group 167 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/the-math-of-migraine.html | 1 |
| tpl_167 | Magnified Featuring Darin Messina — group 168 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/magnified-featuring-darin-messina.html | 1 |
| tpl_168 | Magnified Featuring Sean Mcewen — group 169 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/magnified-featuring-sean-mcewen.html | 1 |
| tpl_169 | A Journey Of Sight Progress — group 170 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/a-journey-of-sight-progress.html | 1 |
| tpl_170 | What Does It Take To Discover A New Medicine — group 171 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/what-does-it-take-to-discover-a-new-medicine.html | 1 |
| tpl_171 | Shining Light On Glaucoma And Eye Health — group 172 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/shining-light-on-glaucoma-and-eye-health.html | 1 |
| tpl_172 | Page layout group 173 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/three-factors-that-drove-transformational-integration-abbvie-allergan.html | 1 |
| tpl_173 | Page layout group 174 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/how-medicinal-chemists-are-creating-new-weapons-against-autoimmune-diseases.html | 1 |
| tpl_174 | Navigating Ulcerative Colitis As A Child — group 175 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/navigating-ulcerative-colitis-as-a-child.html | 1 |
| tpl_175 | Page layout group 176 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/advancing-a-public-health-approach-to-patient-safety.html | 1 |
| tpl_176 | Page layout group 177 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/connecting-patients-with-care-3-lessons-learned-during-covid-19.html | 1 |
| tpl_177 | Page layout group 178 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/more-than-skin-deep-3-lessons-for-expanding-equity-in-dermatology.html | 1 |
| tpl_178 | Page layout group 179 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/making-it-migraine-friendly-why-were-reimagining-workplace.html | 1 |
| tpl_179 | Page layout group 180 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/chembeads-improving-artificial-intelligence-through-human-ingenuity.html | 1 |
| tpl_180 | Stronger Together Convergence Minds And Data — group 181 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/stronger-together-convergence-minds-and-data.html | 1 |
| tpl_181 | Page layout group 182 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/how-abbvie-is-bringing-antiviral-expertise-to-covid-19-battle.html | 1 |
| tpl_182 | Chasing The Value Of A Walk Down The Aisle — group 183 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/chasing-the-value-of-a-walk-down-the-aisle.html | 1 |
| tpl_183 | Page layout group 184 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/day-in-life-government-affairs-director-educates-and-empowers.html | 1 |
| tpl_184 | Page layout group 185 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/day-in-the-life-creating-impact-with-nonprofit-partners.html | 1 |
| tpl_185 | Page layout group 186 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/life-after-stroke-living-with-and-researching-spasticity.html | 1 |
| tpl_186 | Nisha Patel Burns — group 187 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-leaders/nisha-patel-burns.html | 1 |
| tpl_187 | Injecting Hope One Vaccine At A Time — group 188 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/injecting-hope-one-vaccine-at-a-time.html | 1 |
| tpl_188 | Profile Stories — group 189 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/profile-stories.html | 1 |
| tpl_189 | Magnified Featuring Edrice Simmons — group 190 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/magnified-featuring-edrice-simmons.html | 1 |
| tpl_190 | Company Stories — group 191 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/company-stories.html | 1 |
| tpl_191 | Eedi Stories — group 192 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/eedi-stories.html | 1 |
| tpl_192 | Sustainability Stories — group 193 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/sustainability-stories.html | 1 |
| tpl_193 | Abbvie Research Collaborative — group 194 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/abbvie-research-collaborative.html | 1 |
| tpl_194 | Page layout group 195 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/shedding-light-upon-a-misunderstood-skin-condition-hidradenitis.html | 1 |
| tpl_195 | A Legacy Of Leadership In Mental Health — group 196 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/a-legacy-of-leadership-in-mental-health.html | 1 |
| tpl_196 | Magnified Featuring Johanna Corbin — group 197 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/magnified-featuring-johanna-corbin.html | 1 |
| tpl_197 | Page layout group 198 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/5-ways-abbvie-work-to-deliver-medicines-in-half-the-time.html | 1 |
| tpl_198 | Voices Abbvie Reflecting On Decade Impact — group 199 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/voices-abbvie-reflecting-on-decade-impact.html | 1 |
| tpl_199 | Page layout group 200 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/resilient-reality-the-emotional-toll-of-ovarian-cancer.html | 1 |
| tpl_200 | Page layout group 201 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/going-inside-prison-walls-to-help-eliminate-hepatitis-c.html | 1 |
| tpl_201 | Science Stories — group 202 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/science-stories.html | 1 |
| tpl_202 | Why You Cant Wait With Rheumatoid Arthritis — group 203 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/why-you-cant-wait-with-rheumatoid-arthritis.html | 1 |
| tpl_203 | Page layout group 204 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/specialized-research-in-chaotic-systems-sparcs.html | 1 |
| tpl_204 | Page layout group 205 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/the-value-of-education-from-a-dim-reality-to-a-bright-future.html | 1 |
| tpl_205 | Page layout group 206 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/how-the-parkinsons-disease-community-is-shaping-the-future.html | 1 |
| tpl_206 | Page layout group 207 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/working-parents-2023-finding-comfort-in-community.html | 1 |
| tpl_207 | Page layout group 208 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/recognizing-the-mental-health-impact-of-chronic-skin-disease.html | 1 |
| tpl_208 | Digital Science Lab — group 209 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/digital-science-lab.html | 1 |
| tpl_209 | Immunologys Next Frontier — group 210 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/immunologys-next-frontier.html | 1 |
| tpl_210 | Magnified Featuring Nicholas Donoghoe — group 211 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/magnified-featuring-nicholas-donoghoe.html | 1 |
| tpl_211 | Eye Care Stories — group 212 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/eye-care-stories.html | 1 |
| tpl_212 | Time Is Hours — group 213 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/time-is-hours.html | 1 |
| tpl_213 | Page layout group 214 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/decoding-immune-systems-secrets-inside-the-discovery-of-a-new-medicine.html | 1 |
| tpl_214 | Neuroscience Stories — group 215 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/neuroscience-stories.html | 1 |
| tpl_215 | Page layout group 216 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/one-veterans-journey-and-abbvies-commitment-to-mental-health-research.html | 1 |
| tpl_216 | Immunology Stories — group 217 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/immunology-stories.html | 1 |
| tpl_217 | Page layout group 218 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/how-abbvies-integrated-operations-help-prevent-drug-shortages.html | 1 |
| tpl_218 | Page layout group 219 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/five-reasons-why-small-cell-lung-cancer-is-tough-to-treat.html | 1 |
| tpl_219 | Page layout group 220 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/childhood-cancer-patients-and-their-families-find-a-home-away-from-home.html | 1 |
| tpl_220 | Page layout group 221 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/expert-insights-the-promise-of-genetic-medicine-and-abbvies-role-in-research.html | 1 |
| tpl_221 | Page layout group 222 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/putting-our-people-first-abbvies-family-benefits.html | 1 |
| tpl_222 | Page layout group 223 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/real-world-evidence-uncovers-gaps-in-IBD-care.html | 1 |
| tpl_223 | Oncology Stories — group 224 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/oncology-stories.html | 1 |
| tpl_224 | Page layout group 225 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/ready-set-launch-abbvie-opens-new-facility-in-the-bay-area.html | 1 |
| tpl_225 | Page layout group 226 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/more-than-a-stiff-neck-the-impact-of-living-with-cervical-dyston.html | 1 |
| tpl_226 | Transforming Cancer Care From The Inside Out — group 227 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/transforming-cancer-care-from-the-inside-out.html | 1 |
| tpl_227 | Aesthetics Stories — group 228 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/aesthetics-stories.html | 1 |
| tpl_228 | Can We Find Cures Faster — group 229 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/can-we-find-cures-faster.html | 1 |
| tpl_229 | Navigating The Hidden Side Of Cancer — group 230 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/navigating-the-hidden-side-of-cancer.html | 1 |
| tpl_230 | Ambassadors In Action — group 231 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/ambassadors-in-action.html | 1 |
| tpl_231 | Working At Abbvie Stories — group 232 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/working-at-abbvie-stories.html | 1 |
| tpl_232 | Page layout group 233 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/three-ways-ai-is-changing-drug-discovery-at-abbvie.html | 1 |
| tpl_233 | Page layout group 234 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/new-microsite-clinic-brings-healthcare-to-chicago-southwest-side.html | 1 |
| tpl_234 | Elevating Health Care For All — group 235 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/elevating-health-care-for-all.html | 1 |
| tpl_235 | Page layout group 236 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/advice-from-scientist-turned-physician-turned-robot-builder-be-curious.html | 1 |
| tpl_236 | Page layout group 237 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/much-more-than-itchy-skin-breaking-down-complexities-atopic-dermatitis.html | 1 |
| tpl_237 | Page layout group 238 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/meet-the-arch-a-time-saving-tool-for-researchers-focused-on-finding-cures.html | 1 |
| tpl_238 | Page layout group 239 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/ensuring-patients-around-world-get-medicines-during-covid-19.html | 1 |
| tpl_239 | Real People Real Inspiration Joes Story — group 240 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/real-people-real-inspiration-joes-story.html | 1 |
| tpl_240 | Page layout group 241 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/a-molecular-behavior-chart-speeding-up-research-with-predictive-analytics.html | 1 |
| tpl_241 | Philanthropy Stories — group 242 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/philanthropy-stories.html | 1 |
| tpl_242 | Serving Communities Stories — group 243 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/serving-communities-stories.html | 1 |
| tpl_243 | Virology Stories — group 244 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/virology-stories.html | 1 |
| tpl_244 | Synthetic Control Arm End Placebos — group 245 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/synthetic-control-arm-end-placebos.html | 1 |
| tpl_245 | Little Patients Big Impact — group 246 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/little-patients-big-impact.html | 1 |
| tpl_246 | Page layout group 247 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/celebrating-abbvies-2025-working-parents-caregivers.html | 1 |
| tpl_247 | Patient Support Stories — group 248 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/patient-support-stories.html | 1 |
| tpl_248 | Page layout group 249 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/growing-sustainably-through-innovation-how-abbvie-takes-action.html | 1 |
| tpl_249 | Change From Within — group 250 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/change-from-within.html | 1 |
| tpl_250 | Partnerships Stories — group 251 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/partnerships-stories.html | 1 |
| tpl_251 | Page layout group 252 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/sharpening-focus-on-eye-diseases-caused-by-diabetes.html | 1 |
| tpl_252 | Bay Area Opportunities — group 253 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/bay-area-opportunities.html | 1 |
| tpl_253 | Social Media Community Guidelines — group 254 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/social-media-community-guidelines.html | 1 |
| tpl_254 | Cerevel — group 255 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/cerevel.html | 1 |
| tpl_255 | Mitokinin — group 256 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/mitokinin.html | 1 |
| tpl_256 | Celsius Therapeutics — group 257 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/celsius-therapeutics.html | 1 |
| tpl_257 | Immunogen — group 258 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/immunogen.html | 1 |
| tpl_258 | Discovery Files — group 259 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people/discovery-files.html | 1 |
| tpl_259 | Allergan — group 260 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/allergan.html | 1 |
| tpl_260 | Behind The Science — group 261 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people/behind-the-science.html | 1 |
| tpl_261 | Linda Scarazzini — group 262 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people/our-rd-leaders/linda-scarazzini.html | 1 |
| tpl_262 | Equal Employment Opportunity Employer — group 263 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/equal-employment-opportunity-employer.html | 1 |
| tpl_263 | Capstan Therapeutics — group 264 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/capstan-therapeutics.html | 1 |
| tpl_264 | Savings Card — group 265 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/patients/patient-support/patient-assistance/savings-card.html | 1 |
| tpl_265 | Available Programs — group 266 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/patients/patient-support/patient-assistance/available-programs.html | 1 |
| tpl_266 | Eligibility Criteria — group 267 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/patients/patient-support/patient-assistance/eligibility-criteria.html | 1 |
| tpl_267 | Science In 60 Seconds — group 268 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people/science-in-60-seconds.html | 1 |
| tpl_268 | Aliada Therapeutics — group 269 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/aliada-therapeutics.html | 1 |
| tpl_269 | Contactus — group 270 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/contactus.html | 1 |
| tpl_270 | Online Application Overview — group 271 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/patients/patient-support/patient-assistance/online-application-overview.html | 1 |
| tpl_271 | Locations — group 272 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/contact-center/locations.html | 1 |
| tpl_272 | Daejin Abidoye — group 273 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people/our-rd-leaders/daejin-abidoye.html | 1 |
| tpl_273 | Wolfram Nothaft — group 274 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people/our-rd-leaders/wolfram-nothaft.html | 1 |
| tpl_274 | Eleni Lagkadinou — group 275 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people/our-rd-leaders/eleni-lagkadinou.html | 1 |
| tpl_275 | Raymond Votzmeyer — group 276 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people/our-rd-leaders/raymond-votzmeyer.html | 1 |
| tpl_276 | Abbvie Pride — group 277 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/life-at-abbvie/employee-resource-groups/abbvie-pride.html | 1 |
| tpl_277 | Income Criteria — group 278 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/patients/patient-support/patient-assistance/income-criteria.html | 1 |
| tpl_278 | Philip Hajduk — group 279 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people/our-rd-leaders/philip-hajduk.html | 1 |
| tpl_279 | Access To Investigational Drugs Policy — group 280 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/access-to-investigational-drugs-policy.html | 1 |
| tpl_280 | Michael Foley — group 281 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people/our-rd-leaders/michael-foley.html | 1 |
| tpl_281 | Page layout group 282 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/two-lives-converging-in-the-fight-against-parkinsons.html | 1 |
| tpl_282 | Asian Leadership Network — group 283 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/life-at-abbvie/employee-resource-groups/asian-leadership-network.html | 1 |
| tpl_283 | Veterans — group 284 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/life-at-abbvie/employee-resource-groups/veterans.html | 1 |
| tpl_284 | Human Capital Management — group 285 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/sustainability/environmental-social-and-governance/human-capital-management.html | 1 |
| tpl_285 | Declaracion De Accessibilidad — group 286 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/accessibility-statement/declaracion-de-accessibilidad.html | 1 |
| tpl_286 | Page layout group 287 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/empowering-innovation-through-the-abbvie-foundation-health-equit.html | 1 |
| tpl_287 | Patents — group 288 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/patents.html | 1 |
| tpl_288 | Page layout group 289 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/patients/patient-support/patient-assistance/patient-assistance-frequently-asked-questions.html | 1 |
| tpl_289 | Primal Kaur — group 290 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people/our-rd-leaders/primal-kaur.html | 1 |
| tpl_290 | Reasonable Accommodations — group 291 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/reasonable-accommodations.html | 1 |
| tpl_291 | Page layout group 292 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/how-employee-resource-groups-create-meaningful-impact-at-abbvie.html | 1 |
| tpl_292 | Ahora Hispanic Latino — group 293 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/life-at-abbvie/employee-resource-groups/ahora-hispanic-latino.html | 1 |
| tpl_293 | Abbvie Ventures Portfolio — group 294 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/partner-with-us/abbvie-ventures/abbvie-ventures-portfolio.html | 1 |
| tpl_294 | Environmental Sustainability — group 295 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/sustainability/environmental-social-and-governance/environmental-sustainability.html | 1 |
| tpl_295 | Lab To Life — group 296 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people/lab-to-life.html | 1 |
| tpl_296 | Jonathon Sedgwick — group 297 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people/our-rd-leaders/jonathon-sedgwick.html | 1 |
| tpl_297 | Andrew Campbell — group 298 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people/our-rd-leaders/andrew-campbell.html | 1 |
| tpl_298 | Page layout group 299 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/who-we-are/our-stories/five-technologies-supporting-progress-in-challenging-diseases.html | 1 |
| tpl_299 | Lab Of The Future — group 300 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people/lab-of-the-future.html | 1 |
| tpl_300 | Darin Messina — group 301 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people/our-rd-leaders/darin-messina.html | 1 |
| tpl_301 | Ability At Abbvie — group 302 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/life-at-abbvie/employee-resource-groups/ability-at-abbvie.html | 1 |
| tpl_302 | Shuhong Zhang — group 303 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/science/our-people/our-rd-leaders/shuhong-zhang.html | 1 |
| tpl_303 | Black Business Network — group 304 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/life-at-abbvie/employee-resource-groups/black-business-network.html | 1 |
| tpl_304 | Women Leaders In Action — group 305 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/join-us/life-at-abbvie/employee-resource-groups/women-leaders-in-action.html | 1 |
| tpl_305 | Allergan Labeling — group 306 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/allergan-labeling.html | 1 |
| tpl_306 | Page layout group 307 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/patients/patient-support/patient-assistance/online-application-frequently-asked-questions.html | 1 |
| tpl_307 | Abbvie Research Collaborative Endometrosis — group 308 | Same structural layout across 2 page(s) in the crawl. | https://www.abbvie.com/science/abbvie-research-collaborative-endometrosis.html, https://www.abbvie.com/science/abbvie-research-collaborative-migraine.html | 2 |
| tpl_308 | Nimbletherapeutics — group 309 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/nimbletherapeutics.html | 1 |
| tpl_309 | Privacy — group 310 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/privacy.html | 1 |
| tpl_310 | Partnerships Chicago Cubs — group 311 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/partnerships-chicago-cubs.html | 1 |
| tpl_311 | Latest Earnings — group 312 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/latest-earnings.html | 1 |
| tpl_312 | Privacy Inquiry — group 313 | Same structural layout across 1 page(s) in the crawl. | https://www.abbvie.com/privacy-inquiry.html | 1 |
