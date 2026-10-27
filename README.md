# CodeClause Web Development Internship Projects

A collection of small web-development exercises from an internship/training period. The repository contains three separate projects.

## Projects

### 1. Chat Application
A Node.js chat application using Express and Socket.IO for real-time communication.

- **Stack:** Node.js, Express, Socket.IO
- **Entry point:** `Chat-Application/app.js`
- **Run:** install the package dependencies from `Chat-Application/package.json`, then run `npm start` from that folder.

### 2. News Portal
A front-end news page with HTML, CSS, JavaScript, and a client-side news API integration.

- **Entry point:** `NewsPortal/index.html`
- **Assets:** `script.js`, `style.css`, `api-key.example.js`, and a news image
- **Local configuration:** copy `api-key.example.js` to `api-key.js` in the same folder and set your own NewsAPI key locally. The local `api-key.js` file is ignored by Git.
- **Run:** open `NewsPortal/index.html` in a browser after configuring the API integration.

**API-key warning:** Any key placed in browser JavaScript is visible to visitors. The previously tracked `NewsPortal/api-key.js` has been removed from the current branch and replaced with a safe example file. A real key may still exist in earlier Git commits, so revoke/rotate the exposed NewsAPI key in the provider dashboard and review the repository history. Prefer a server-side proxy over putting secret keys in browser code.

### 3. Text Editor
A browser-based text editing interface.

- **Entry point:** `Texteditor/index.html`
- **Stack:** HTML, CSS, JavaScript
- **Run:** open the HTML file in a browser.

## General requirements

- Node.js (for Chat Application)
- A modern browser (for News Portal and Text Editor)

## Repository maintenance

The Chat Application directory currently includes a `node_modules` folder. For a cleaner source repository, keep the package manifest/lock file and remove generated dependencies from version control after confirming they can be restored with `npm ci`.

These projects are educational demos rather than hardened production services. Add tests, error handling, input validation, and documentation as each project is extended.
