# National Access Point Reference Architecture

The National Access Point Reference Architecture (NRA) defines a framework and guideline for the implementation of harmonized national access points across Europe.

It is based on the FRAME (FRamework Architecture Made for Europe) available at [GitHub](https://github.com/FRAME-NEXT/FRAME) and dedicated websites of [FRAME home](https://frame-online.eu/) and of [FRAME-NEXT project](https://frame-next.eu/).

This repository hosts:

- latest model of the the NRA in the Enterprise Architect SW
- description of update procedures
- a [website](https://napcore.github.io/NAP-Reference-Architecture/) with latest NRA, FRAME repository and FRAME metamodel as a browseable version . 

## NRA model 

The NRA model is stored as XMI file and as a FRAME toolbox. 

To open the NRA first the toolbox must be loaded into empty EA project and then XMI with the NRA imported to that file. Any other sequence will break the stereotypes.

## Website with browsable NRA

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
