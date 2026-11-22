# Vijay Kumar A G — Personal Portfolio

A responsive, minimal portfolio for data analytics, data science and AI/ML roles. Built with HTML, CSS and vanilla JavaScript. No build step or dependencies.

## Preview locally

Open `index.html` in your browser. For a local development server (optional), run from this directory:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Personalize before publishing

1. In `index.html`, replace `[ADD YOUR PROFESSIONAL EMAIL]` with your email. To make it clickable, use `<a href="mailto:you@example.com">you@example.com</a>`.
2. Add your current resume as `resume/Vijay_Kumar_AG_Resume.pdf`, then replace `href="resume/README.txt"` with `href="resume/Vijay_Kumar_AG_Resume.pdf"`.
3. Verify education, project descriptions, skills, and internship claims; add internship organization names, dates, certificates and individual project links only after checking your records.
4. The featured project links to https://self-validating-eda-agent.streamlit.app/ (Streamlit apps may sleep when inactive). Confirm it is publicly accessible.
5. Optionally add your own portrait or project screenshots, and update Open Graph metadata.

## Publish to GitHub Pages (new repository)

1. Sign in to GitHub and create a **public** repository named `portfolio` (do not initialize it with a README if following the commands below).
2. Extract this ZIP and open a terminal inside the `vijay-portfolio` folder.
3. Run:

```bash
git init
git branch -M main
git status
git add index.html styles.css script.js README.md assets/favicon.svg resume/README.txt
git diff --cached --stat
git commit -m "Build responsive data science portfolio website"
git remote add origin https://github.com/arkatvijay0/portfolio.git
git push -u origin main
```

4. In GitHub, go to **Settings → Pages → Build and deployment**. Choose **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
5. Your website should appear at `https://arkatvijay0.github.io/portfolio/` after GitHub finishes deploying. This is the expected address, not a live verified site yet.

### Subsequent updates

```bash
git status
git diff
git add index.html styles.css script.js README.md
# If adding your resume, also stage the PDF explicitly:
# git add resume/Vijay_Kumar_AG_Resume.pdf
git diff --cached
git commit -m "Update portfolio projects and contact information"
git push origin main
```

**Before staging:** inspect all files for secrets, API keys, passwords, private datasets, virtual environments, and sensitive personal information. Do not publish these to a public GitHub repository.

## File structure

```text
vijay-portfolio/
├── index.html
├── styles.css
├── script.js
├── assets/
│   └── favicon.svg
├── resume/
│   └── README.txt
└── README.md
```

## Notes

- Uses relative URLs so it works on GitHub Pages project sites.
- Navigation is keyboard accessible and mobile friendly.
- The website does not submit forms or collect personal data.
- Portfolio project descriptions summarize previously discussed work; review them before publishing.

## Featured research project

The Self-Validating EDA Agent is presented with its architecture, core validation features, supported datasets, and direct **Launch web application** link. The repository is https://github.com/arkatvijay0/Self_Validating_Data_Agent. Avoid adding unverified benchmark metrics.

The uploaded resume is **not** bundled automatically because it contains personal contact details. Review the PDF and add it to `resume/` only if you want it publicly downloadable.
