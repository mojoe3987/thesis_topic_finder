# AGENTS.md

## Cursor Cloud specific instructions

### Overview

**Thesis Topic Finder** is a single-file static web application (`thesis-topic-finder.html`) built with React 18, Tailwind CSS, and Babel Standalone — all loaded via CDN. There is no build system, no package manager, no `package.json`, and no server-side code.

### Running the app

Serve the file with any static HTTP server:

```sh
python3 -m http.server 8080
```

Then open `http://localhost:8080/thesis-topic-finder.html` in a browser.

### API key requirement

The app calls the OpenRouter API (`https://openrouter.ai/api/v1/chat/completions`) for all AI features. The placeholder `API_KEY_HERE` in the HTML must be replaced with a valid OpenRouter API key (appears 4 times in the file). Without it, the UI loads and is interactive but AI responses will fail. The key should be provided via the `OPENROUTER_API_KEY` secret.

### Lint / Test / Build

- **No linter, test framework, or build step exists** in this repository.
- Validation is manual: open the HTML in a browser and interact with the 5-stage workflow.
- The app requires an internet connection for CDN dependencies (React, Tailwind, Babel) and the OpenRouter API.
