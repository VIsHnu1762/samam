# Vision: Samam

**Your document, the same everywhere.**

## Problem statement
People edit a document on one device and it breaks on another: fonts swap, spacing shifts, tables collapse, a 1-page resume becomes 2. On top of that, applicants fight portal rules (file type, size in KB, pixel size) with a mix of ad-filled sites that upload their private files. Fixing all this properly today means paying for Acrobat or Microsoft 365.

## Root causes
| Pain | Root cause |
|---|---|
| Layout breaks Mac vs Windows vs phone | Missing fonts get substituted; .docx reflows differently in each app (Word, Pages, Google Docs) |
| Can't edit/convert without paying | Full-fidelity tools are licensed (Acrobat, Office desktop) |
| Portal rejects the file | Each portal has its own size/format rules; no tool targets "under X KB" directly |
| Privacy fear | Free online tools process files on their servers |
| Juggling many sites | Tools are scattered: one for merge, one for compress, one for convert |

## Who it's for
See [PERSONAS.md](PERSONAS.md): **Arjun** (Mac student), **Priya** (job/exam applicant), **Ravi** (small office/shop).

## Solution
A free, browser-based toolkit that:
1. **Freezes layout:** turn any document into a PDF that looks identical everywhere
2. **Fixes files for portals:** compress/resize to an exact target, convert PDF ⇄ image
3. **Handles everyday PDF jobs:** merge, split, reorder, sign
4. **Respects privacy:** core tools run on your device; nothing uploaded

## Principles
1. Persona first: no feature without a persona job behind it
2. Fidelity: what you see on one device is what you see on all
3. Privacy by default
4. Works on a cheap phone on slow data
5. Small and finished beats big and half-done

## Boundaries (not building yet)
Full Word/Pages replacement, real-time collaboration, native apps, payments, accounts.

## Success metrics
- 25 real users across the 3 personas by week 6
- 10 real "broken files" collected and fixed
- Portal preset hits target size on first try ≥ 95% of the time
- Core tools: zero server cost; 50-page merge < 5 s on a mid-range phone

## Resume line (target)
"Built Samam, a privacy-first, browser-based document toolkit used by X students and applicants; client-side PDF processing with zero server cost."
