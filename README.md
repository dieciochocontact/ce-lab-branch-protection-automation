# Lab M5.04 - Branch Protection & PR Automation

**Cloud Engineering Bootcamp - Week 5, Day 2**  
**Module:** Cloud Automation & CI/CD

## Start Here: Fork, Clone, and Submit

You will complete this lab by working in **your own fork** of the lab repository and submitting a **Pull Request (PR)**.

1. **Fork the lab repository** to your GitHub account.
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/<your-github-username>/ce-lab-branch-protection-automation.git
   cd ce-lab-branch-protection-automation
   ```
3. **Follow all instructions below** and save your work in this repo (files, screenshots, and notes).
4. **When finished, submit your work:**
   - `git add` → `git commit` → `git push`
   - Open a **Pull Request** from your fork back to the original lab repo
   - Copy the **PR URL** and paste it into the **Lab Submission** field in the Student Portal

## 📋 Lab Overview

Configure branch protection rules and automated PR workflows to enforce code quality, security, and review standards before merging changes.

## 🎯 Learning Objectives

- Configure branch protection rules
- Implement automated PR checks
- Set up CODEOWNERS for review automation
- Configure status checks and merge requirements
- Implement automated PR labeling and assignment

## 📁 Repository Structure

```
ce-lab-branch-protection-automation/
├── .github/
│   ├── workflows/
│   │   ├── pr-checks.yml
│   │   ├── pr-labeler.yml
│   │   └── auto-assign.yml
│   ├── CODEOWNERS
│   └── pull_request_template.md
├── src/
├── README.md
└── .gitignore
```

## ✅ Submission Requirements

1. **Branch Protection Configuration**
   - Configured protection rules for main branch
   - Required status checks
   - Review requirements

2. **PR Automation Workflows**
   - Automated PR checks
   - Labeling automation
   - Auto-assignment

3. **CODEOWNERS File**
   - Team-based code ownership
   - Automated reviewer assignment

4. **Documentation**
   - Branch protection strategy
   - PR workflow documentation

## 🎓 Grading Rubric

| Criteria | Points |
|----------|--------|
| **Branch Protection** | 30 |
| **PR Automation** | 30 |
| **CODEOWNERS Setup** | 25 |
| **Documentation** | 15 |
| **Total** | 100 |

## 💡 Tips

- Test branch protection with a test branch
- Use GitHub's branch protection UI for initial setup
- Implement incremental checks (linting, testing, security)
- Document the review process clearly

## 📚 Resources

- [Branch Protection Rules](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches)
- [CODEOWNERS](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)

## 🚀 Submission

**Reminder:** After pushing your work and opening a PR:
- Copy the **PR URL**
- Paste it into the **Lab Submission** field in the Student Portal
