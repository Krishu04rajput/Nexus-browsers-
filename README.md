# NEXUS Browser

A futuristic browser-style dashboard prototype built with plain HTML, CSS, and JavaScript.

## Publish using GitHub Pages (no VS Code required)

1. Create a repository named `NEXUS-Browser` on GitHub.
2. Add `index.html` to the repository root and paste the full code from the included file.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/(root)**, then Save.
6. Wait for the published site link to appear in Settings → Pages.

## Features
- Google, DuckDuckGo, and Bing search redirection
- Browser-style internal tabs (dashboard tabs, not separate browser-engine tabs)
- Local bookmarks, history, shortcuts, and tasks
- Theme, glow, background, and motion settings
- Live clock and Open-Meteo weather lookup
- Responsive layout and animated decorative graphs

## Important limitations
This is a static web dashboard, not a standalone browser engine. External sites open in a new tab because many websites block iframe embedding. System graphs are illustrative, not real hardware telemetry. Data is stored in the current browser's local storage and does not sync across devices.
