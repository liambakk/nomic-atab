# Keeping the files organised

Keep the source files in a private folder shared with Liam. Use clear file names and point to them from the case notes. Keep passwords and access tokens out of the notes and index.

## File index

The [file index](../data-manifest.csv) is there if helpful. Start with the file name, where to find it and which case it relates to. Fill the other columns where the information is available; there is no need to fill every cell before sharing the files. Use one row per file or version.

| Column | Meaning |
| --- | --- |
| `file_id` | Stable reference such as `FILE-001`; use it in case notes. |
| `company_ref` | Selected company name or consistent reference. |
| `workflow_ref` | Reference used in the workflow description. |
| `case_refs` | Related case references separated by semicolons. |
| `filename` | File name within the private source folder. |
| `private_location` | Folder-relative path or access-controlled link, without credentials. |
| `source_system` | System, document collection or communication channel of origin. |
| `record_type` | What the file contains; distinguish events, snapshots and supporting documents. |
| `period_start` and `period_end` | Dates covered, where known. |
| `exported_at` | Export date and time, including timezone. |
| `version` | Export or file version; preserve older versions if needed and permitted. |
| `permission_ref` | Reference to the sharing notes for the material sent to Liam. |
| `notes` | Gaps, replacements or other interpretation needed. |

Use `unknown` or `not applicable` where appropriate. Preserve original records and note any changes. If names or IDs are replaced, use consistent replacements across related files so cases can still be connected.

## Local copies

If an engineer needs local working copies, use `data/raw/`, `data/exports/` or `data/private/`. These folders are excluded from Git by the supplied `.gitignore`. The ignore file is a convenience, not access control; review changes before committing.

## Small examples in the repository

Complete real case narratives alongside the source records in the private folder. Repository examples must be suitable for its readers; while the repository is public, that means anyone on the web. Identify invented teaching examples explicitly and keep them separate from real cases.
