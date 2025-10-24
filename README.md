# Generates my PDF resume

This project now uses a **YAML‑driven workflow** to build a LaTeX resume and compile it into PDF. The data lives in `resume.yaml` and the template is stored in `templates/resume.tex`.

## New YAML Workflow

* Create or edit `resume.yaml` with your personal information, experiences, education, skills, projects, etc. The schema follows the example in the file.
* Run the CLI to generate a LaTeX file and compile it:

```bash
# Generate LaTeX from YAML
yaml-resume-builder build --input resume.yaml --output daniel_resume.tex
# Compile to PDF (one‑page optimized)
pdflatex -interaction=nonstopmode daniel_resume.tex
```

The resulting PDF (`daniel_resume.pdf`) will be a single‑page, ATS‑friendly resume.

## Template Customization

The LaTeX template is located in `templates/resume.tex`. Feel free to tweak colors, fonts, or layout as needed.

