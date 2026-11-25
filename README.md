# Closing the Loop – Hostel Maintenance Complaint Tracker

A static website (one `index.html`, no build step, no dependencies).

## Files
- `index.html`  the whole website (HTML, CSS and JavaScript)
- `vercel.json` Vercel settings (clean URLs and basic security headers)

## Run locally
Double-click `index.html`, or run `npx serve .` in this folder.

## Deploy to Vercel: Option A (Vercel CLI, fastest)
1. Install Node.js from https://nodejs.org
2. In this folder, run: `npm i -g vercel`
3. Run: `vercel login` and sign in
4. Run: `vercel --prod`
   Answer the prompts: set up and deploy? Yes. Link to existing project? No.
   Framework preset: Other. Output directory: `.` (just press Enter).
5. Vercel prints your public link, like `https://closing-the-loop.vercel.app`

## Deploy to Vercel: Option B (GitHub)
1. Create a new GitHub repository and upload these files.
2. Go to https://vercel.com/new and import that repository.
3. Framework Preset: Other. Leave build command and output directory empty.
4. Click Deploy. Your public link appears when it finishes.

## Note
This is a front-end prototype. Complaints are kept in memory and reset when the page is refreshed.
