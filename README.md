# Secure Git Fundamentals for Security Engineers

This repo is your complete guide to mastering Git and GitHub workflows — not just as a developer, but as a security engineer who needs to understand version control from a *defensive*, *forensic*, and *collaborative* lens.

## 🔐 Why Git Matters in Security

- Track code-level incidents and patches
- Detect injected or unauthorized commits
- Respond to credential leaks or repo breaches
- Lock down CI/CD pipelines
- Use Git logs as evidence trails in investigations

## 📚 Modules

### 1. Git Basics
Covers `init`, `clone`, `add`, `commit`, `merge`, `push`, and `pull`.

### 2. Secure Git Practices
- Signing commits with GPG
- Removing secrets from commit history
- Using Git hooks to prevent unsafe commits
- `.gitignore` best practices

### 3. GitHub Collaboration Security
- Enforcing branch protections and PR reviews
- Hardening GitHub Actions
- Monitoring repos with secret scanning tools
- Creating a secure disclosure workflow

### 4. VS Code Git Workflow
- Setting up Git in VS Code
- Using extensions like GitLens
- Handling `.env` files securely in repos

### 5. Git Forensics & Auditing
- Using `git log`, `blame`, and `bisect` in incident response
- Tracing who added a vulnerable line and when
- Responding to a malicious code push

### 6. Security Case Studies
- Real-world styled walkthroughs:
  - A leaked AWS key in commit history
  - A rogue pull request with malicious code
  - A critical patch cycle tracked in Git logs

## 🧰 Tools Used
- `gitleaks`
- `truffleHog`
- `git-secrets`
- GitHub Advanced Security (if enterprise)
- VS Code + GitLens

## 🚨 Ideal For:
- Aspiring or current Security Engineers
- DevSecOps learners
- SOC/IR analysts wanting to use Git as an audit tool
