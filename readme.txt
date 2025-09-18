Link Detox — Static Demo

A simple phishing detection demo that runs entirely on the client-side, designed for hosting on GitHub Pages.

Features
- Check a URL — assigns a random risk score (0–100%) for demo purposes.
- Preview Website — embeds the target site in an iframe (note: some sites block embedding).
- Report Phishing — users can submit suspicious URLs (saved in their browser’s localStorage).
- Reported URLs — view the locally stored phishing reports.

Live Demo
Once deployed to GitHub Pages, the app will be available at:
https://YOUR_USERNAME.github.io/REPO_NAME/

Installation & Usage
1. Clone or download this repository.
2. Open index.html directly in your browser, or serve locally with:
   python -m http.server 8000
   Then visit http://localhost:8000.

Deploying to GitHub Pages
1. Push this project to a new GitHub repository.
2. On GitHub, go to Settings → Pages.
3. Under Source, select Branch: main and Folder: /(root).
4. Save and wait 1–2 minutes for the site to go live.

Notes
- This demo uses random risk scores. It does not perform real phishing detection.
- Reports are saved in localStorage only (not shared across users).
- Some websites may not load in the preview iframe due to security headers.

License
MIT License — free to use and modify.
