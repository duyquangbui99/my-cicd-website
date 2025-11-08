# CI/CD Pipeline Report

## Student Information
- Name: Quang Bui
- Date: 2025-11-07
- Repository: https://github.com/duyquangbui99/my-cicd-website
- Live URL: https://duyquangbui99.github.io/my-cicd-website/

## Deployment History
Check the Actions tab for complete deployment history.

### Iteration Summary
1. **Initial Deployment**
   - Commit: `<d02cba1>`
   - Time to Deploy: `<1 minute>`
   - Status: `Success`

2. **Iteration 1: Project Tracking**
   - Commit: `<a4aeedc>`
   - Changes Made: Added Trello board link to README.md
   - Deployment Time: `<1 minute>`

3. **Iteration 2: Deploy Info & Personalization**
   - Commits: `<a4aeedc, 8a8a0b1>`
   - Changes Made: Replaced "Your Name", updated university + graduation year, added deploy-info.json, added CI/CD project card
   - Deployment Time: `<1 minute>`

4. **Iteration 3: Feature Branch Workflow**
   - PR Number: `<#1>`
   - Branch: `feature/add-contact`
   - Changes Made: Added contact.html; updated nav links on all pages
   - Deployment triggered by: Pull Request merge

## CI/CD Understanding

### What is CI/CD?
Continuous Integration (CI) automatically builds and tests code when changes are committed; Continuous Deployment (CD) automatically releases those changes to users after passing checks. Together, CI/CD shortens feedback loops and makes shipping safe and repeatable.

### Benefits Observed
1. Push-to-deploy workflow eliminated manual steps.
2. Clear visibility of build status/history in GitHub Actions.
3. Easy rollback by reverting a commit or PR.
4. Collaboration-friendly: PRs trigger deploys after review.

### Challenges Faced
- `<The instruction was clear, there were just some indentation issues in the YAML file, but I fixed them by following your guide in class.>`

### Real-World Application
In larger projects, CI/CD enforces code quality with automated tests, builds artifacts, and deploys to multiple environments (dev/stage/prod). Feature branches flow through pull requests for review before merging to main, which triggers production deploys. This creates consistency, reduces human error, and enables faster, safer iterations.

## Screenshots
- [ ] Initial deployment 
- [ ] GitHub Actions tab showing successful builds 
- [ ] Live website after final iteration 

---
