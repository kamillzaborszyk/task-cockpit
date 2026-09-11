# History methodology

The application was developed as sequential standalone HTML files before Git was introduced. The files from version 1.30 through 1.46 and the first 2.0 alpha were imported in version order.

This produces a real and inspectable Git diff between every supplied snapshot. It does not recreate the original commit dates or claim that Git was used during the earlier development period.

## Validation

JavaScript embedded in every snapshot was extracted and checked with `node --check` during import.

Two supplied files failed syntax validation and are not used as release versions:

- `task_cockpit_1_31.html`, superseded by `task_cockpit_1_31_ready.html`
- `task_cockpit_2.0.0-alpha.1.html`, superseded by the corrected duplicate `task_cockpit_2.0.0-alpha.1 1.html`

The invalid files are retained under `archive/rejected/` for traceability.
