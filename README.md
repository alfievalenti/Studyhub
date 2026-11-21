# StudyHub — College Manager

A personal, local-first college planner built as a Progressive Web App.

## Features
- Dashboard with open assignments, deadlines, score average and upcoming events
- Assignment tracker with subjects, due dates, statuses and details
- Weekly planner with dated study sessions
- Events and important dates
- Score tracker with percentages and subject averages
- College database for topic notes, revision resources, links and practicals
- Workout centre with 80+ searchable exercises, muscle/equipment filters, sets, reps, weights, workout stopwatch, rest timer, workout history and weekly muscle map
- Editable subject list
- Automatic saving in the browser
- JSON export/import backups
- Installable PWA and basic offline caching when hosted over HTTPS

## Important data note
StudyHub stores data in the browser's localStorage on the device/browser where it is used. It does not upload data to a server and does not automatically sync between your iPhone and MacBook. Export a JSON backup regularly. Clearing browser site data can remove the saved information.

## Run locally
You can open `index.html` in a modern browser for local testing. For install/offline features, host the folder on an HTTPS static host.

## Publish as a link
One straightforward option is GitHub Pages:
1. Create a GitHub repository.
2. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to the repository root.
3. In repository Settings → Pages, select deploy from the main branch and root folder.
4. Wait for GitHub Pages to publish your site. It will provide a public HTTPS URL.
5. Open that URL on your iPhone in Safari → Share → Add to Home Screen.

Keep the repository public only if you are comfortable with the app's source code being public. Your actual planner data is not committed to the repository; it stays in your browser.

## Suggested routine
- Export a backup weekly.
- Use Settings & backup → Export all data.
- Keep the JSON backup in a private, safe location.
