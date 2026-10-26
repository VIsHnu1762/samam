# Product Backlog: Samam

Priority: P0 = MVP, P1 = next, P2 = later, P3 = stretch. Status: Todo / Doing / Done / Dropped.
Persona: A = Arjun (Mac student), P = Priya (applicant), R = Ravi (small office).

## Epic 0: Foundation
| ID | Task | Persona | Priority | Status |
|----|------|---------|----------|--------|
| F-1 | Choose stack | all | P0 | Todo |
| F-1b | Choose name and brand (Samam) | all | P0 | Done |
| F-2 | Repo, README, folder structure | all | P0 | Doing |
| F-3 | UI shell: upload, drag and drop, download, mobile-first | all | P0 | Todo |
| F-4 | Deploy pipeline (Vercel / Netlify / GitHub Pages) | all | P0 | Todo |

## Epic 1: Validate the personas
| ID | Task | Persona | Priority | Status |
|----|------|---------|----------|--------|
| V-1 | Interview 5 students (Mac + Windows) | A | P0 | Todo |
| V-2 | Interview 5 applicants; collect real portal size rules | P | P0 | Todo |
| V-3 | Talk to 2 xerox/print shops | R | P1 | Todo |
| V-4 | Collect 10 real files that break across devices | A | P0 | Todo |

## Epic 2: Core PDF tools (MVP)
| ID | Task | Persona | Priority | Status |
|----|------|---------|----------|--------|
| P-1 | Merge PDFs (with reorder) | P, R | P0 | Todo |
| P-2 | Split PDF (page ranges) | P, R | P0 | Todo |
| P-3 | PDF to images (PNG/JPG) | P | P0 | Todo |
| P-4 | Images to PDF | P, R | P0 | Todo |
| P-5 | Compress PDF | A, P | P1 | Todo |
| P-6 | Sign PDF (draw/type/upload) | R | P1 | Todo |
| P-7 | Rotate / delete / reorder pages | R | P1 | Todo |

## Epic 3: Portal-ready (India differentiator)
| ID | Task | Persona | Priority | Status |
|----|------|---------|----------|--------|
| R-1 | Compress image/PDF to exact target size (KB) | P | P0 | Todo |
| R-2 | Resize photo/signature to exact pixels | P | P1 | Todo |
| R-3 | Presets for common portals (from V-2 data) | P | P1 | Todo |

## Epic 4: Layout fidelity (core differentiator)
| ID | Task | Persona | Priority | Status |
|----|------|---------|----------|--------|
| L-1 | Root-cause each broken file from V-4 | A | P0 | Todo |
| L-2 | Docx to PDF with layout frozen (LibreOffice service) | A | P1 | Todo |
| L-3 | Missing-font detector and warning | A | P1 | Todo |
| L-4 | Side-by-side "does it look the same?" check | A | P2 | Todo |

## Epic 5: Editing
| ID | Task | Persona | Priority | Status |
|----|------|---------|----------|--------|
| E-1 | Annotate (highlight, text box, draw) | A, R | P1 | Todo |
| E-2 | Fill forms | P, R | P1 | Todo |
| E-3 | PDF to Docx | A | P2 | Todo |
| E-4 | Light text editing in PDF | A | P3 | Todo |

## Epic 6: Quality and launch
| ID | Task | Persona | Priority | Status |
|----|------|---------|----------|--------|
| Q-1 | Large file test (100+ pages) on mid-range phone | all | P1 | Todo |
| Q-2 | Works offline (PWA) | P | P2 | Todo |
| Q-3 | 25 real users, feedback form | all | P0 | Todo |
| Q-4 | README with demo GIF | all | P0 | Todo |

## Not building (for now)
OCR, payments, accounts, native apps, real-time collaboration, full Word editor.

## Milestones
- **M1, week 1:** F-1 to F-3, V-1/V-2 started, P-1, P-2
- **M2, weeks 2-3:** P-3, P-4, R-1, P-5
- **M3, week 4:** deployed, V-4 + L-1 done, 10 users testing
- **M4, weeks 5-6:** L-2, P-6, fixes from feedback, README + demo, 25 users
