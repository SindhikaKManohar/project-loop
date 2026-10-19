# Project LOOP — AI Customer Feedback Intelligence Platform

A polished front-end prototype for a multi-channel Voice-of-Customer analytics product. Built with HTML, CSS, and vanilla JavaScript so it can be hosted as a static site on GitHub Pages or Netlify.

## Features in this prototype
- Dashboard with feedback KPIs and sentiment trend visualization
- Sample AI insight brief and emerging issue highlights
- Feedback inbox with sentiment filtering and add-feedback interaction
- Theme and trend analysis view with suggested actions
- Voice of Customer report preview and downloadable `.txt` report
- “Ask LOOP” question-answer demo with predefined responses
- Data source configuration screens and workspace settings concept
- Responsive layout for desktop and mobile

## Run locally
Open `index.html` in a modern browser. No build tools are required.

## Publish a public project link (GitHub Pages)
1. Create or sign in to a GitHub account.
2. Create a **public** repository named `project-loop`.
3. Upload `index.html`, `styles.css`, `app.js`, and this `README.md` to the repository root.
4. In the repository, open **Settings → Pages**.
5. Under build/deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
6. Wait for GitHub Pages to publish. Your public URL will look like `https://YOUR-USERNAME.github.io/project-loop/` (replace `YOUR-USERNAME`; this is a pattern, not a live link until you publish).
7. Open that URL in an incognito/private window to confirm it loads without sign-in, then paste it into the submission portal.

## Important scope notes
This is a working UI prototype with illustrative sample data. “AI” insight cards and Ask LOOP responses use predefined demo logic, not a connected LLM. There is no production database, authentication, tenant isolation, role enforcement, or external channel integration. Do not present those capabilities as production-ready. For a full production implementation, add a secure API/backend, database, tenant-scoped authorization, real connectors, and an AI provider with proper privacy controls.

## Suggested submission description
“Project LOOP is a responsive customer-feedback intelligence dashboard prototype. It demonstrates sentiment KPIs, feedback inbox filtering, recurring theme analysis, a Voice-of-Customer report generator, and an interactive Ask LOOP experience using sample data. The prototype is designed as a foundation for a secure multi-tenant SaaS product.”
