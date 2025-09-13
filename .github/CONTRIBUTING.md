# Contributing to MLdocs

Thank you for considering contributing to **[MLdocs](https://github.com/Artificial-Geeks/MLdocs)**.
We welcome contributions of all kinds — bug reports, fixes, improvements, and new content.

---

## Ways to Contribute

### 1. Report Bugs

- Open a [Bug Report](../../issues/new?labels=bug).
- Include:
  - Page link or section where the issue occurs.
  - What is wrong or missing.
  - What you expected instead.

### 2. Suggest Improvements

- Open a [Feature Request](../../issues/new?labels=enhancement).
- Explain what you want, why it helps, and any alternatives.

### 3. Edit or Add Docs

- Fork the repo and create a branch:

  ```bash
  git checkout -b docs/my-change
  ```

- Make changes in `content/docs`.
- Preview locally (see setup below).
- Commit and push your branch.
- Open a Pull Request (PR).

### 4. Pull Requests

- Keep PRs focused and small.
- Use clear commit messages (see below).
- In the PR description, explain what changed and why.

---

## Development Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Artificial-Geeks/MLdocs.git
   cd MLdocs
   ```

2. Install dependencies:

   ```bash
   npm install
   # or
   pnpm install
   ```

3. Start dev server:

   ```bash
   npm run dev
   ```

4. Open: [http://localhost:3000](http://localhost:3000)

---

## Commit Guidelines

We follow [Conventional Commits](https://www.conventionalcommits.org/):

- Format:

  ```
  <type>(scope): short description
  ```

- Common types:
  - `fix:` bug fixes
  - `feat:` new features
  - `docs:` documentation changes
  - `chore:` maintenance tasks
  - `refactor:` code changes without new features or fixes

**Example:**

```
docs(content): fix typo in introduction page
```

---

## Style Guide

- Follow existing structure and tone.
- Use clear, simple language.
- Add examples where useful.
- Use Markdown best practices (headings, lists, links).
