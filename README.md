# Connolly Insurance Group - GOAL Reports

Static client reporting site for Connolly Insurance Group (Allstate, Hixson TN). No build step.

| Page | File |
| --- | --- |
| Report hub | `index.html` |
| TN Auto campaign configuration | `tn-auto.html` |
| TN Home campaign configuration | `tn-home.html` |

## Deploy (Vercel)

Import the repo in Vercel with Framework Preset **Other**, no build command, output directory `.` (all set in `vercel.json`). Clean URLs are on (`/tn-auto`), and pages are served `noindex`.

Each page is a self-contained HTML file (logos inlined) built on the GOAL Structured Dashboard design with the shared light/dark toggle.
