name: RadioGenomics_pipeline

# Radiogenomics Pipeline Skill

This skill generates a study-specific RadioGenomics framework. The skill must read the local chunk file from the workspace and use only the information contained in that file. It should not add external assumptions, references, or unsupported methodological details.

## Input

- A chunked manuscript file

## Task

- Read the file
- Extract study structure
- Build RadioGenomics framework

When this skill is invoked, automatically perform the task without asking the user for additional instructions.


## Output

The response must contain only the following two outputs:

1. Conceptual framework (clear, structured)
2. Methodological pipeline ONLY as SVG diagram

## SVG Requirements

- black and white
- no background color
- boxes and arrows
- clear labels
- publication-ready layout
- editable as a standalone `.svg` file

After saving the file, only state:

`SVG diagram saved as RadioGenomics_pipeline.svg`

## Rules

- Use only file content.
- Do not hallucinate.
- Do not present a numbered menu.
- Do not ask follow-up questions.
- Do not suggest optional outputs.

