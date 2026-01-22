# National Access Point Reference Architecture (NRA)

![Version](https://img.shields.io/github/v/tag/NAPCORE/NAP-Reference-Architecture?label=version&style=flat-square)
![License](https://img.shields.io/github/license/NAPCORE/NAP-Reference-Architecture?style=flat-square)
![Last Commit](https://img.shields.io/github/last-commit/NAPCORE/NAP-Reference-Architecture?style=flat-square)
![Open Issues](https://img.shields.io/github/issues/NAPCORE/NAP-Reference-Architecture?style=flat-square)
![Closed Issues](https://img.shields.io/github/issues-closed/NAPCORE/NAP-Reference-Architecture?style=flat-square)

The **National Access Point Reference Architecture (NRA)** provides a harmonised, high‑level architectural framework for implementing interoperable National Access Points (NAPs) across Europe.  
It covers technical, organisational, legal, and business aspects required for a coherent mobility data ecosystem.

The NRA is developed within **NAPCORE**, the National Access Point Coordination Organisation for Europe, which coordinates and harmonises more than 30 mobility data platforms across Europe.

The architecture is based on the **FRAME (FRamework Architecture Made for Europe)** methodology, available at the [FRAME GitHub repository](https://github.com/FRAME-NEXT/FRAME) and documented on [FRAME Online](https://frame-online.eu/) and [FRAME-NEXT](https://frame-next.eu/).


## 📁 Repository Structure

### `/releases`
Contains **official, stable, versioned** NRA releases (e.g., `1.0.0`, `1.1.0`).  
Each release includes:
- Enterprise Architect model files (`.qea`, `.xmi`)
- Word-exported documentation
- Methodology and supporting materials

### `/drafts`
Contains **working drafts** preparing future releases.  
Drafts follow the naming pattern:

'''
<target-version>-draft.<iteration>
'''

Example:

'''
1.1.0-draft.2
'''

The folder:

'''
/drafts/latest
'''

always contains the **most up‑to‑date working draft**, including corrections and improvements that will appear in the next release.

## 🧩 Working With NRA Models

The NRA models are provided as:
- **XMI files** (model exchange)
- **QEA files** (Enterprise Architect project)
- **FRAME toolbox** (required for stereotypes and modelling conventions)

To open the NRA in Enterprise Architect:

1. Create a **new, empty EA project**.  
2. **Load the FRAME toolbox**.  
3. Import the NRA `.xmi` file.  

> Importing the XMI before loading the toolbox will break stereotypes.


## 🎯 Purpose and Scope

The NRA provides:
- A **common reference** for NAP implementations across Europe  
- A **harmonised architectural baseline**  
- A **shared vocabulary** based on FRAME  
- Guidance across:
  - Technical architecture  
  - Organisational roles  
  - Legal and governance aspects  
  - Business processes and data flows  

It is intended for policymakers, NAP operators, architects, and technical teams.

## 🤝 Acknowledgement

This architecture is developed and maintained by **NAPCORE**.

![NAPCORE Logo](https://napcore.eu/wp-content/themes/napcore/images/napcore-logo.png)
![EU Flag](https://napcore.eu/wp-content/themes/napcore/images/eu.png)