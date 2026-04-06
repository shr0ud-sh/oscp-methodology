# OSCP Exam Methodology 2026

A static reference site generated from a CherryTree `.ctb` notes file.

## Features
- Full sidebar navigation with search
- Syntax-highlighted command blocks with copy buttons
- Scroll progress bar + active section tracking
- Mobile responsive

## Hosting on GitHub Pages

1. Create a new **private** GitHub repository (e.g. `oscp-methodology`)
2. Push this folder to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial OSCP methodology site"
   git remote add origin https://github.com/YOUR_USERNAME/oscp-methodology.git
   git push -u origin main
   ```
3. Go to **Settings → Pages → Source** and select **GitHub Actions**
4. The workflow will auto-deploy — your site will be live at:
   `https://YOUR_USERNAME.github.io/oscp-methodology/`

> **Tip:** Keep the repo private so only you can see the source, but the Pages URL will still be accessible to you via browser.
