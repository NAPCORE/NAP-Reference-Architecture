# Contributing to the NAP Reference Architecture

Thank you for your interest in contributing to the National Access Point Reference Architecture (NRA).  
This document explains how contributions are organised, reviewed, and integrated into the project.

## 🧭 Contribution Workflow

All contributions follow the lifecycle:

release → feedback → draft iterations → next release

### 1. Identify the target version

Contributions should be made against the **next planned release**, not the last published one.

Drafts are stored in:

```
/drafts/<target-version>-draft.<iteration>
```

The folder:

```
/drafts/latest
```

always points to the most current working draft.

### 2. Propose a change

You may propose changes by:

- Opening an **issue**  
- Submitting a **pull request**  
- Providing feedback through NAPCORE working channels  

Please reference:
- The affected release or draft  
- The specific model elements or documentation sections  
- The rationale for the change  

### 3. Draft integration

Approved changes are incorporated into the **next draft iteration**:


```
<target-version>-draft.<iteration+1>
```

Drafts may undergo multiple iterations before stabilisation.

### 4. Release publication

Once a draft is validated and approved by NAPCORE governance, it becomes a new numbered release in:

```
/releases/<version>
```

Releases are **immutable**.

## 🛠 Working With the Models

To contribute to the Enterprise Architect models:

1. Start with a **new, empty EA project**.  
2. Load the **FRAME toolbox**.  
3. Import the relevant draft `.xmi` file.  

Never import the XMI before loading the toolbox.

## 📄 Documentation Contributions

Documentation is maintained as Word exports and supporting materials.  
When contributing:

- Keep structure consistent with FRAME methodology  
- Use clear, concise language  
- Ensure alignment between diagrams, models, and text  

## 🤝 Code of Conduct

Contributors are expected to follow NAPCORE’s collaborative principles:
- Respectful communication  
- Evidence‑based argumentation  
- Transparency of rationale  
- Alignment with European interoperability goals  

## 📬 Questions or Feedback?

Please open an issue in the repository or contact the NAPCORE working group responsible for the NRA.