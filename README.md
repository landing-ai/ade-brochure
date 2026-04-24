# ADE Brochure

Versioned home for the Agentic Document Extraction (ADE) brochure and related collateral. Files here are the source of truth; automations keep them in sync with upstream design exports.

## Current brochure

- **File:** [`Agentic_Document_Extraction_Brochure.pdf`](./Agentic_Document_Extraction_Brochure.pdf)

### Open with clickable links

GitHub's in-page PDF preview strips hyperlinks. Use one of these instead:

- [Open raw PDF in browser](https://raw.githubusercontent.com/landing-ai/ade-brochure/main/Agentic_Document_Extraction_Brochure.pdf) — Chrome, Firefox, and Safari render it with working links.
- [Open in Mozilla pdf.js viewer](https://mozilla.github.io/pdf.js/web/viewer.html?file=https://raw.githubusercontent.com/landing-ai/ade-brochure/main/Agentic_Document_Extraction_Brochure.pdf)
- [Open in Google Docs viewer](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/landing-ai/ade-brochure/main/Agentic_Document_Extraction_Brochure.pdf)

## Updating a brochure

1. Drop the new PDF in the repo root, keeping the existing filename so links don't break.
2. Commit on a branch and open a PR — reviewers can use the pdf.js viewer link above to verify links click through.
3. Merge to `main`; the raw/viewer URLs above update automatically.

## Planned automations

- Scheduled pull of the latest design export into a PR.
- PDF link-check on every PR (fail if any hyperlink 404s).
- Slack/email notification when `main` gets a new brochure version.
