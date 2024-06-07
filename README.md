# MkDocs 4 FRAME

Proof of concept for publishing browsable HTML UML models as created by Enterprise Architect.

# Local Installation

Using Python 3.12 and pdm:

$ pdm install

Before using the installed mkdocs command, make sure you activate it's virtualenv.

## Configuration

There is nothing to configure.

## Local development

Edit files in the docs folder. See https://www.mkdocs.org/user-guide/writing-your-docs/

Run from project root:

$ mkdocs serve

Then open http://localhost:8000

This shall update as soon as you save any content file.

## Deploying on GitHub Pages

Just push the repository to GitHub. It shall build the page on it's own.
