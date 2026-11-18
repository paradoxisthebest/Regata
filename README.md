# Regata

Regata is a lightweight, browser-based coding workspace for learners and experienced developers. It brings a multi-file editor, popular language choices, an HTML/CSS/JavaScript preview, and shareable project links together in one approachable interface.

## Run it

Open `index.html` in a modern browser, or serve this directory with any static web server. No build step or dependencies are required.

## Features

- Create and edit files in a range of popular programming languages.
- Autosave the current project in the browser's local storage.
- Run browser projects built with HTML, CSS, and JavaScript in a sandboxed preview.
- Export a project as JSON.
- Create an unlisted, view-only link that includes the project files in its URL.

## Current limitations

This is a static front-end prototype. Only HTML, CSS, and JavaScript run in the live preview; selecting another language does not provide a compiler or runtime. Projects are saved locally in the current browser. Share links encode project content in the URL fragment and are not password-protected, encrypted storage, or a hosted publishing service. Do not put secrets or sensitive information in a shared project.
