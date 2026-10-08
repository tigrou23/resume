# Hugo Pereira's resume

> This repository hosts my LaTeX resume in English and French.

A GitHub Action automatically compiles both versions on each push to `main` and publishes them on GitHub Pages:

- [English resume](https://tigrou23.github.io/resume/resume.pdf)
- [French resume](https://tigrou23.github.io/resume/fr/resume_fr.pdf)

To build both PDFs locally, run from the repository root:

```sh
pdflatex -interaction=nonstopmode -halt-on-error resume.tex
pdflatex -interaction=nonstopmode -halt-on-error -output-directory=fr fr/resume_fr.tex
```

Please refer to my profile for all information: [GitHub](https://github.com/tigrou23).
