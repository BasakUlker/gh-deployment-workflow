# GitHub Actions Deployment Workflow

This project is a simple example of using **GitHub Actions** to deploy a static website to **GitHub Pages**.  
Any changes made to the `index.html` file in the `main` branch will automatically be deployed.

## How it works

- A GitHub Actions workflow in `.github/workflows/deploy.yml` watches for changes to `index.html`.
- When a change is detected, the site is automatically deployed to GitHub Pages.
- The site is live at: [https://BasakUlker.github.io/gh-deployment-workflow/](https://BasakUlker.github.io/gh-deployment-workflow/)

## Purpose

The purpose of this project is to understand:
- GitHub Actions
- Continuous Integration and Deployment (CI/CD)
- GitHub Pages deployment

Related to: https://roadmap.sh/projects/github-actions-deployment-workflow
