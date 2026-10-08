# MAEEMNGT 2211 — Leadership in Education (Section 4-MAED-EM-H)

Class website for Module 4, 1st Semester, SY 2026–2027. One page, no build step.

Maintained by Carlo S. Villalona, LPT, PhD · carlo.villalon@perpetualdalta.edu.ph

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site: content, styles, and script |
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

All course data is in one block near the bottom of `index.html`, between
`EDIT HERE: course data` and `end of course data`. Edit it on GitHub with the pencil icon and commit.

| To change | Edit |
|---|---|
| A document link | The Drive file ID in `start`, `modules`, or `tasks` (the long code in a Drive link between `/d/` and `/view`) |
| A due date | The date in `tasks`, written `YYYY-MM-DD` |
| A session date or topic | `weeks` |
| Weekly readings | `readings` |
| The "last updated" line | `updated` |

An empty link (`""`) shows the item with a "to be posted" label. The Conference-Style Reporting guide is currently set this way.

The banner at the top and the task status labels update by themselves from the date in Manila time.
