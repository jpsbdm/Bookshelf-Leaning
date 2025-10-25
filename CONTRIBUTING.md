First of all, thank you for your interest in contributing!  
This is a study project, and every collaboration is an opportunity to learn.

## Workflow

We use a simple workflow to keep the project organized:

### 1. Issues

For each new task (feature, bug, etc.), an issue must be created on our GitHub Kanban board.

### 2. Branches

- **`main`**: Contains the production/stable code. Only merges from `dev` are allowed.  
- **`dev`**: Main development branch. All work in progress is integrated here.  
- **`feat/<summary>`**: For new features (e.g., `feat/create-contact-page`).  
- **`fix/<summary>`**: For bug fixes (e.g., `fix/broken-footer-link`).  
- Always create your branch from `dev`.

### 3. Commits

- Use the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) standard (or a simplified version).  
- Examples: `feat:`, `fix:`, `docs:`, `style:`, `refactor:`, `test:`, `chore:`  
- Example message: `feat: add contact form with basic validation`.

### 4. Pull Requests (PRs)

- Once your task is complete, open a Pull Request from your branch to `dev`.  
- Use the [`PULL_REQUEST_TEMPLATE.md`](PULL_REQUEST_TEMPLATE.md) to describe your changes.  
- **Link the PR to its corresponding issue.**  
- Wait for peer review — the other team member must review and approve the changes.  
- After approval, the merge should be done using **“Squash and Merge”** to keep the `dev` history clean.

---

## Definition of Done (DoD)

A task is only considered “Done” when:

- ✅ The HTML opens in the browser without rendering errors.  
- ✅ Semantic best practices are applied (`<header>`, `<main>`, `<nav>`, `<section>`, etc.).  
- ✅ Basic accessibility is considered (e.g., `lang="en"`, `alt` on images, `label` linked to `input`).  
- ✅ The task checklist in the issue has been fully completed.  
- ✅ The Pull Request has been reviewed and approved by the other team member.

---

## Environment Setup

For **v1.0.0**, no dependencies are required.  
A code editor (such as VS Code) and a browser are sufficient.
