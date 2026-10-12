# Conference lessons

Summaries of conferences and talks: the top lessons, each with an action to take today.

Live: https://dusan-kolenovic.github.io/conference-summaries/

## Layout

- `index.html` — the list of all summaries, newest first.
- `YYYY-MM-DD-slug/index.html` — one summary per folder.
- `support.js` and `_ds/` — the Claude Design runtime and the Hours design system, shared by every page.
- `.nojekyll` — required, or GitHub Pages skips the `_ds/` folder and pages load unstyled.

## Adding a new summary

1. Export the `.dc.html` file from the Claude Design project.
2. Save it as `YYYY-MM-DD-slug/index.html`.
3. In that file, change `./support.js` to `../support.js` and every `_ds/` path to `../_ds/`. Add a `<title>`.
4. Add one `<li>` for it at the top of the list in the root `index.html`.
5. Commit and push. Pages updates in about a minute.

## Sources

| Summary | Claude Design project | File |
|---|---|---|
| 2026-09-22 State of AI SDLC | `5137f5f7-d046-446d-bd90-69d64450cac3` | `Conference Lessons.dc.html` |
