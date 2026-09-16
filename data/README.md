# Keeping the files organised

Keep the source files in a private folder shared with Liam. Use clear file names and add a short explanation of what each contains. Keep passwords and access tokens out of the notes and index.

## File index

The [file index](../data-manifest.csv) is there if helpful. Start with the file name, company or platform, what the file contains and the period covered. Workflow and case references can stay blank until Liam has reviewed the data. Fill the other columns where the information is available; use one row per file or version.

| Column | Meaning |
| --- | --- |
| `file_id` | Simple reference such as `FILE-001`; use it when pointing to this file. |
| `company_ref` | Selected company name or consistent reference. |
| `workflow_ref` | Optional later, once a workflow has been identified. |
| `case_refs` | Optional later, once specific cases are being explored; separate multiple references with semicolons. |
| `filename` | File name within the private source folder. |
| `private_location` | Folder-relative path or access-controlled link, without credentials. |
| `source_system` | System, document collection or communication channel of origin. |
| `record_type` | What the file contains; distinguish events, snapshots and supporting documents. |
| `period_start` and `period_end` | Dates covered, where known. |
| `exported_at` | Export date and time, including timezone. |
| `version` | Export or file version; preserve older versions if needed and permitted. |
| `permission_ref` | Reference to the sharing notes for the material sent to Liam. |
| `notes` | Gaps, replacements or other interpretation needed. |

Leave unknown fields blank or add a short note. Preserve original records and note any changes. If names or IDs are replaced, use consistent replacements across related files so the records still connect.

## Local copies

If an engineer needs local working copies, use `data/raw/`, `data/exports/` or `data/private/`. These folders are excluded from Git by the supplied `.gitignore`. The ignore file is a convenience, not access control; review changes before committing.

## Small examples in the repository

Complete real case narratives alongside the source records in the private folder. Repository examples must be suitable for its readers; while the repository is public, that means anyone on the web. Identify invented teaching examples explicitly and keep them separate from real cases.
