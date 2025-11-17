# Deploy & Pin — Quick Steps

## 1) Add files
- index.html
- styles.css
- assets/ (avatar.jpg, netflix.png, crime.png, bankruptcy.png, vitacare.png, quote.svg, favicon.png, badge-*.svg, Phemelo_Sebopelo_CV.pdf)

## 2) Commit & push to GitHub
Create a new public repository (e.g., `phemelo-portfolio`) and push these files.

## 3) Deploy options (choose one)

### GitHub Pages (quick)
- Repo → Settings → Pages → Build and deployment: Deploy from a branch
- Source: Branch: `main`, Folder: `/ (root)`, Save
- Site URL will be `https://<username>.github.io/<repo>/`

### Netlify (recommended for nicer domain)
- Sign in to Netlify → New site from Git → connect GitHub → choose repo
- Deploy (default settings for static site)
- Netlify gives you `https://your-site.netlify.app` (change name in site settings)

## 4) Pin the repo
- Go to your GitHub profile → Customize your pins → select the portfolio repo

## 5) Replace placeholders
- Edit `index.html` to point project links to your real repos and demo pages.
- Replace images in /assets with your screenshots. Use 1200×700 export for good quality.

## 6) Embed Tableau (optional)
- Publish to Tableau Public and copy the embed iframe. Replace the project image area with the iframe.

## 7) (Optional) Automatic daily heartbeat (for contributions)
- If you want a daily commit to count for your GitHub contributions, add a workflow that commits a heartbeat file using a PAT. See instructions in chat or request "generate workflow".
