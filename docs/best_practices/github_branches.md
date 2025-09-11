# Branch Naming in GitHub

Branches in GitHub can be named flexibly, but following conventions helps keep repositories organized and understandable. Below are common branch types and naming patterns.

---

## 🔹 Default Branch
- `main` (current GitHub default)  
- `master` (older default)

---

## 🔹 Feature Branches
Used for developing new features.

Examples:
- `feature/login-page`
- `feature/shopping-cart`
- `feat/api-integration`

---

## 🔹 Bugfix Branches
Used for fixing bugs.

Examples:
- `bugfix/navbar-overlap`
- `fix/memory-leak`
- `hotfix/crash-on-start`

---

## 🔹 Release Branches
Used to prepare production releases.

Examples:
- `release/v1.0.0`
- `release/2.3`
- `release/stable`

---

## 🔹 Hotfix Branches
Used for urgent fixes directly in production.

Examples:
- `hotfix/critical-security-patch`
- `hotfix/payment-error`

---

## 🔹 Experimental / Other Branches
Used for testing or trying new ideas.

Examples:
- `experiment/new-ui`
- `spike/graphql-prototype`
- `draft/documentation-update`

---

## 🔹 Environment-Specific Branches
Sometimes tied to deployment environments.

Examples:
- `dev` (development)  
- `prod` or `production`

---

## ✅ Tips for Branch Naming
- Use `/` to organize (like folders): `feature/...`, `bugfix/...`.  
- Keep names **descriptive and short**.  
- Avoid spaces; use `-` or `/`.  
- Consider adding **ticket IDs** for traceability, e.g.:
  - `feature/JIRA-123-add-authentication`

