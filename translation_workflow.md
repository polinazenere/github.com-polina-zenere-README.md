# Translation Workflow with CAT Tool and Pandoc

## Step 1: Create Source Document
- Wrote technical specification in Markdown format
- Used Pandoc-compatible syntax

## Step 2: CAT Tool Translation
- Used OmegaT CAT tool for translation
- Imported `heroes_path_spec.md`
- Translated to English
- Exported as `heroes_path_spec_en.md`

## Step 3: Create Translation Memory
- Extracted key terminology
- Created translation memory file
- Ensured consistency across document

## Step 4: Pandoc Conversion Commands
The following commands can be used with Pandoc:

```bash
# Convert to PDF
pandoc heroes_path_spec.md -o output.pdf

# Convert to HTML
pandoc heroes_path_spec.md -o output.html

# Convert to DOCX
pandoc heroes_path_spec.md -o output.docx
