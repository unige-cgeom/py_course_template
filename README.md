# Quarto template with Python for complementary certificate of geomatics courses

## About

Quarto is an open‑source publishing system that lets you create documents, websites, books, 
blogs, presentations, and scientific reports using plain text files (e.g., .qmd). It’s
developed by Posit (formerly RStudio).

Quarto brings together a set of powerful features aimed at making scientific and technical 
writing both intuitive and fully reproducible. It supports several programming languages—including 
R, Python, Julia, allowing authors to mix narrative text and executable code seamlessly within the 
same document. 

Because Quarto is based on Markdown, writing remains simple and readable while still enabling 
sophisticated formatting.  

A key strength of Quarto is its focus on reproducibility. Code chunks are executed automatically 
during rendering, and their results—figures, tables, analyses—are directly embedded in the final output. 
This ensures that documents, reports, and publications always reflect the latest state of the underlying 
data and computations.

Quarto also integrates smoothly with scientific workflows and tools such as Jupyter, RStudio, and VS Code, 
and supports extensions for templates, filters, and themes. Citation management is built in: BibTeX and 
CSL files can be used to generate consistent references and bibliographies automatically. 
Together, these features make Quarto a versatile platform for producing high‑quality, transparent, and 
reproducible scientific content.

All materials provided in this repository are inspired by the workshop given at the Universisty of Geneva 
_"Reproducible Research Workflows with Quarto and R - Getting Started"_. All workshop material (slides and 
hands-one) are available [online](https://crsuzh.pages.uzh.ch/workshop-quarto-2025-unige/).



## Templates

This repository provides templates using Python. For detailed installation instructions see hands-on
[here](https://crsuzh.pages.uzh.ch/workshop-quarto-2025-unige/demo_py/)

The template is structured as follows:

- A Quarto Markdown (.qmd) file `index.qmd` at the root of the course folder. This file contains a YAML header with the
course title and authors (with affiliations and contact details). The rest of the file is the basic information to be 
displayed on the course homepage.
- An overall YAML (.yml) file `_quarto.yml` that contains informaiton on how the files are structured (homepage, chapters etc...). This will help during the compilation.
- Folders with additional content (e.g. for the course pages)


## Live Examples
- [SPACE-GEOLOGY (2026)](https://github.com/unige-cgeom/SPACE-GEOLOGY/). The course is 
[published online](https://unige-cgeom.github.io/SPACE-GEOLOGY/) using GitHub automatic deployment workflows.
- [Template (from this repository)](https://unige-cgeom.github.io/py_course_template)

More examples will follow!


## Deploy

To use this template m
