# Section Planner (Template)

This is a beginner-friendly template for the **Section Planner** React app.
It loads schedule data from `public/course_offerings.csv` and helps selecting sections by time/day/faculty.

## Quick start (locally)
1. Replace `public/course_offerings.csv` with your real CSV.
2. Edit `package.json` `homepage` to `https://<your-username>.github.io/section-planner`.
3. Install and run:
   ```bash
   npm install
   npm run dev
   ```

## Deploy to GitHub Pages (beginner-friendly)
1. Create a GitHub repository named `section-planner` and push this project.
2. In `package.json` set `"homepage"` to your GitHub Pages URL:
   `https://your-username.github.io/section-planner`
3. Run locally to verify: `npm run build`
4. Deploy: `npm run deploy`
5. Visit `https://your-username.github.io/section-planner`

For a fully online setup (no terminal), use GitHub Codespaces or upload this repo as a template and follow the README steps in the browser.
