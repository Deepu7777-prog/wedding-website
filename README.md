# Wedding Invitation · Dr. Krishna Prasad & Dr. Jyothsna

A single-page wedding invitation. Opens with a temple gate and an "Open the Doors" button, then the invitation appears with a shower of rose petals. Every button tap sprinkles more petals.

Everything is in `index.html` (photos and the opening video are embedded), so there is nothing to build.

## Push to GitHub
1. Create an empty repo on github.com (e.g. `wedding-invitation`) — don't add a README there.
2. In this folder:
```
git init
git add .
git commit -m "Wedding invitation with temple opening"
git branch -M main
git remote add origin https://github.com/<your-username>/wedding-invitation.git
git push -u origin main
```
(Or on github.com: **Add file → Upload files** and drag in these files.)

## Deploy on Netlify
1. Go to app.netlify.com → **Add new site → Import an existing project → GitHub**.
2. Pick the repo. Leave build command empty, publish directory `.` (already set in `netlify.toml`).
3. Click **Deploy**. You get a link like `https://something.netlify.app` — change it under **Site configuration → Change site name**.

Quick option without GitHub: **Add new site → Deploy manually** and drag this folder in.
