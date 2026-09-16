# Source records and file index

Keep the source exports in a private folder agreed with Liam. The repository holds instructions, approved explanatory material and an index. Share a folder link that requires the intended person's access; do not put passwords, access tokens or signed download links in the index or issues.

## File index

Add one row per source file or distinct version in [data-manifest.csv](../data-manifest.csv). The file starts with column names only; it contains no supplied records.

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
| `permission_ref` | Reference to the applicable permission record and scope. |
| `notes` | Gaps, replacements or other interpretation needed. |

Use `unknown` or `not applicable` where appropriate. Preserve original records and note any changes. If names or IDs are replaced, use consistent replacements across related files so cases can still be connected.

## Local copies

If an engineer needs local working copies, use `data/raw/`, `data/exports/` or `data/private/`. These folders are excluded from Git by the supplied `.gitignore`. The ignore file is a convenience, not access control; review changes before committing.

## Small examples in the repository

Include an example or case narrative only when its contents are cleared for the repository's collaborators. Cases can contain confidential details even when the source files are stored elsewhere. Otherwise keep the completed notes with the source records and use a reference here. Identify invented teaching examples explicitly and keep them separate from real cases.
