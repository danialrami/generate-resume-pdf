# AGENTS

## Build / Lint / Test
- **Build**: `pdflatex -interaction=nonstopmode daniel_ramirez_resume.tex`
- **Lint**: `chktex -q -l 1 daniel_ramirez_resume.tex`
- **Test**: No automated tests – run the build command and inspect the PDF.
- **Single Test**: `pdflatex -interaction=nonstopmode <file>.tex`

## Code Style Guidelines
- **Imports**: N/A (LaTeX)
- **Formatting**: 4‑space indentation, lines <80 chars.
- **Types**: N/A
- **Naming**: Section titles Title Case, labels camelCase.
- **Error Handling**: Use `\error` for missing references.
- **Comments**: Use `%` for comments.
- **Packages**: Load only necessary packages.
- **Line Length**: Keep lines <80 chars for readability.
- **Cursor Rules**: None defined in .cursor/rules.
- **Copilot Rules**: None defined in .github/copilot-instructions.md.

## Cursor / Copilot Rules
- No special rules – follow standard LaTeX conventions.
