# Study Planner

A simple study planner with a clean UI, profiles, up to 6 subjects, drag-and-drop days, dark mode and phone support. No sign-up, and your data stays in your browser.

**Live:** https://mSB3L.github.io/subject-planner/

## Features

- **Profiles:** keep separate plans (Backlogs, Practice…). Rename, duplicate or delete them.
- **1–6 subjects per profile:** set the names and colors yourself.
- **Drag and drop:** move a chapter within its subject, or move a whole day's plan. Others slide over smoothly.
- **Schedule tools:** shift all dates by ±1 day (or N days), skip any weekdays (e.g. Sundays), skip a specific day and push everything forward, or close date gaps.
- **Export** as an image (PNG) or PDF.
- **Dark mode** (follows your system until you choose) and a layout that adapts to phones.

## Your data and backups

Everything is saved automatically **in your own browser**. Nothing is sent to a server, and there are no accounts.

To avoid losing your plans:

- Use **Backups → Download backup** now and then. The `.json` file contains all your profiles, and you can import it again on any device.
- **Save HTML** downloads a copy of the page with your plans stored inside it.
- The app keeps two copies in the browser plus automatic restore points (**Backups**), which also bring back deleted profiles.
- Clearing site data wipes browser storage. Safari can also remove data from sites you haven't visited for about a week. A downloaded backup protects you in both cases.

Your data belongs to the exact link you use. If the address changes, the new address starts empty, so restore from a backup there.

## Run it yourself

It is a single `index.html` file with no dependencies and no build step.

- **Locally:** download `index.html` and open it in a browser.
- **GitHub Pages:** put `index.html` in a public repository, then go to *Settings → Pages* and deploy from the `main` branch, root folder.

## Browser support

Built for current versions of Chrome, Edge, Firefox and Safari (desktop and mobile). It has been tested most in Chromium-based browsers, so please report problems in other browsers.

## Contributing

Issues and pull requests are welcome. The whole app is one HTML file (styles and scripts included), so changes are easy to review.

## License

[MIT](LICENSE): free to use, copy, modify and share.
