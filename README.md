# LaTeX Thesis Template

This repository provides a LaTeX template specifically designed for students at the Chair of AI Engineering, University of Passau. It is configured to ensure minimal requirements for easy compilation, both locally and on cloud-based platforms like Overleaf. 

This template offers a structured example for your thesis and includes basic formatting guidelines for citations, tables, and figures.

## Usage
- Download the files
- Choose Your Platform:
  - **Online:** Upload the files to [Overleaf](https://www.overleaf.com) for cloud-based editing and compilation
  - **Local**: Install a [LaTeX distribution](https://www.latex-project.org/get) on your computer and compile the files locally
- Select your thesis type in `main.tex` by uncommenting either `\bachelor` or `\master` in the preamble (`\bachelor` is activated by default)
- Insert personal information in the preamble of `main.tex` (`\authorname`, ...)
- Compile the LaTeX file to generate the PDF. We recommend using `pdfLaTeX`, but other engines may also work
- Write your thesis ;)

## Notes
- By default, the template uses a twosided option, which starts chapters on odd pages, making it ideal for printed versions of the thesis. However, if you prefer to optimize your LaTeX file for a digital PDF version, you should consider modifying the first two lines of `main.tex` as follows:
```tex
\documentclass[a4paper,12pt,notitlepage]{report}
\usepackage[a4paper, top=1.1in, bottom=1.1in, left=1in, right=1in]{geometry}
  ```
