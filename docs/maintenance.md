# Document maintenance

These steps are for Liam or an engineer maintaining the brief. They are not needed to provide the first data handoff.

## Source and Word copy

The maintained wording is in [brief.md](../brief.md). The shareable Word copy is in [deliverables](../deliverables/Ben%20-%20Liam%20and%20Atab%20data%20brief.docx). The builder preserves the agreed layout: 11-point black Helvetica throughout, with bold limited to the document title and main section headings.

## Regenerate

Use Python 3.10 or later and install the document dependency in a virtual environment:

```sh
python3 -m venv .venv
.venv/bin/python -m pip install -r requirements-docs.txt
.venv/bin/python scripts/build_brief.py
```

On Windows, use `.venv\Scripts\python.exe` for the equivalent commands. The script resolves paths relative to the repository, so it can be run from another working directory.

The builder supports this brief's headings, paragraphs, bullets, two-column tables and explicit page-break markers. It is not a general Markdown converter. Keep those supported elements when editing the source, or update the builder if the format changes.

## Review before sharing

Open or render every page after regeneration. Check wording, page breaks, table wrapping, footer position and font. The current guide has two pages. Helvetica must be available to the application rendering the document; font substitution can change its appearance even when the file specifies Helvetica.

Commit the updated Markdown and reviewed Word copy together. If only a case or system note changes, regenerating the brief is unnecessary.
