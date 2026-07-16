# York College Nursing Club Website — Master Handoff
*For starting the build in Claude Code. Everything from the planning conversation lives in this one file.*

---

## 👋 START HERE (instructions for the Claude Code session)

This file is the complete output of a planning conversation for a **York College Department of Nursing student resource site**, run by the Cohort Secretary / Nursing Club leadership.

**What this project is:** a static website (not an official college publication — see framing note below) that centralizes forms, policies, admission info, clinical site info, and other scattered nursing-program content into one place, prioritized by what actually confuses students most.

**Source documents that should sit alongside this file** in a `source-docs/` folder — ask the user to confirm they've added these before building pages that reference them:
- `Nursinghandbook.pdf` — 2025-2026 Nursing Student Handbook
- `Physical_Exam.pdf` — official York College Medical Record / Physical Exam form
- `Fall_2026_Undergraduate_Grid_Academic_Calendar.pdf`
- `Spring_2027_Undergraduate_Grid_Academic_Calendar.pdf`

**Suggested first steps in this session:**
1. Confirm the source PDFs above are present in the project folder
2. Propose a simple site structure/file layout (plain HTML/CSS is probably right for a site this size — no need for a framework unless the user wants one)
3. Build Tier 1 pages first (see below) since that content is 100% ready
4. Ask the user about hosting (GitHub Pages vs. Netlify/Vercel — this was left undecided in planning) before finalizing folder structure, since it can affect setup

**Framing reminder to carry through every page of copy:** this is a **Nursing Club / student-leadership resource**, not an official York College or CUNY publication. Content should read as "here's what students and cohort leadership have gathered to help you," not as an authoritative institutional source. Anywhere content could be mistaken as official (forms, deadlines, fees, policies), include a small disclaimer/link back to the official source — both to protect accuracy and to avoid stepping on the college's toes.

---

## SITE MAP & PRIORITY TIERS

### TIER 1 — Build First

**1. Policy Hub** — *100% ready from the handbook, reformat only*
- Attendance & Lateness Policy
- Uniform Policy (Generic + RN-BS, grooming standards)
- Grading Scale & Progression/Dismissal Policy
- Testing Day Rules (exam procedures, restroom policy, electronics, etc.)
- Clinical Requirements (CPR, health clearance, CastleBranch, background checks, COVID policy, **Infection Control Certification** — see Source 4)
- Academic Integrity & AI Policy
- Withdrawal Policy (W vs WU, deadlines)
- Appeals Policy & APR Committee process
- Format idea: collapsible accordion/tabs, one policy per tab, not a wall of text

**2. Forms Library** — organize by "when you'd need it," not alphabetically

| Situation | Form | Status |
|---|---|---|
| Missing clinical | Absence/appeal letter to APR | Need file |
| Health clearance | Medical-Physical exam form (incl. immunization history) | ✅ Have it — `Physical_Exam.pdf` |
| Switching clinical sites | Transfer request | Need file |
| Course withdrawal | Schedule Builder / petition (Rm AC-4G04) | Need file/link |
| Grade appeal | Grade appeal letter | Need file |
| INC grade | INC extension petition | Need file |

Each entry: what it's for → who approves it → typical turnaround → download link.

**3. Start Here / New Student Page** — assembled from handbook + live site sources
- Orientation basics (mandatory, held June/July)
- Health clearance checklist (full list below in "CastleBranch Requirements")
- CastleBranch account setup: **$94.18**, package code **UQ29DTIM**
- Drug test timing: no earlier than 2 weeks before classes start, but at least 1 day before
- Uniform purchase: Meridy's Uniforms, passcode **York2002**
- NEX exam setup warning (see "NEX Examination" section — wrong account setup risks a paid retake)
- ⭐ Callout: WA grade issued for immunization non-compliance — pull the live date each semester (see Academic Calendar section)
- Key contacts
- Link out to Forms Library + Policy Hub

### TIER 2 — Build Second

**4. Admission Criteria** — ready from handbook + live application page
- Generic BS track: 5 key pre-req courses (ENG 125, PSY 102, BIO 234, BIO 235, CHEM 106/107), 3.0 GPA minimum in those 5, NLN NEX exam, 50th percentile minimum
- RN-BS track: NURS 200 Challenge Exam (80%+), NURS 203 (C+ min), current unencumbered NY RN license
- Immigration status documentation categories
- Criminal background check disclosure
- Fall 2026 application deadline: **May 25, 2026** (link emailed in March — contact gbranch@york.cuny.edu if missing)
- Priority seating: up to 5 students who started/maintained their college career at York, ranked by GPA + NEX score

**5. Course Plan / Semester Sequence** — ready from handbook 4-year plan tables
- Filterable by Pre-Nursing / Semester 1–4
- Generic track table + RN-BS track table
- Course descriptions (linked per course)
- QCC-to-York transfer sequence for that specific pathway
- Gen-Ed/Common Core category breakdown (from catalog page) — which courses satisfy which bucket
- Degree completion rules: 120 credits total, 60 liberal arts credits, 40 in-residence, 2.0 min GPA

**6. Clinical Site Directory** — general info pages, NOT semester assignments (availability shifts unpredictably, even faculty don't know in advance — frame as "things to know if you end up here")

| Site | Address | Phone |
|---|---|---|
| Flushing Hospital Medical Center | 4500 Parsons Blvd, Flushing, NY 11355 | (718) 670-5000 |
| Jamaica Hospital Medical Center | 8900 Van Wyck Expressway, Jamaica, NY 11418 | (718) 206-6000 |
| Queens Hospital Center | 82-68 164th St, Jamaica, NY 11432 | (718) 883-3000 |
| Long Island Jewish (LIJ) Forest Hills — Northwell | 102-01 66th Road, Forest Hills, NY 11375 | (718) 830-4000 |
| Elmhurst Hospital Center (NYC H+H) | 79-01 Broadway, Elmhurst, NY 11373 | (718) 334-4000 |
| Bellevue Hospital (NYC H+H) | 462 First Ave, New York, NY 10016 | (212) 562-4141 |
| Manhattan VA Medical Center | 423 East 23rd St, New York, NY 10010 | (212) 686-7500 |
| Venture House (Queens location) | 150-10 Hillside Ave, Jamaica, NY 11432 | (718) 658-7201 |

Exterior reference photos for each site were gathered during planning via web image search — re-search by hospital name if needed in this session; verify usage rights before publishing (prefer each hospital's own official media/press page over news photography).

Still needed (not googleable — real student experience only): parking situation, dress code quirks, "what to expect" tips, best transit route from campus. Crowdsource from Nursing Club.

**7. Faculty & Staff Directory** — ready from handbook, just needs clean layout (names/titles/emails — see handbook)

Nursing Club officers (current, confirmed):
- President: Nazia Hossain
- Vice President: Oscar Leyva
- Secretary: Sunny Sediqi
- Treasurer: Stacy Hutchinson
- Social Media Liaison: Maria Molina
- Community Liaison: Shani Cameron
- Financial Liaison: Palmer
- Faculty Advisor: Dr. Margarett Alexandre
- Meetings: Science Building, Room 133

### TIER 3 — Nice to Have

**8. Academic Calendar** — have Fall 2026 + Spring 2027 (source PDFs in `source-docs/`)

Key dates to surface (not the full grid):

| Event | Fall 2026 | Spring 2027 |
|---|---|---|
| First day of classes | Aug 28 | Jan 28 |
| Last day to add a course | Sep 3 | Feb 3 |
| Last day to drop w/o W grade | Sep 17 | Feb 17 |
| **WA grade — immunization non-compliance** | **Sep 27** | **Feb 25** |
| Midterm period | Oct 6–14 | Mar 15–21 |
| Course withdrawal deadline (W grade) | Nov 6 | Apr 5 |
| Finals | Dec 15–21 | May 21–27 |
| Degree conferral | Jan 1, 2027 | Jun 1, 2027 |

Note: these are college-wide, not nursing-specific, but govern the deadlines nursing students live by. Will need re-gathering each semester — check if the Registrar posts these at a predictable URL so this section can link out instead of needing manual updates.

**9. FAQ** — build from leadership's actual repeat questions (not yet gathered — ask the user)

**10. Announcements / News Feed**

**11. Prospective Student Landing Page** — ready from handbook (mission, philosophy, outcomes)

**12. Accreditation blurb** — ACEN, "Continuing Accreditation" status, contact: 3390 Peachtree Road NE, Suite 1400, Atlanta, GA 30326 / (404) 975-5000

---

## CastleBranch Health Clearance Requirements (full checklist for Start Here)
- MMR: 2 vaccinations OR positive antibody titer for all 3 components
- Varicella: 2 vaccinations OR positive antibody titer
- Hepatitis B: 3 vaccinations, positive titer, OR declination waiver
- Tuberculosis: annual renewal — 1-Step TB skin test, QuantiFERON Gold blood test, or chest x-ray if positive
- Tetanus: renews every 10 years
- CPR Certification: must be AHA **Healthcare Provider** course specifically; front + back copy, signed card
- Physical Exam: official school form, signed *and* stamped by physician/NP/PA; renews annually by **June 15**
- Title IX Sexual Harassment Training certificate
- FIT Test results (respirator fit test)
- COVID-19 vaccination documentation (must include manufacturer)
- Influenza: required annually Aug–March, or declination waiver; must include lot # and expiration date
- Infection Control Certification (from live application page, not in printed handbook)

Deadlines: Generic students' docs due 3rd week of July (fall); RN-BSN students' docs due 4th week of November (spring). Drug test: no earlier than 2 weeks before classes start, at least 1 day before.

---

## NEX Examination (for Start Here / Admission Criteria)
- Cost: $80, purchased via National League for Nursing (NLN) Testing Portal
- 90-day window to take it once purchased
- Last date to take NEX for Fall 2026 admission: Monday, May 25, 2026
- 30-day mandatory wait before a retake after failing
- Fully remote now (no longer offered at York's Testing Center)
- ⚠️ Institution code required at account setup: **476695-01 - York College - Queens** — wrong setup disconnects results from York, risking a forced paid retake
- ADA accommodation: NLN no longer processes requests directly — students purchase the "ACC version" of the test (same $80) for extended time
- Office contact: (718) 262-2054, M–F 9AM–5PM

---

## Known Content Issues on the Official Site (flag to department, don't just silently fix)
1. **"Nursing Generic (BS) Application" page displays RN-BS admission criteria** instead of Generic criteria (references RN licensure requirement, junior-year entry) — likely a copy-paste error. Good talking point for why this project matters.
2. **CastleBranch fee is stale in two places**: handbook says $89.98, live Undergrad Policies page says $65.00 — actual current fee is **$94.18** (confirmed directly, package code UQ29DTIM).
3. **Nursing Club officer roster is stale on the Advisory Board page** (lists Nicele Arana et al.) vs. the correct current roster on the dedicated Club page (Nazia Hossain et al., confirmed current).

---

## Decisions Made During Planning
- **Scope: BSN only** (Generic + RN-BS tracks). MS Nursing Education program explicitly excluded.
- **Not an official college site** — framed as a Nursing Club/student resource throughout.
- **Tuition/fee info excluded** — out of scope for a student-run resource.
- **Clinical Site Directory is general info, not a scheduling tool** — availability is unpredictable each semester.

## Still Open (not resolved during planning — flag to user early in the Code session)
- Hosting choice: GitHub Pages vs. Netlify/Vercel vs. undecided
- Who else needs edit access later (just the user, other officers, or future cohort secretaries) — affects whether a CMS-lite approach is worth it vs. plain static files
- Real FAQ list (needs to come from the user's actual experience, not a document)
- Per-clinical-site details beyond address/phone (parking, dress code, tips)
- Additional forms beyond the physical exam form (absence letters, transfer requests, grade appeal, INC petition)
