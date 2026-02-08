# DEN Working Paper Template

A Quarto template for DEN Working Papers.

## Installation

To use this template in a new project:

```bash
quarto use template <username>/den-paper
```

This will create a new directory with the template files and install the extension.

## Using the Template

The template provides a `template.qmd` file that you can use as a starting point. Key metadata fields include:

```yaml
title: "Your Paper Title"
format: den-paper-pdf

# Paper settings
manuscript: article  # article, rescience, data, software, editorial, proceedings, poster
layout: publish      # preprint or publish
year: 2026
volume: 1

# Publication info (for published layout)
published: "20 May 2026"

# Authors
author:
  - name: "Author Name"
    orcid: "0000-0000-0000-0000"
    affiliations:
      - name: "Institution, City, Country"
    email: "author@email.com"

# Keywords (maximum five)
keywords:
  - keyword one
  - keyword two

# Abstract
abstract: |
  Your abstract here...

bibliography: bibliography.bib
```

## Rendering

To render the document:

```bash
quarto render template.qmd
```

## Output

The template produces a PDF formatted for DEN Working Papers with:
- B5 paper size
- Professional typography
- Automatic bibliography formatting
- Support for figures, tables, and equations

## License

This template is released under the LaTeX Project Public License v1.3c.
