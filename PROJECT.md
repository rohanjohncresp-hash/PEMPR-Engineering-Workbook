# PEMPR Engineering Workbook

## Purpose

The PEMPR Engineering Workbook repository is the controlled working location for
engineering planning, asset support, maintenance, and shutdown-management
materials. It brings manuals, workbooks, SAP tools, reusable templates, figures,
presentations, and supporting documentation together in a consistent structure
so that contributors can find, review, and maintain project information.

## Repository structure

| Directory | Contents |
| --- | --- |
| `Asset Management Manual/` | Asset-management policies, procedures, and guidance. |
| `PEMPR Workbook/` | The primary PEMPR workbook and its supporting files. |
| `SAP Tools/` | SAP reports, utilities, data-loading aids, and instructions. |
| `Shutdown Management/` | Shutdown plans, schedules, checklists, and close-out material. |
| `Figures/` | Diagrams, charts, images, and other shared visual assets. |
| `Templates/` | Controlled, reusable document and spreadsheet templates. |
| `Presentations/` | Briefing packs, training slides, and project presentations. |
| `Documentation/` | General project guidance, references, decisions, and supporting records. |

## Working practices

- Store each file in the directory that best matches its purpose.
- Use clear, descriptive file names and include a revision or date where useful.
- Keep source documents in their native format and place shared figures in
  `Figures/` rather than duplicating them across documents.
- Review changes before committing, especially updates to formulas, macros, links,
  and controlled templates.
- Do not commit Microsoft Office lock files, autosave files, local editor settings,
  or operating-system metadata; these are excluded by `.gitignore`.
- Use concise commit messages that explain the engineering or documentation change.

## Document control

Git history provides the change record for repository content. Contributors should
avoid overwriting an approved document without an appropriate review and should
record significant assumptions, decisions, and release notes in `Documentation/`.
Where formal document-control requirements apply, the approved external process
remains authoritative.
