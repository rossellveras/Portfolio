# Rossell Veras — Technical Writing & Systems Portfolio

A static portfolio site showcasing technical writing samples for CIS coursework and job applications. No build tools required — plain HTML/CSS.

## What's included

```
index.html                                  Main portfolio page
styles.css                                  Site styling
writing-samples/
  AI-Generated-Content-Research-Report.pdf         Long-form research report
  AI-Generated-Content-Presentation.pdf            Companion slide presentation
  LED-Exit-Sign-Proposal.pdf                       Business proposal
  WiFi-Troubleshooting-Instructions.pdf            Technical instructions
  World-Orange-Production-Data-Visualization.pdf   Data visualization exercise
  Starbucks-Social-Media-Evaluation.pdf            Case study analysis
  Workplace-Messaging-Collaboration-Tools.pdf      Research paper
  Removing-the-ISM-Exercise.pdf                    Editing exercise
resume.pdf                                   (Add your own résumé PDF here)
```

## Before you publish

1. **Add your résumé.** Save a PDF of your current résumé as `resume.pdf` in this folder (replacing the placeholder reference in `index.html` if you name it differently).
2. **Update your email.** In `index.html`, find `mailto:youremail@example.com` in the Contact section and replace it with your real email address.
3. **Add more writing samples** as you complete them: drop the PDF into `writing-samples/`, then copy one of the `<article class="sample">` blocks in `index.html` and update the tag, title, description, and the `href` to point to your new PDF.
4. **Preview locally** by opening `index.html` directly in a browser before publishing, to confirm all links work.

## Publishing with Git and GitHub Pages

These steps assume you have a free [GitHub](https://github.com) account and Git installed. If you're following along with this week's LinkedIn Learning videos, this covers the same core workflow: init → add → commit → push → enable Pages.

### 1. Create a new repository on GitHub

1. Go to [github.com/new](https://github.com/new).
2. Name it something like `portfolio` (your public URL will include this name).
3. Leave it **Public** (Pages requires a public repo on free accounts).
4. Do **not** initialize with a README (you already have one) — click **Create repository**.

### 2. Push this folder to GitHub

Open a terminal in this project folder and run:

```bash
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/portfolio.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your actual GitHub username, and `portfolio` with whatever you named the repository.

### 3. Enable GitHub Pages

1. On GitHub, open your repository and go to **Settings → Pages**.
2. Under **Build and deployment → Source**, select **Deploy from a branch**.
3. Under **Branch**, select `main` and folder `/ (root)`, then click **Save**.
4. Wait 1–2 minutes. Your public URL will appear at the top of that same Pages settings page, typically:

```
https://YOUR-USERNAME.github.io/portfolio/
```

### 4. Updating the site later

Any time you add a new writing sample or edit content, push your changes again:

```bash
git add .
git commit -m "Add new writing sample"
git push
```

GitHub Pages automatically redeploys within a minute or two of each push.

## Submitting for your assignment

Once live, copy the `https://YOUR-USERNAME.github.io/portfolio/` URL from the Pages settings page and submit that as your public portfolio link.
