# Project Overview

A self-contained, encrypted single-page web app. The `index.html` file decrypts itself at runtime using AES-GCM and renders a SharePoint authentication interface in the browser.

No build system or dependencies required — it's a static file served directly.

## How to run

The workflow `Start application` serves the project with Python's built-in HTTP server on port 5000:

```
python3 -m http.server 5000
```

## Stack

- Pure HTML/JS (no framework, no build step)
- Single file: `index.html`

## User preferences

_None recorded yet._
