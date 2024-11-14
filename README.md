# National Access Point Reference Architecture

The National Access Point Reference Architecture (NRA) is a set of high level views that enable plans to be made for interoperable NAP. It covers technical aspects, plus the related organisational, legal and business issues. It defines a framework and guideline for the implementation of harmonized national access points across Europe. 

NAP reference Archictecture is an initiative of the [NAPCORE (National Access Point Coordination Organisation for Europe)](https://napcore.eu/), a formed organisation to coordinate and harmonise more than 30 mobility data platforms across Europe. It is based on methodology created by the FRAME (FRamework Architecture Made for Europe) available at [GitHub](https://github.com/FRAME-NEXT/FRAME) with dedicated websites of [FRAME home](https://frame-online.eu/) and of [FRAME-NEXT project](https://frame-next.eu/).

## Structure of the repository 

- Releases: NAP Reference Architecture releases (1.0.0, etc.); each release having updated high level views and recommendations according to latest understanding.
- Working Drafts: Working drafts including revisions to the latest NAP Reference Architecture release.
- Website: Latest NRA, FRAME repository and FRAME metamodel as a browseable version [website](https://napcore.github.io/NAP-Reference-Architecture/)

## Working with NAP Reference Arcirecture models 

The NAP Reference Arcirecture models are stored as XMI file and as a FRAME toolbox. 

To open the NRA first the toolbox must be loaded into empty EA project and then XMI with the NRA imported to that file. Any other sequence will break the stereotypes.

## Working with website

The website content is stored in /docs folder.

### Local Installation

Using Python 3.12 and pdm:

$ pdm install

Before using the installed mkdocs command, make sure you activate it's virtualenv.

### Local development

Edit files in the docs folder. See https://www.mkdocs.org/user-guide/writing-your-docs/

Run from project root:

$ mkdocs serve

Then open http://localhost:8000

This shall update as soon as you save any content file.

### Deploying on GitHub Pages

Just push the repository to GitHub. It shall build the page on it's own.
See: https://napcore.github.io/NAP-Reference-Architecture/

## Acknowledgement
This Architecture respresents the architecture of National Access Point harmonized by [NAPCORE](https://napcore.eu/)

![NAPCORE](https://napcore.eu/wp-content/themes/napcore/images/napcore-logo.png)

![Co founded by EU](https://napcore.eu/wp-content/themes/napcore/images/eu.png)
