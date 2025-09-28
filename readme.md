# 🚀 Deploying Your AI Portfolio with MkDocs

**Last Updated:** 2025

---

## 📁 Step 1: Get Started with the Portfolio Template

1. Download the MkDocs AI portfolio template:
   - [Download Template ZIP](./ai_portfolio_mkdocs.zip)

2. Extract the archive and navigate to the folder:
   ```
   cd ai_portfolio_mkdocs
   ```

---

## 🛠 Step 2: Install MkDocs & Material Theme

Install MkDocs and the Material theme (do this once):

```
pip install mkdocs mkdocs-material
```

---

## 🧪 Step 3: Preview Your Portfolio Locally

Launch the development server:

```
mkdocs serve --dev-addr 127.0.0.1:8000
```

Open this URL in your browser:
```
http://127.0.0.1:8501
```

---

## 📤 Step 4: Upload Your Code to GitHub

1. Create a new repository on GitHub (e.g., `ai-portfolio`)
   - Go to https://github.com/new
   - Name your repo (e.g., ai-portfolio)
   - Set it to public, and skip the README (add it later if you wish)
2. In your terminal, run the following commands:

```bash
git init # Initialize your local repository
git remote add origin https://github.com/your-username/ai-portfolio.git # Use your repo's URL
git add . # Stage all files
git commit -m "Initial commit" # Commit your work
git branch -M main # Set the main branch
git push -u origin main # Upload your code to GitHub
```

---

## 🌍 Step 5: Publish to GitHub Pages

Deploy your site with:

```bash
mkdocs gh-deploy # Deploys your site to GitHub Pages
```

- This will build your website,
- Push it to the `gh-pages` branch,
- And GitHub Pages will host it for you.

---

## 🔗 Step 6: View Your Portfolio Online

Visit:

```bash
https://your-username.github.io/ai-portfolio/ # Replace with your GitHub username
```

✅ Your portfolio should now be live!

---

## 💡 Additional Tips

- Edit `mkdocs.yml` to customize the site name, theme, or colors.
- Place your resume in the `/docs/` directory and link it in `resume.md`.
- Share your portfolio link on LinkedIn, GitHub, or other platforms.
- Explore more customization options in the documentation:
  - [MkDocs Documentation](https://www.mkdocs.org/user-guide/writing-your-docs/)
  - [Material for MkDocs Documentation](https://squidfunk.github.io/mkdocs-material/getting-started/)

---
