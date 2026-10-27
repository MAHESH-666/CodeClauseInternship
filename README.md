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
- **Assets:** `script.js`, `style.css`, and a news image
- **Run:** open `NewsPortal/index.html` in a browser after configuring the API integration.

**API-key warning:** Any key placed in browser JavaScript is visible to visitors. Do not commit private API keys. Use a server-side endpoint or provider-approved public/demo key, and rotate a key if it has already been exposed.

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
