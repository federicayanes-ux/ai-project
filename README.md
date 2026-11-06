# AI, in the margins

A short, personal explainer about artificial intelligence, built for the assignment's public GitHub Pages website. The page covers how AI works, useful applications, reliability, bias, privacy, voice cloning, service outages, electricity demand and possible futures.

## Open it

Open `index.html` in your browser. Everything is static, with relative paths and no installation or build step. The page makes no AI requests and collects no personal data. Fonts are supplied by the visitor's device.

## Publish on GitHub Pages

1. Sign in to GitHub and create a **public** repository named `ai-project`.
2. Add this folder's contents directly to the repository root. `index.html` must be at the top level, not inside another `ai-project` folder. Include `assets/` and `.nojekyll`.
3. Commit the files to `main`.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**, then **main** and **/ (root)**. Save.
6. Wait for the deployment to finish, then open the GitHub Pages link shown there. Check the page on your phone as well.
7. Submit the working website link and the public repository link. Copy the real links from GitHub; replace any example usernames you see in the assignment.

## Understand the choices

- **index.html:** semantic headings, navigation, three main chapters, source footnotes and a process note. The first-person passages are opinions and possible uses, with no invented autobiographical stories. Review these passages and adjust them so they reflect your own views before submitting.
- **styles.css:** warm paper, blue ink, Georgia serif type, ruled sections and a wide margin. The layout becomes a single column on phones. Keyboard focus is visible. The chart distinguishes an estimate from a forecast using solid and hatched bars.
- **script.js:** three buttons choose a short, prewritten response. The `aria-pressed` attributes identify the selection; a live region announces the changed response. The main content remains available without JavaScript.
- **assets/thinking.svg:** an original vector notebook-and-pencil illustration, created for this page. `favicon.svg` is the browser icon.
- **.nojekyll:** lets GitHub Pages serve these static files directly.

## Evidence and acknowledgements

The five sources are linked beside relevant claims and listed at the bottom of the page. The IEA figures refer to **all data centres**, not AI alone. Its 2030 figure is a forecast from its **2025** report, not a measured outcome or a claim that blackouts are inevitable. The Cloudflare incident is attributed to the company's own account.

OpenAI Codex (https://openai.com/codex/) assisted with research, writing, illustration, coding and verification. The live page acknowledges that assistance. The student remains responsible for reviewing the finished submission and being able to explain its content and code.

## Files to publish

```
ai-project/
├── index.html
├── styles.css
├── script.js
├── README.md
├── .nojekyll
└── assets/
    ├── thinking.svg
    └── favicon.svg
```

No passwords, API keys, account details, external font downloads or build dependencies are included.
