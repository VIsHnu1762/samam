# Personas: who we build for, and what they actually need

> Rule: a feature only enters the backlog if it serves one of these people's real jobs.

---

## 1. Arjun: final-year student, Mac user (primary)
**Context:** Uses a MacBook and an Android phone. Teachers, placement cells and companies send .docx files made on Windows Word. He has no Microsoft 365 license.

**Jobs to be done**
- Open a .docx and see it exactly as the sender made it
- Edit his resume / report on phone, then finish it on Mac without the layout breaking
- Submit assignments and resumes as clean PDFs

**Pains**
- Pages shifts fonts, spacing and tables; resume goes from 1 page to 2
- Online tools hit daily limits or ask to pay right at download
- Uncomfortable uploading his resume and ID to unknown servers

**Needs from Samam:** faithful preview, "freeze layout" to PDF, merge/compress, no signup.

---

## 2. Priya: job and exam applicant (primary, India-specific)
**Context:** Applies on government, exam and job portals from her phone or a cyber café.

**Jobs to be done**
- Upload photo, signature and certificates in the exact format the portal demands (e.g. JPG under 50 KB, PDF under 200 KB, set pixel size)
- Combine scanned pages into one PDF
- Convert PDF to image or image to PDF

**Pains**
- Portals reject files for size or format, often near deadlines
- Has to juggle 3-4 different websites for one application
- Slow mobile data; heavy sites fail

**Needs from Samam:** "portal-ready" presets (target size in KB, dimensions, format), works offline and on low-end phones.

---

## 3. Ravi: small office / shop owner (secondary)
**Context:** Runs a small business or a print/xerox shop. Handles invoices, quotations, ID copies and forms for customers daily.

**Jobs to be done**
- Merge, split, rotate, reorder pages quickly
- Sign and send quotations
- Print documents that look right

**Pains**
- Can't justify Acrobat subscription
- Customer IDs uploaded to random sites is a privacy risk

**Needs from Samam:** fast batch tools, signing, privacy by default.

---

## Persona-to-feature map
| Feature | Arjun | Priya | Ravi |
|---|---|---|---|
| Faithful .docx preview / freeze to PDF | ★★★ | ★ | ★★ |
| Merge / split / reorder | ★★ | ★★★ | ★★★ |
| Compress to target size (KB) | ★★ | ★★★ | ★ |
| PDF ⇄ image | ★ | ★★★ | ★★ |
| Sign | ★ | ★ | ★★★ |
| No signup, no upload | ★★★ | ★★ | ★★★ |
| Works on low-end phone / offline | ★ | ★★★ | ★★ |

## Validation plan (before we build beyond MVP)
- Interview 5 people per persona (classmates, placement cell, a xerox shop)
- Ask: "Last time a document gave you trouble, what happened?" (not "would you use this?")
- Collect real broken files and real portal size rules; log them in DEVLOG

## Who else Samam serves
| Tier | Categories |
|---|---|
| Primary (v1.0) | Print/xerox/cyber café shops, Common Service Centre operators, college students, exam and job aspirants |
| Secondary (v1.1) | IT professionals and technical writers, teachers and college offices, HR/admin in small firms, small business owners, patients and caregivers |
| Served through others | Seniors and first-time digital users (via shops and CSCs) |
| Later | Freelancers, real estate and legal clerks, office professionals |
| Not our market | CAs, lawyers, document specialists |
