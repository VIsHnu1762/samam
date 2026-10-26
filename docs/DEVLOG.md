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
