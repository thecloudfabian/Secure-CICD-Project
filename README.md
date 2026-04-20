# CI/CD Pipeline Project (Github Actions)

## Overview
This project demonstartes a simple CI/CD pipeline using Github Actions and Github Pages to automate testing and deployment of a static website

## What it does
- Automatically runs checks on every push
- Validates project structure
- Deploys website using GitHub Pages

## Services
- GitHub
- GitHub Actions
- HTML
- GitHub Pages

## CI Pipeline
On every push to 'main':
1. Checkout code
2. Validate required files exist
3. Run basic HTML check

## Deployment
Automatically deployed via GitHub Pages from the `main` branch.

## Live Site
https://thecloudfabian.github.io/Secure-CICD-Project/

## Notes
Dockerfile exists in this repository but is not part of the deployment pipeline (experimental setup).

## Purpose
Built to demonstrate CI/CD fundamentals, automation, and deployment workflows.
