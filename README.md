# Rohit Kumar — Developer Portfolio

A responsive, static HTML/CSS/JavaScript portfolio customized from the supplied resume and Masterly dark portfolio layout direction.

## Files
- `index.html` — portfolio content and sections
- `assets/style.css` — responsive dark theme
- `assets/script.js` — mobile navigation, project filters, scroll effects
- `assets/rohit-kumar-resume.pdf` — downloadable resume

## Before publishing
1. Review phone, email, location and social profile URLs in `index.html`.
2. Confirm the resume PDF is the latest version.
3. Add a professional headshot if you want one; the current hero uses a code-themed visual, so no portrait is assumed.
4. Check all project descriptions and dates for accuracy.
5. The skill bars are decorative only, not measured skill percentages.

## Test locally
Open `index.html` in a browser. For a local server, run:
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

## Deploy with GitHub Pages
### 1. Create a repository
- Sign in to GitHub.
- Click **New repository**.
- Suggested name: `rohit99336.github.io` (this gives the clean URL `https://rohit99336.github.io`).
- Choose **Public** and create the repository.

### 2. Upload using Git (Linux)
Extract this ZIP, open a terminal inside the extracted `rohit-portfolio` folder, then run:
```bash
git init
git add .
git commit -m "Add personal developer portfolio"
git branch -M main
git remote add origin https://github.com/rohit99336/rohit99336.github.io.git
git push -u origin main
```
If Git asks for authentication, use GitHub SSH (recommended) or a Personal Access Token; your GitHub account password is not accepted for Git HTTPS authentication.

If you already use SSH for GitHub, use this remote instead:
```bash
git remote set-url origin git@github.com:rohit99336/rohit99336.github.io.git
git push -u origin main
```

### 3. Enable GitHub Pages
- Open repository **Settings → Pages**.
- Under **Build and deployment**, choose **Deploy from a branch**.
- Select branch `main` and folder `/ (root)`.
- Click **Save**.
- Wait for the deployment to finish. Your site should appear at `https://rohit99336.github.io`.

### Alternative repository name
If you name the repository `portfolio`, the URL will be:
`https://rohit99336.github.io/portfolio/`
For this project, keep all asset paths relative (`assets/...`) so the site works from a repository subpath too.

## Updating the portfolio
Edit the HTML/CSS/JS, then:
```bash
git add .
git commit -m "Update portfolio"
git push
```
GitHub Pages will redeploy automatically.

## Important notes
- GitHub Pages hosts static websites. This portfolio is static and does not require PHP/Laravel hosting.
- Do not upload API keys, `.env` files, passwords or private credentials.
- A live project link is not shown for projects unless it was explicitly provided/verified; project names and descriptions are presented from the resume.
