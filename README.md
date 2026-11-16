# MCSTM Smart Library Management

This ZIP contains the existing Smart Library Management demo with only the requested login/logout updates and the supplied original college logo.

## Files
- `index.html` — complete library application
- `mcstm-logo.png` — supplied MCSTM logo, unchanged

## Run locally
Keep `index.html` and `mcstm-logo.png` in the same folder, then open `index.html` in a modern browser. For GitHub Pages, upload both files to the repository root.

## Notes
- Existing library modules and browser-stored demo data structure are retained.
- Login screen has no visible demo-credentials panel and includes a password visibility eye control.
- Logout clears the active browser session and login fields. The app revalidates the session when browser history restores a cached page.
- Browser password-manager suggestions are controlled by the browser and may still appear depending on its settings.
- This is a browser-storage demo, not a production authentication system. Do not use real or sensitive credentials/data.
