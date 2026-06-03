# DevOps-Beginner-Roadmap4

# GitHub Pages Deployment Workflow

This project demonstrates how to use GitHub Actions to automatically deploy a static website to GitHub Pages whenever changes are made to the `index.html` file.

## Features

- Automatic deployment using GitHub Actions
- Deploys only when `index.html` changes
- Uses GitHub Pages for hosting
- CI/CD workflow implementation

## Project Structure

```bash
.github/workflows/deploy.yml
index.html
README.md
```

## How It Works

1. A push is made to the `main` branch
2. GitHub Actions checks whether `index.html` changed
3. If changed, the workflow runs automatically
4. The website is deployed to GitHub Pages

## Technologies Used

- GitHub Actions
- GitHub Pages
- HTML
- YAML

## Live Website

https://github.com/owolabigrace/DevOps-Beginner-Roadmap4

## Learning Outcomes

This project helped me understand:

- Continuous Integration (CI)
- Continuous Deployment (CD)
- GitHub Actions workflows
- GitHub Pages hosting
- Workflow automation

# Project URL 
https://roadmap.sh/projects/github-actions-deployment-workflow