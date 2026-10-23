# ThinkRoot — Maths Diagnostic MVP

A static, beginner-friendly MVP for the ThinkRoot learning diagnostic idea. It runs in the browser and requires no API key, backend, or build step.

## Features
- Five algebra diagnostic questions covering common error patterns
- Rule-based preliminary misconception signal
- Targeted practice question with immediate feedback
- Local progress history using browser localStorage
- Responsive layout for desktop and mobile
- No external libraries or API secrets

## Run locally
Open `index.html` in a modern browser.

## Deploy to a public URL using GitHub Pages
1. Sign in to GitHub and create a new **public** repository named `thinkroot`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then Save.
6. Wait for GitHub Pages to publish. The URL will usually be `https://YOUR-USERNAME.github.io/thinkroot/`.

## Important limitations
- This is a prototype, not a validated educational diagnostic model.
- It uses transparent, hand-authored rules and a small question set, not a trained classifier or live LLM.
- It does not have user accounts or cloud-synced data. Progress is stored in the current browser only.
- The system reports a *possible learning focus*, not a definitive diagnosis.
- Before public use with real students, add privacy controls, broader validated question banks, testing, and an optional secured backend/AI API.

## Suggested team split
- AI/backend lead: expand the misconception rules and create labelled test cases.
- Frontend/deployment lead: UI, GitHub Pages deployment, browser/device testing.
- Research/documentation lead: verify questions, label examples, measure accuracy and maintain documentation.
