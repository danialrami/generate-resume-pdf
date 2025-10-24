# Generates my PDF resume

This project uses a YAML workflow to build a LaTeX resume and compile it into PDF.

## New YAML Workflow

The `resume.yaml` file defines the data for your resume. You can edit it to add sections, experiences, education, etc. The CLI will render the template and produce `daniel_resume.pdf`.

## Usage

```bash
# Build the PDF
python -m yaml_resume_builder.cli build
```

