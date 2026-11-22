# Vijay Kumar A G — Portfolio

Minimal responsive static portfolio, ready for GitHub Pages.

## Files
- `index.html` — website content
- `styles.css` — responsive styling
- `script.js` — navigation and footer
- `assets/favicon.svg` — browser icon
- `resume/Vijay_Kumar_AG_Resume.pdf` — public resume

## Publish to an existing `portfolio` GitHub repository
1. Extract the ZIP. Open the inner `portfolio-main` folder.
2. Review the email, phone, resume and project claims. All are public when deployed.
3. In your GitHub `portfolio` repository, upload/replace `index.html`, `styles.css`, `script.js`, `README.md`, and upload the `assets` and `resume` folders (or their files preserving the paths).
4. Commit changes. Go to Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.
5. Visit `https://arkatvijay0.github.io/portfolio/` after deployment.

## Git commands (PowerShell, after cloning the repository)
```powershell
git status
git diff --check
git diff
# Review for passwords, tokens, .env files, virtual environments and private datasets.
git add index.html styles.css script.js README.md assets/favicon.svg resume/Vijay_Kumar_AG_Resume.pdf
git diff --cached --stat
git diff --cached --check
git commit -m "Update portfolio projects, experience and public contact details"
git push origin main
```

## Privacy
This portfolio intentionally displays a phone number, email and resume publicly at the owner's request. The resume may contain additional personal details. Remove any you do not want indexed by search engines before publishing.
