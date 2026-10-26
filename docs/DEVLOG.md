# Daily Dev Log: Samam

Format: **Did / Fixed / Learned / Next / Blockers**

---

## 2026-10-26 (Day 0)
**Did**
- Chose the problem: documents look different on phone vs Mac (broken alignment, clumped text)
- Chose the product: free, browser-based, privacy-first document toolkit
- Wrote vision and backlog; set scope boundaries and milestones
- Named it: product **Samam**, brand **Samam Labs**, AI teammate **Sakha**
- Defined 3 personas (Arjun, Priya, Ravi) and mapped features to them
- Mapped competitors and our position (privacy + fidelity + portal-ready)
- Added "portal-ready" epic after the applicant persona surfaced it
- Set up repo structure locally

**Fixed:** nothing yet (planning day)

**Learned**
- Layout breaks because of font substitution and reflow; PDF freezes layout, .docx does not
- Indian applicants have a sharp, specific pain: portals reject files over a size limit

**Next**
- Create empty GitHub repo `samam`; push this setup
- Decide stack (B-3)
- Start interviews (V-1, V-2) and collect broken files (V-4)

**Blockers:** GitHub repo must be created by the owner (Sakha cannot create new repos). Resolved: repo live.

---

## 2026-10-26 (Day 0, R&D)
**Did**
- Market and competitor research (kept private)
- Expanded scope to 45 features across 8 modules; prioritized into 4 phases with gates
- Sharpened the two differentiators: Fidelity Check and Application Kit

**Learned**
- A generic "private PDF toolkit" is not enough on its own; job-based flows are the gap
- .docx to PDF can now run fully in the browser via WebAssembly

**Next**
- Start validation interviews (V-1, V-2)

**Blockers:** none

---

## 2026-10-26 (Day 0, scope update)
**Did**
- Added Page Flow Check (F-8, P0) and Page Flow Fix (F-9, P1): stranded headings, lone lines, split tables, empty pages after PDF export
- Agreed working rule: no technical work until the founder says go; every screen and button needs a written reason
- Put stack choice (B-3) on hold

**Next**
- Screen-by-screen product spec with a reason for every element
- Validation interviews (V-1, V-2)

**Blockers:** none

---

## 2026-10-26 (Day 0, release date)
**Did**
- Set the v1.0 release date: **1 Jan 2027**
- Dated plan: shape until 15 Nov (spec freeze), build 16 Nov - 24 Dec (feature freeze), beta 25-31 Dec
- v1.0 = all P0 items; P1 items move to v1.1 (Feb 2027)

**Next**
- Screen-by-screen spec, starting with home and the Fidelity + Page Flow journey

**Blockers:** none

---

## 2026-10-26 (Day 0, cross-platform fidelity)
**Did**
- Widened fidelity to all standard platforms: Word (Win/Mac), Pages, Google Docs, LibreOffice, phone
- Added Platform Preview (F-10), Compatibility Report (F-11, lite in v1.0), Portable .docx (F-12)
- Added fidelity test lab (V-5) to ground predictions in real screenshots

**Next**
- Screen-by-screen spec

**Blockers:** none

---

## 2026-10-26 (Day 0, user research)
**Did**
- Mapped where PDFs show up in real life and the 8-stage PDF lifecycle
- Classified users into 8 segments by frequency and skill; v1.0 targets students, applicants, print shops
- Listed built-in tricks users don't know; decided Samam should do them and explain them
- Added C-10, C-11, C-12, F-13, K-9, X-8 (P0); raised PDF to .docx to P2. Scope: 56 features
- Drafted interview questions and an 8-question survey

**Next**
- Run 15 interviews and collect 100 survey answers by 15 Nov
- Screen-by-screen spec

**Blockers:** none

---

## 2026-10-26 (Day 0, big bets)
**Did**
- Added six evidence-backed bets: Document Wallet, Pre-flight check card, Resume Check, print-shop QR handoff, one-tap self-attest, shareable tip cards
- v1.0 gains Resume Check (lite) and Pre-flight (lite); both reuse engines already planned
- Scope: 61 features

**Working agreement**
- Sakha brings at least one new evidence-backed idea or risk to every session, not only answers

**Next**
- Interviews and survey; screen-by-screen spec

**Blockers:** none

---

## 2026-10-27 (Day 1)
**Did**
- Mapped 14 user categories by occupation into 4 tiers
- Added Common Service Centre operators as a primary category
- Added C-13 (ID card print layout), C-14 (print-ready check), F-15 (tech-doc export check). Scope: 64 features

**Next**
- Interview 1 print shop and 1 CSC operator this week

**Blockers:** none
