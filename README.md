# Dmitry Guminov - CV

[![Build LaTeX CV](https://github.com/dimagum/cv_dmitry_guminov/actions/workflows/build.yml/badge.svg)](https://github.com/dimagum/cv_dmitry_guminov/actions)

Welcome to the repository containing the source code for my personal resume. 

🔗 [**Download the latest PDF version here**](https://raw.githubusercontent.com/dimagum/cv_dmitry_guminov/dev/CV_Dmitry_Guminov.pdf)

## Preview

<a href="https://raw.githubusercontent.com/dimagum/cv_dmitry_guminov/dev/CV_Dmitry_Guminov.pdf">
  <img src="preview.png" alt="Resume Preview" width="600" style="border: 1px solid #ddd; border-radius: 4px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</a>

## How it works (CI/CD)

This resume is written in **LaTeX**. To ensure the PDF is always up-to-date with the source code, I configured a CI/CD pipeline using **GitHub Actions**. 

Every time a change is pushed to the `.tex` file, a Dockerized LaTeX environment (`xu-cheng/latex-action`) automatically compiles the document and commits the fresh `CV_Dmitry_Guminov.pdf` back to the repository.

## Local Development

If you want to build this CV locally:

**Requirements:**
- VS Code with [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) extension
- MiKTeX / TeX Live (or Docker)

**Build:**
Just open `CV_Dmitry_Guminov.tex` in VS Code and press `Ctrl+Alt+B`.