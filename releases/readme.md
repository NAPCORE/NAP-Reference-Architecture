# NAP Reference Architecture – Official Releases

This directory contains the **official, versioned releases** of the National Access Point Reference Architecture (NRA).  
Each release is published as a standalone, immutable package and reflects the consolidated understanding agreed within NAPCORE at the time of publication.

## 📦 Contents of Each Release

A typical release folder (e.g., `1.0.0/`) includes:

- **Architecture Model Files**
  - `*.qea` — Enterprise Architect project file containing the NRA model
  - `*.xmi` — Model exchange file for importing into other EA projects or tools

- **Documentation**
  - `*.docx` — Word export of the NRA documentation (high‑level views, descriptions, recommendations)
  - Additional supporting documents where relevant

- **Methodology Material**
  - FRAME‑based methodology documents used to structure the NRA
  - Supporting descriptions of modelling conventions and stereotypes

## 🧭 Purpose of This Directory

The releases serve as:
- A **stable reference** for Member States and stakeholders
- A **baseline for implementation** of harmonised National Access Points
- A **citation‑ready source** for policy, technical, and organisational work

Releases are **not modified** after publication.  
All ongoing work happens in the `/drafts` directory.

## 🛠 Working With the Architecture Files

To open a release in Enterprise Architect (EA):

1. Create a **new, empty EA project**.
2. **Load the FRAME toolbox** into the project.
3. Import the NRA model using the provided `.xmi` file  
   *(Importing the XMI before loading the toolbox will break stereotypes.)*

The `.qea` file can also be opened directly if you prefer a ready‑to‑use EA project.

## 🔄 Where to Find Work in Progress

Drafts and upcoming changes are maintained in: `/drafts`

These drafts will eventually be consolidated into the next numbered release.