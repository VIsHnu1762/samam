# Backlog & Roadmap: Samam

Priority: P0 = MVP, P1 = next, P2 = later, P3 = stretch. Persona: A = Arjun (Mac student), P = Priya (applicant), R = Ravi (small office).

## Roadmap
Started 26 Oct 2026. **v1.0 release: 1 Jan 2027.**

| Phase | Dates | Focus | Gate |
|---|---|---|---|
| Shape | 26 Oct - 15 Nov | Screen-by-screen spec, interviews. No code. | Spec freeze, 15 Nov |
| Build 1 | 16 Nov - 6 Dec | Core PDF tools | Core tools working |
| Build 2 | 7 Dec - 24 Dec | Fidelity, page flow, photo/signature tools | Feature freeze, 24 Dec |
| Beta | 25 Dec - 31 Dec | 25 beta users, fixes only | No P0 bugs open |
| **v1.0** | **1 Jan 2027** | All P0 items | Public release |
| v1.1 | Feb 2027 | P1 items (page flow fix, exam kit, sign, offline) | — |

## Foundation
| ID | Task | Status |
|---|---|---|
| B-1 | Name and brand | Done |
| B-2 | Repo and docs | Done |
| B-3 | Choose stack (after product spec is complete) | On hold |
| B-4 | UI shell: upload, drag and drop, download | Todo |
| B-5 | Deploy pipeline | Todo |

## Validation
| ID | Task | Persona | Status |
|---|---|---|---|
| V-1 | Interview 5 students (Mac + Windows) | A | Todo |
| V-2 | Interview 5 applicants; collect portal rules | P | Todo |
| V-3 | Talk to 2 print/xerox shops | R | Todo |
| V-4 | Collect 10 files that break across devices | A | Todo |

## Features
| ID | Feature | Persona | Priority | Status |
|---|---|---|---|---|
| **Core PDF** |||||
| C-1 | Merge with drag-to-reorder | P, R | P0 | Todo |
| C-2 | Split / extract pages | P, R | P0 | Todo |
| C-3 | PDF to JPG/PNG | P | P0 | Todo |
| C-4 | Images to PDF | P, R | P0 | Todo |
| C-5 | Compress PDF to a target size (KB) | A, P | P0 | Todo |
| C-6 | Rotate, delete, reorder pages | R | P1 | Todo |
| C-7 | Page numbers, watermark | R | P2 | Todo |
| C-8 | Password protect / unlock | R | P2 | Todo |
| C-9 | Strip hidden metadata | all | P2 | Todo |
| **Fidelity** |||||
| F-1 | .docx to PDF in the browser | A | P0 | Todo |
| F-2 | Font audit (used, missing, substituted) | A | P0 | Todo |
| F-3 | Page-count guard ("still 1 page") | A | P1 | Todo |
| F-4 | Side-by-side preview across devices | A | P1 | Todo |
| F-5 | Swap to metric-compatible fonts | A | P1 | Todo |
| F-6 | Open .pages files without a Mac | A | P2 | Todo |
| F-7 | PDF to .docx | A | P3 | Todo |
| F-8 | Page Flow Check: flag stranded headings, lone lines at page top/bottom, split tables, blank gaps, empty pages | A | P0 | Todo |
| F-9 | Page Flow Fix: one-tap fixes with before/after preview | A | P1 | Todo |
| **Application Kit** |||||
| K-1 | Photo resize to exact px + KB | P | P0 | Todo |
| K-2 | Signature cleanup | P | P0 | Todo |
| K-3 | Verified exam presets (top 10) | P | P1 | Todo |
| K-4 | One flow: pick exam, get every file | P | P1 | Todo |
| K-5 | Name + date-of-photo overlay | P | P1 | Todo |
| K-6 | Pre-upload rejection checker | P | P1 | Todo |
| K-7 | Download all as ZIP | P | P2 | Todo |
| K-8 | Community presets with review | P | P3 | Todo |
| **Sign & forms** |||||
| S-1 | Draw / type / upload signature | R | P1 | Todo |
| S-2 | Fill form fields | P, R | P1 | Todo |
| S-3 | Stamp, date, initials | R | P2 | Todo |
| S-4 | Flatten after signing | R | P2 | Todo |
| **Edit** |||||
| E-1 | Highlight, text box, draw | A, R | P2 | Todo |
| E-2 | True redaction | R | P2 | Todo |
| E-3 | OCR | R | P3 | Todo |
| E-4 | Edit existing PDF text | A | P3 | Todo |
| **Experience & trust** |||||
| X-1 | Mobile-first, low-end Android | all | P0 | Todo |
| X-2 | No signup, no upload | all | P0 | Todo |
| X-3 | Installable offline app (PWA) | P | P1 | Todo |
| X-4 | Android "Share to Samam" | P, R | P2 | Todo |
| X-5 | Tamil and Hindi UI | P, R | P2 | Todo |
| X-6 | Local history | all | P3 | Todo |
| X-7 | Accessibility | all | P2 | Todo |
| T-1 | "Zero uploads" proof page | all | P1 | Todo |
| T-2 | Open source, reproducible build | all | P0 | Doing |
| T-3 | Cookie-free analytics | all | P1 | Todo |
| G-1 | Landing pages per task / exam | P | P1 | Todo |
| G-2 | Feedback + opt-in broken-file submission | all | P1 | Todo |

## Not building (for now)
Accounts, payments, native apps, real-time collaboration, a full Word editor.
