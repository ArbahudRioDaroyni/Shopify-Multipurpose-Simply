# Git Branch Naming Standard

This document defines the branch naming conventions to ensure consistency and clarity in the repository.

---

## 📌 General Rules
- Use **lowercase** for all branch names.
- Use **dashes (-)** to separate words.
- Branch names should be **clear**, **concise**, and **descriptive**.
- Avoid special characters other than letters, numbers, and dashes.

---

## 🔧 Branch Naming Structure

### 1. `feature/`
Used when developing a new feature.

**Format:**
feature/<feature-name>

**Examples:**
feature/login-page
feature/add-payment-method
feature/export-report-csv

---

### 2. `bugfix/`
Used for fixing non-critical bugs found during development.

**Format:**
bugfix/<bug-description>

**Examples:**
bugfix/fix-null-pointer-login
bugfix/wrong-total-price

---

### 3. `hotfix/`
Used for urgent fixes to critical production issues.

**Format:**
hotfix/<issue-description>

**Examples:**
hotfix/fix-payment-crash
hotfix/urgent-login-error

---

### 4. `release/`
Used when preparing a new release version.

**Format:**
release/<version-number>

**Examples:**
release/1.2.0
release/2.0.1

---

### 5. `chore/`
Used for routine tasks that are not features or bug fixes (cleanup, refactor, updates).

**Format:**
chore/<task-name>

**Examples:**
chore/update-dependencies
chore/refactor-auth-service

---

### 6. `test/`
Used for experiments, prototypes, or testing ideas.

**Format:**
test/<experiment-name>

**Examples:**
test/new-cache-approach
test/ui-animations

---

### 7. `docs/`
Used for documentation updates.

**Format:**
docs/<description>

**Examples:**
docs/update-readme
docs/api-spec-adjustment

---

## 📌 Optional: Including Task/Jira IDs
If using a task management system such as Jira, Trello, or Asana, you may include the ticket ID.

**Format:**
feature/<TICKET-ID>-<feature-name>

**Examples:**
feature/JIRA-123-add-login-page
bugfix/TASK-88-wrong-calc

---

## ✅ Purpose of This Standard
- Ensures consistent naming across the team.
- Makes reviewing, searching, and tracking branches easier.
- Provides clear context for the work each branch represents.