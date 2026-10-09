# MAEEMNGT 2211 — Leadership in Education (Section 4-MAED-EM-H)

Class website for Module 4, 1st Semester, SY 2026–2027. One page, no build step.

Maintained by Carlo S. Villalona, LPT, PhD · carlo.villalon@perpetualdalta.edu.ph

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site: content, styles, and script |
| `assets/professor.jpg` | The professor's portrait |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |
| `README.md` | This guide |

## Publish on GitHub Pages

1. Sign in at github.com and create a new **public** repository, for example `maeemngt2211`.
2. Open the repository, choose **Add file → Upload files**, drag in `index.html`, `.nojekyll`, and `README.md`, then **Commit changes**.
3. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to *Deploy from a branch*, **Branch** to `main` and folder `/ (root)`, then **Save**.
4. After a minute or two the address appears on the same page: `https://YOUR-USERNAME.github.io/maeemngt2211/`. Share that link with the class.

## Before you share the link

- **Drive sharing.** The page links to files in the Google Drive folder *MAEEMNGT 2211 Leadership in Education 4-MAED-EM-H*. Set the folder to *Anyone with the link — Viewer* (or share it with your students' accounts), otherwise students will see "Request access".
- **The page is public.** Anyone with the address can open it. It carries `noindex`, which asks search engines not to list it, but it is not private. Do not put grades, class lists, or student work on it.

## Updating the site

The page is plain HTML with no build step, laid out in the same sections as the PHDENG 2214 class site: About, Professor, Start here, Schedule, Modules, Tasks, Reporting, Profile, Field, Readings, Grading, Standards, Policies. Edit `index.html` on GitHub with the pencil icon and commit.

| To change | Look for |
|---|---|
| A document link | The Drive link in the matching section (`drive.google.com/file/d/<ID>/view`); the learner profile uses a Canva link |
| A due date | The `Due Friday, ...` labels in the Schedule and Tasks sections (each date appears in both) |
| Examination dates | The two `exam` cards at the end of the Schedule section |
| Group sizes and inquiry questions | The Reporting section (`id="conference"`) |
| Weekly readings | The Readings section (`id="readings"`) |
| The professor's photo | Replace `assets/professor.jpg` (720 x 900) |

The "This week" label on the schedule sets itself from the date in Manila time.

For deadlines, the website states that it takes precedence over the PDFs, so keep its dates current.
