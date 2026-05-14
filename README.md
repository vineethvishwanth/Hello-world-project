# Hello World — CI/CD with GitHub Actions

A simple Hello World webpage deployed automatically using a GitHub Actions CI/CD pipeline.

## What it does

Every time you push code to `main`, the pipeline automatically:
1. **Builds** — validates your files
2. **Deploys** — publishes to GitHub Pages

## Project structure

```
hello-world-cicd/
├── index.html                        ← The Hello World webpage
├── README.md                         ← This file
└── .github/
    └── workflows/
        └── deploy.yml                ← CI/CD pipeline
```

## Setup

1. Push this project to a **public** GitHub repo
2. Go to **Settings → Pages → Source → GitHub Actions**
3. Push any change to `main` — your site goes live at:

```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

## Live URL

Find your live URL in: **GitHub repo → Environments → github-pages**
