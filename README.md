# TechCrunch Disrupt 2026 trip kits

Three static sites, one folder each. Each is its own Netlify site.

| Folder | Netlify site |
|---|---|
| shella-sf-trip-kit | shella-sf-trip-kit.netlify.app |
| martha-sf-trip-kit | martha-sf-trip-kit.netlify.app |
| keyona-trip-desk | keyona-trip-desk.netlify.app |

Each site: Base directory = its folder. No build command. Publish directory = its folder.
A push that changes only one folder deploys only that site.

Each page talks to its own Google Apps Script. The address is the `EXEC` line near the top of the script block in `index.html`.
