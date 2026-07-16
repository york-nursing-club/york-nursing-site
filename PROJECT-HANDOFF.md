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
| Missing clinical | vSim Clinical Replacement Packet (~23 pages) | Need file — mentioned in chat, not yet obtained |
| Health clearance | Medical-Physical exam form (incl. immunization history) | ✅ Have it — `Physical_Exam.pdf` |
| Health clearance | HRSS form (from clinical placement email, sent to Janet Tyson) | Need file — meaning/purpose needs confirming |
| Switching clinical sites | Transfer request | Need file |
| Course withdrawal | Schedule Builder / petition (Rm AC-4G04) | Need file/link |
| Grade appeal | Grade appeal letter | Need file |
| INC grade | INC extension petition | Need file |
| Nursing Club candidacy | Nursing Club Officer Form (needs 3 faculty signatures) | Need file |

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

**9. FAQ** — build from leadership's actual repeat questions. First real batch gathered from cohort chat patterns (anonymized — no names/numbers, themes only):
- How does the Prep U / ATI adaptive quiz mastery system actually work? (question set sizes, accuracy thresholds, why progress "doesn't move")
- Where do I find my Kaplan access link? (comes via school email, easy to miss)
- Where's the DocuCare access code? (instructor-specific, posted on Brightspace)
- I bought ShadowHealth directly instead of the free trial — where's my Tina Jones assignment?
- What is CircleIn and why do I have it? (frequently forgotten/unclear even after being told once)
- Is a clinical skills "demo + practice" session graded, or just practice?
- Where do I check if training videos (e.g. PPE/hand hygiene) have been posted yet?

**13. NEW — Tools & Platforms Glossary** *(added based on real chat confusion — not in original plan)*
One short section per ed-tech tool nursing students are expected to use: what it is, where to access it, and the #1 thing people get confused about. Candidates so far: Prep U/ATI, Kaplan, DocuCare, ShadowHealth, CircleIn, Brightspace (for course-specific postings like training videos). This would meaningfully cut down on repeat chat questions.

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

## Source 14: Full Cohort 15 Chat History — 3 chats analyzed (June 2025 – July 2026)
*Analyzed in full across the main Cohort 15 chat (7,464 msgs), a smaller "OG Cohort 15" side chat (1,451 msgs, Nov 2025–Jul 2026), and a Spring 2026 cohort chat (2,593 msgs, Jan–Jul 2026). All names/numbers stripped — findings below are patterns only, not attributed quotes.*

**⭐ Biggest single finding — validates the whole Start Here concept:**
Multiple students reported that the "drug test no earlier than 2 weeks before classes" rule was **not clearly stated in the acceptance letter**, only clarified verbally at orientation — by which point several students had already tested too early and had to retake (and repay for) it. This is exactly the kind of costly, preventable confusion this site exists to fix. Strong callout candidate for Start Here.

**Uniform — real logistics not in any official doc:**
- Worn only for lab/clinical days, not regular lecture (unless lab falls same day) — confirmed repeatedly across all 3 chats, this is clearly a recurring point of confusion every semester
- Code "York2002" confirmed working (matches handbook)
- Sizing runs inconsistent — students recommend trying on before committing to sizes across a full uniform set
- Grooming checks are strict in practice: white socks checked, no insignias, pants/hem length enforced
- Whites visibly yellow by semester 3 for most people — normal wear, not a compliance issue

**Kaplan (NCLEX readiness tool):**
- Free — school has a grant covering it, don't let anyone think they need to pay
- Used every semester; graded 5–10% of course grade depending on the course
- Access comes via a school email link — if missing, contact the instructor, don't assume it doesn't apply to you
- **Accommodations timing**: extended-time students see the same countdown as everyone else, but get a "Continue" option instead of forced "Submit" once the standard time expires — the extra time only becomes visible after the original allotted time ends (per cohort experience, worth confirming officially)
- Retakes are faculty-proctored
- "Decision tree" video modules just need to be watched and marked complete, not tested
- Login issues are a recurring complaint — worth a "if Kaplan won't let you log in" troubleshooting note

**Prep U (adaptive quiz system, part of the CoursePoint platform):**
- Access path: CoursePoint → select your course (e.g., Med Surg) → sidebar → "Prep U" → select chapter
- Required mastery level varies by course/instructor (e.g., Level 4 required in one course) — not a fixed program-wide number, so don't publish one without confirming per-course
- Assigned chapter ranges sometimes go beyond what's technically listed in the syllabus — instructor-driven, changes often

**DocuCare (EHR simulation, ~$170):**
- Comes in duration options (6/12/24 months) — real confusion about which to buy. Given it's used across multiple semesters/courses, buying short-duration options risks it expiring mid-program.
- Instructor-specific access codes — must get the correct one for your specific lab section, not just any code circulating

**ShadowHealth (virtual patient simulation):**
- Requires a 16-digit course pin (course + instructor-specific)
- Has a free trial option, but some students buy directly — those who do sometimes can't find the same assignments (e.g., "Tina Jones" case, HEENT) that trial users see automatically
- Grade weight unclear to students — worth confirming and publishing

**vSim — a tool not previously documented anywhere:**
Virtual clinical simulation, used specifically as a **clinical makeup/replacement** option when a student misses a clinical day. A "Student vSim Clinical Replacement Packet" document was circulated (23 pages) — worth requesting a copy for the Forms Library, since missed clinical is otherwise framed in the handbook as strictly not permitted.

**FIT Testing (N95 respirator fit test) — genuinely underdocumented:**
- **Separate service and separate cost from BLS/CPR** (~$60 extra) — easy to assume it's bundled, it's not
- Must be **clean-shaven** for men, or you'll be turned away and have to reschedule
- Masks not always provided — bring your own N95 or buy on-site
- Some students got it bundled same-day with BLS at outside providers (e.g., via Groupon) — worth listing as a tip

**Flu shot — timing tip + recurring headache:**
- Must be the **current flu season's** shot specifically — an old one gets rejected
- Best window per cohort experience: **last week of July through first week of August** — pharmacies often don't stock the new season's shot before that, creating a squeeze against CastleBranch deadlines
- Insurance coverage varies by pharmacy — some students had to shop around

**Titers — a recurring point of confusion:**
- Titer = bloodwork showing immunity, used as an alternative to redoing a vaccine series
- Real confusion over exactly which combination of shots + titer results CastleBranch will accept (e.g., 2 shots + positive titer sometimes accepted in place of a 3rd Hep B dose) — worth a plain-language explainer since this trips people up repeatedly

**Physical Exam form — a specific gotcha:**
Some outside medical providers won't run a TB test without a physician's order — the CastleBranch physical exam form itself specifies the TB test requirement, so students are advised to **bring the actual form with them** to the appointment rather than just describing the requirement verbally.

**A form not in the original Forms Library list — "HRSS form":**
Mentioned as arriving via a clinical-placement email from faculty, to be filled out and sent to **Janet Tyson (College Administrative Assistant)**. Likely related to health/clinical readiness sign-off — worth getting the actual document and confirming what HRSS stands for.

**Nursing Club officer candidacy — another real form:**
"Nursing Club Officer Form" — requires signatures from **3 faculty members** who have personally taught the candidate, submitted to the current officer holding that position before elections. Add to Forms Library.

**Clinical site placement communication:**
Placement info comes via email from **Janet Tyson (College Administrative Assistant)** — matches the staff directory from the handbook. Placement corrections/updates also come through her. Good to name explicitly on the site as "who to contact about clinical placement."

**Appeals — an emotional/support pattern worth noting, not just a process one:**
Beyond the formal APR process documented in the handbook, there's a real pattern of students banding together informally after failing a course (commonly Pharm or Med-Surg) to share appeal experiences and support each other. Worth considering whether the Policy Hub's Appeals page could point toward peer support (e.g., Nursing Club) in addition to the formal process — timing note from cohort experience: appeals are pursued right up through the first day of the next semester.

**CircleIn — clarified:**
Not an academic study tool in practice — the Nursing Club uses it specifically to keep a membership roster/directory, not for coursework. Worth correcting the assumption in the Tools & Platforms glossary.

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
- Per-clinical-site details beyond address/phone (parking, dress code, tips) — still mostly open, though "VA hospital" and "Forest Hills" were mentioned in passing in Source 14 without detail
- Additional forms beyond the physical exam form: absence letters, transfer requests, grade appeal, INC petition, Nursing Club Officer Form (new, found in Source 14 — needs the actual PDF)
- FAQ: now has a strong real foundation from Source 14 (see Tools & Platforms glossary + FAQ list above) — still worth supplementing with the user's own top questions, but no longer starting from zero

---

## BUILD LOG (added post-launch — status as actually implemented on the live site)

As of this update, the site is live at **https://york-nursing-club.github.io/york-nursing-site/**
(GitHub org: `york-nursing-club`, repo: `york-nursing-site`). Everything below reflects what's
actually been built, not just planned:

- ✅ Tier 1 fully built: Policy Hub (real handbook text, not placeholders), Forms Library, Start Here
- ✅ Most of Tier 2 built: Admission Criteria, Clinical Site Directory (9 confirmed sites incl.
  Kings County), Faculty & Nursing Club Directory
- ✅ Academic Calendar (Tier 3) built with key dates
- ✅ Study Guides page — organized by nursing/clinical semester 1–5 (Generic BS track), shell
  ready for content, none contributed yet
- ✅ Externships page (not in original plan) — 13 systems linked: NYC H+H, Jamaica Hospital,
  Flushing Hospital, VA-STEP, Northwell, NYP, Mount Sinai, NYU Langone, MSK, HSS, Maimonides,
  Catholic Health (LI), Montefiore
- ✅ Tools & Platforms Glossary (this update) — Prep U, Kaplan, DocuCare, ShadowHealth, vSim,
  CircleIn, Brightspace
- ✅ FAQ page (this update) — 7 real questions from Source 14
- ✅ Forms Library updated with vSim packet, HRSS form, Nursing Club Officer Form rows
- ✅ Start Here updated with drug-test callout, FIT test/flu shot/titer/physical-exam gotchas,
  Janet Tyson as clinical placement contact
- ✅ Policy Hub updated with real uniform logistics and appeals peer-support note
- ✅ Site reskinned to York cardinal red/white/gold, branded with the actual Club patch, shield
  logo/favicon, and campus photos
- ⬜ Not yet built: Course Plan/Semester Sequence page (Tier 2, item 5), Announcements/News Feed,
  Prospective Student Landing Page, Accreditation blurb
- ⬜ Still need actual files for: absence appeal letter, transfer request, grade appeal letter,
  INC petition, vSim Clinical Replacement Packet, HRSS form, Nursing Club Officer Form
- ⬜ Clinical Site Directory still needs crowdsourced per-site tips (parking, dress code, transit)
