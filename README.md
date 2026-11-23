# Microsoft AI Day @ JPMC

| File | What it is |
|---|---|
| `index.html` | The live flyer. On a laptop it shows the flyer scaled to the window; on a phone it stacks. |
| `agenda.html` | This week's agenda ("How the day runs"). Opens from the "Review the agenda for this week" oval. |
| `agenda.json` | The agenda content. Replace this file to publish a new agenda. |
| `assets/` | Logos, icons, Texas map, QR code, fonts. |

## Publish on GitHub Pages
1. Create a repository (for example `ai-day-jpmc`).
2. Upload everything in this folder (keep the `assets` folder) to the repository root.
3. Settings -> Pages -> Source "Deploy from a branch", Branch `main`, Folder `/ (root)` -> Save.
4. Live at `https://<your-username>.github.io/ai-day-jpmc/` (agenda at `.../agenda.html`).

## Edit the agenda (no coding)
1. Open `https://<your-username>.github.io/ai-day-jpmc/agenda.html?edit`
2. Click any text to change it. Each row has: style (plain, highlight, break, side-by-side cards),
   start and end time, move up or down, duplicate, add row, delete, and an optional button (text + link).
   Sections can be renamed, moved, deleted, and added.
3. Set the "Calendar date" to turn on "Add to calendar" buttons and the "Happening now" / "Up next" badges.
4. Edits auto-save as a draft in your browser only. Visitors don't see them yet.
5. Click **Download agenda.json**, then in GitHub upload it over the old `agenda.json`
   (Add file -> Upload files -> Commit changes). The live page updates within a minute or two.

Visitors (no `?edit`) see the read-only view: collapsible sections, Details buttons, booking buttons,
Add to calendar and Print.
