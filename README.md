# CI/CD Workflow with Branching Strategy - PoC

## Branching Strategy
- main → production
- feature/* → development

## CI
- Triggered on feature branch
- Build & test automated using GitHub Actions

## CD
- Triggered on merge to main
- Automated deployment

## Tech Stack
- Node.js
- Express
- GitHub Actions
