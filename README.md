# York Nursing Hub

Live site: **https://sunnysediqi.github.io/york-nursing-site/**

This is the York College Nursing Club's student resource site — forms, policies, admission
info, clinical site info, and study guides in one place. It's a plain HTML/CSS static site
(no build step, no framework) hosted for free on GitHub Pages.

This file is for whoever inherits this site next — a future Cohort Secretary, officer, or
anyone helping maintain it who wasn't around when it was built.

## The one thing to know

**Any change pushed to the `master` branch goes live automatically** within about a minute.
There's no separate "deploy" step — edit, commit, push, done.

## Adding a study guide (no coding required)

1. Get the PDF (or doc) you want to add.
2. Rename it to match the course code, e.g. `NURS210.pdf`.
3. Drop it into the `study-guides/` folder.
4. Open `study-guides.html`, find that course's card, and change:
   ```html
   <span class="status-need">No study guide yet</span> — <a href="study-guides/NURS210.pdf">add one</a>
   ```
   to something like:
   ```html
   <span class="status-have">Available</span> — <a href="study-guides/NURS210.pdf">Download</a>
   ```
5. Commit and push (see below).

## Replacing a PDF (handbook, calendars, forms)

Same idea — drop the new file into `source-docs/` (or `forms/`) using the **exact same
filename** as the old one, and every link pointing to it updates automatically. If the new
file has a different name, you'll also need to update the `href` wherever it's linked.

## Making a text edit (dates, fees, names, etc.)

Each page is a plain `.html` file in the root folder (`index.html`, `start-here.html`,
`policies.html`, etc.). Open one in any text editor:

- Find the text you want to change and edit it directly — leave anything inside `<angle
  brackets>` alone, that's structural markup, not content.
- Colors and fonts live in one shared file: `css/style.css`. You shouldn't need to touch
  this unless you're changing the look of the whole site.
- If you're not comfortable editing HTML, that's fine — bring the change to whoever's
  helping maintain the site (or to an AI coding assistant like Claude Code, which is how
  this site was originally built) and describe what needs to change in plain language.

## Pushing changes live

If you're comfortable with git:

```bash
git add -A
git commit -m "describe what changed"
git push
```

If you're not, ask whoever's helping you maintain the site to run this for you — it takes
seconds once the files are ready.

## Where things are

| Folder/file | What it's for |
|---|---|
| `index.html`, `start-here.html`, etc. | The actual pages |
| `css/style.css` | All site-wide styling (colors, layout) |
| `source-docs/` | Official PDFs (handbook, physical exam form, calendars) |
| `study-guides/` | Student-contributed study guide files |
| `assets/images/` | Logo, favicon, hero photos |
| `assets/images/branding/` | Original, uncropped source images — useful if you want to
  make new variations later |
| `PROJECT-HANDOFF.md` | The original planning document this site was built from — has
  background on scope decisions, what's still missing, and known issues on the official
  York site |

## Known gaps (as of this writing)

- Several forms aren't uploaded yet (absence appeal letter, transfer request, grade appeal,
  INC petition) — see `forms.html`.
- Tier 3 content not yet built: Course Plan page, FAQ, Announcements, Prospective Student
  landing page, Accreditation blurb.
- Clinical Site Directory is missing crowdsourced details (parking, dress code, transit tips)
  — see `clinical-sites.html`.
- Academic Calendar key dates need to be re-checked and updated every semester.

## Reminder for every page

This is a **Nursing Club resource, not an official York College or CUNY publication**. Keep
that framing in any new content, and link back to the official source for anything
deadline-, fee-, or policy-related.
