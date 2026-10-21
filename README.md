# CEDoW Primary Mathematics K–6 Professional Learning

Self-paced professional learning modules for teachers in the Catholic Education Diocese of Wollongong, aligned to the NSW Mathematics K–10 Syllabus (2022) and NESA Teaching Advice.

**Live site:** https://thomask04-dotcom.github.io/cedow-primary-maths-pl/

## Modules

| Focus area | File |
|---|---|
| 1. Representing Number | `01-representing-number.html` |
| 2. Combining & Separating Quantities / Additive Relations | `02-additive-relations.html` |
| 3. Forming Groups / Multiplicative Relations | `03-multiplicative-relations.html` |
| 4. Partitioned Fractions / Quantity Fractions | `04-fractions.html` |
| 5. Geometric Measure | `05-geometric-measure.html` |
| 6. Two-dimensional Spatial Structure | `06-2d-spatial-structure.html` |
| 7. Three-dimensional Spatial Structure | `07-3d-spatial-structure.html` |
| 8. Non-spatial Measure | `08-non-spatial-measure.html` |
| 9. Data | `09-data.html` |
| 10. Chance | `10-chance.html` |

Every module follows the same seven sections:

1. The Vertical Trajectory & Big Ideas
2. Key Conceptual Shifts & Pedagogical Traps
3. Interactive Tool Lab
4. Student Diagnostic Clinic & Root Misconceptions
5. Task Makeover Studio (Working Mathematically)
6. Module Mastery Checkpoint
7. Canvas LMS Deployment Guide

## Module finder (`index.html`)

`index.html` is the home page of the site and a searchable finder for all ten modules.

**To add it to Google Sites:** in your site, choose **Insert → Embed → Embed code**, paste the whole contents of `index.html`, then drag the embed box to the size you want. When embedded, the finder hides its own header and footer, and each module opens in a new tab.

Module links point to the live site above. If the site moves, update `SITE_URL` near the bottom of `index.html`.

## Shared look

Every module uses the same header, sidebar, intro banner, section headings and footer. These come from a block of CSS marked `cd-shell-css` in the `<head>` of each module and a small script marked `cd-shell-js` at the end of each page. Both are identical in every file, so a change to the shared look should be made in all ten modules.
