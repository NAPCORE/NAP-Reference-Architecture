Here’s a significantly improved, clearer, more structured, and more professional README you can drop directly into the repository.  
# National Access Point Reference Architecture (NRA)

![Version](https://img.shields.io/github/v/tag/NAPCORE/NAP-Reference-Architecture?label=version&style=flat-square)
![License](https://img.shields.io/github/license/NAPCORE/NAP-Reference-Architecture?style=flat-square)
![Last Commit](https://img.shields.io/github/last-commit/NAPCORE/NAP-Reference-Architecture?style=flat-square)
![Open Issues](https://img.shields.io/github/issues/NAPCORE/NAP-Reference-Architecture?style=flat-square)
![Closed Issues](https://img.shields.io/github/issues-closed/NAPCORE/NAP-Reference-Architecture?style=flat-square)

The **National Access Point Reference Architecture (NRA)** provides a harmonised, high‑level architectural framework for implementing interoperable National Access Points (NAPs) across Europe.  
It covers not only technical architecture, but also the organisational, legal, and business considerations required for a coherent and sustainable mobility data ecosystem.

The NRA supports Member States in aligning their NAP implementations with the objectives of **NAPCORE**—the *National Access Point Coordination Organisation for Europe*—which coordinates and harmonises more than 30 mobility data platforms across Europe.

The architecture is based on the **FRAME (FRamework Architecture Made for Europe)** methodology, available at the [FRAME GitHub repository](https://github.com/FRAME-NEXT/FRAME) and documented on the [FRAME Online](https://frame-online.eu/) and [FRAME-NEXT](https://frame-next.eu/) websites.

## 📁 Repository Structure

### **Releases**
`/releases`  
Contains official NRA releases (e.g., *1.0.0*).  
Each release includes updated high‑level views, architectural components, and recommendations reflecting the latest shared understanding within NAPCORE.

### **Working Drafts**
`/drafts`  
Contains ongoing revisions and draft updates that will feed into future NRA releases.  
These drafts represent work in progress and may evolve before being included in an official release.

## 🧩 Working with the NRA Models

The NRA models are provided in two formats:

- **XMI file** – the model exchange format  
- **FRAME Toolbox** – the supporting FRAME methodology toolbox

To open and work with the NRA in *Enterprise Architect (EA)*:

1. Create a **new, empty EA project**.  
2. **Import the FRAME toolbox** into the project.  
3. **Import the NRA XMI file** into the same project.

> ⚠️ Importing the XMI before loading the toolbox will break stereotypes and model definitions.  
> Always load the toolbox first.

## 🎯 Purpose and Scope

The NRA provides:

- A **common reference** for Member States implementing or evolving their National Access Points  
- A **harmonised architectural baseline** supporting interoperability across Europe  
- A **shared vocabulary and modelling approach** based on FRAME  
- Guidance that spans:
  - Technical architecture  
  - Organisational roles and responsibilities  
  - Legal and governance considerations  
  - Business processes and data flows  

It is intended for policymakers, NAP operators, architects, and technical teams working on mobility data exchange.

## 🤝 Acknowledgement

This architecture is developed and maintained by **NAPCORE**, supporting the harmonisation of National Access Points across Europe.

`https://napcore.eu/wp-content/themes/napcore/images/napcore-logo.png`

`https://napcore.eu/wp-content/themes/napcore/images/eu.png`
