NRA/NLKF update procedures
==========================

***This document outlines procedures for taking in feedback to update NAP reference architecture (NRA).***

**Author:** *Me*

**History**

| Version | Who | note |
| --- | --- | --- |
| 0.1 | Petr Bureš | First draft based on NRA maintainers internal discussion |
| 0.2 | PB+BW | Revision of the document |
| 0.3 | WG2.3 | Internal revision of the document. |
| 20241009 | WG2.3 | Resolution at the meeting |

# Types of feedback

We recognize three types of feedback:

- **Review Feedback**: Based on the review of the documents/outputs produced by the NRA team.
- **Internal Feedback**: Based on an issue/topic identified by the NRA team and resolved with the identified interested party.
- **Demonstrator Feedback**: Based on expected input from NAPCORE demonstrators.

## Identification of Actors

- **NRA Maintainers**: BW, PB (HD).
- **NRA Team**: A larger group composed of WG2.3 participants.

# Review Feedback

This is regular feedback to comment on NRA products, documents, and architecture views. It can be submitted as an issue in GitHub (to be set up) or as a filled-in MS Word template.

Both review feedback forms are meant for documenting a proposed change by members of the NAPCORE community or external entities. Feedback should be received, recorded/initiated, analysed, addressed, replied and documented. If it leads to changes or updates, these fall at the responsibility of the NRA maintenance team.

## Feedback Input

### MS Word Template

Based on the feedback request or from its own initiative, a reviewing entity sends out a filled-in MS Word document to the NRA team (address to be set up).

The template is based on the ISO IEC template and consists of a table with the following columns:

- **MB/ID**: Member body or organization or individual that created the comment.

NRA specific:

- **View / Type / Object Name**: Three columns specifying what is being commented upon. Comments for the whole view have type and object name undefined.
  - **View**: Motivational layer, user needs, functional, physical, organizational, communication, and security view.
  - **Type**: Object type as it is specified in EA: data flow, function, application, etc.
  - **Object Name**: Name of the object as it appears in EA.

NLKF specific:

- **View: NLKF / Type = Category / Object Name = KPI number**: Three columns specifying what is being commented upon. Comments for the whole view have type and object name undefined.
  - **View**: set to NLKF for all or general.
  - **Type/Category**: Category of a KPI as defined in the framework (e.g., accessibility).
  - **Object Name/KPI number**: the number of KPI.

General:

- **Type of Comment**: General, editorial, technical.
- **Comments**: The comment with justification is placed here.
- **Proposed Change**: How the comment should be resolved. / Including a picture or a link to online document.
- **Observation**: How the comment was resolved by the NRA team.

### GitHub Issue

Based on the feedback request or from its own initiative, a reviewing entity files an issue on GitHub (<https://github.com/NAPCORE/NAP-Reference-Architecture/issues>) with the **same content** as in the MS Word template. This is a preferred way to describe an issue.

Template of the issue shall address (in reference to MS file issue):

- **Issue name:** composed of the problem description and scope identification
  - **\[View / Type / Object Name\]** – as inserted by the user
  - **Short description**
- **Label assigned by user: Type of Comment** (as inserted by user)
- **Contents of the issue:**
  - **Comments –** initial comments from the filing user
  - **Proposed Change** **–** initial proposal from the filing user.
- Content of the issue follow-up
  - **Observation**: a sequence of comments to the issue ending with a resolution.

## Feedback Processing

1. If the issue is received as file, NRA maintainers create a GitHub issue and attach the submitted file with comments to it.
2. NRA maintainers review the issue and
    1. assign labels
        1. **Scope**: bug, enhancement, question
        2. **Severity**: minor, major
        3. **Status**: needs review, in review, reviewed, done
        4. **Milestone**: version in which it will be implemented (date?)
    2. Assign resolution team
    3. assess the impact: whether the issue potential resolution triggers a substantial change on MS implement or operate their NAP. If a substantial change is foreseen, the resolution may need to involve a SCOM decision.

In case of **minor** feedback:

1. NRA maintainers propose and implement a feedback resolution.
2. NRA maintainers inform NRA team about the implemented resolution (or include it in a change log).

In case of **major** feedback:

1. NRA maintainers identify a (preliminary) resolution proposal.
2. NRA maintainers schedule a resolution meeting involving the NRA (+ NLKF) team and the commenting party.
3. Workshops/seminars introducing the issue for a very serious change.
4. During the resolution meeting, a decision is made on to address the review feedback.
5. The resolution is implemented either during the meeting or later based on the taken decision.

### Reaction times, issue resolution timeframe

The timeframe is subject to regular period of the NRA maintenance meetings.

For any issue

- Step 1 –2: **one month**, ideally during monthly NRA maintainers meeting

For a minor issue

- Step 3: **two months**
- Step 4: **one week**

For a major issue

- Step 3-4: **two months**
- Step 5: **one week**
- Step 6: **two weeks to two months** to implement resolution of major issue based on its complexity.

# Internal Feedback

A specific issue is identified within the NRA that needs approval and possible intervention/collaboration from another working group (the issue clearly relates to a specific WG and/or other involved entities). For example, a decision on the standards to be applied for interfaces or processes to be realized by NAP, etc.

The procedure is as follows:

1. The NRA team identifies an issue where approval from a specific WG is needed.
2. NRA maintainers propose a resolution of the identified problem AND the responsible WG.
3. The NRA team sets up a meeting with the responsible WG, where the issue is presented and confirmed/rejected.
4. Based on the decision of the responsible WG, the NRA maintainers process the change to the NRA.

The internal feedback serves to involve responsible WGs in the important NRA aspects. The actions are needed, for example, for:

- **\[WG4.4\] Metadata Standards**: Resolving what parts and how it shall be referenced within the NRA.
- **\[WG2.2\] Data Sets / Service Profiles**: Resolving which profiles are recommended for delegated acts.
- And others, not yet identified.

### Reaction times, issue resolution timeframe

The timeframe is subject to regular period of the NRA maintenance meetings.

For any issue

- Step 1 –2: **two months**, ideally during monthly NRA team meeting
- Step 3: **one month** (after completion of step 1 and 2)
- Step 4: **two weeks to two months** to implement resolution of an issue based on its complexity.

# Demonstrator Feedback

This type of feedback is reserved for demonstrators to bring **back any good practice/information** about what platform has been used, what approach has been taken, how it was organized, etc.

The feedback is organized into sections with specific information:

- **Licenses**: What license (for data/service usage and NAP usage (metadata)) types have been necessary to use in the demonstrator and if there is a lesson learned (e.g., what type is most useful or what licenses are needed for what part of the practice and how they were collected, etc.).
- **Interfaces**: What interfaces have been used with what software solution and what transport protocol, and if there is a lesson learned (e.g., what was found to be useful, most accepted, what software solutions are preferred, what security was deemed sufficient, what procedures, etc.).
- **Specification**: What data/service/metadata specification (standard or protocol specification, profile) has been used and with what outcome, and if there is a lesson learned (e.g., what specification for what data type, how was the implementation realized, shared code, tags used).
- **Functionality**: What functionality is needed at the NAP to make the demonstrator work and what functionality of the demonstrator is seen as beneficial to be adopted by NAPs.
- **Processes**: What processes realized by the demonstrator are relevant for the NAP and could be adopted in full or partially by the NAP. For example, registration of users, and how specifically (compare with current NRA)
- **Quality Parameters/Requirements**: Did the demonstrator yield any specific information about quality parameters of the NAP, or if there are any recommendations on the quality of the NRA service.
- **Additional Info**: Any other good practice that did not fit into previous categories but is beneficial for NAP.

The intention is to identify good practices, resolutions, software code that could be reused by other NAPs.

# Versioning

For new releases of the NRA the following scheme will be used:

- New versions will be released periodically (e.g. quarterly) fixing several issues, improvements and bugs at once, i.e. not every issue resolution will trigger new version release.
- The versioning scheme will follow semantic versioning ([Semantic Versioning)](https://semver.org/)
  - Given a version number MAJOR.MINOR.PATCH, increment the:
    - MAJOR version when you make incompatible API changes
    - MINOR version when you add functionality in a backward compatible manner
    - PATCH version when you make backward compatible bug fixes
  - Additional labels for pre-release and build metadata are available as extensions to the MAJOR.MINOR.PATCH format. (alpha \[a\], beta \[b\], release candidate \[rc\])
- For more information see: <https://semver.org/>

The versioning scheme applies to architectural views (i.e., motivational layer, user needs, functional view, physical view, organizational view, etc.) and to a file itself. Only views that changed will have the version increased. Version on the level of architectural objects is date of change of the object (e.g date modified)
