# unitn-master-ia

A GitHub Pages-ready digital study notebook for the **Artificial Intelligence Systems** master's at the **Università di Trento**.

The repository is designed to grow across the whole master's degree. At the moment it contains only **Machine Learning**, while the architecture is intentionally course-agnostic so Foundations of AI and future courses can be added later without redesigning the site.

## Current structure

- Master overview
  - Machine Learning
    - Module 1
      - A.P.
        - Class 1 — Bayesian Networks
        - Class 2 — Learning in Graphical Models
      - F.M.
        - Moodle recordings & slides
        - Lecture-note migration area
    - Module 2
      - Reserved for later this semester

## Design goals

- Poppins typography
- no decorative emojis
- notebook-like reading layout
- KaTeX math rendering
- explicit visual labels for Further explanation, Simplified definition, Example, Blackboard example, and Useful connection
- sticky course navigation and automatic page table of contents
- quick navigation with `Ctrl/Cmd + K`
- clean print/PDF stylesheet via the **Export PDF** button
- responsive layout for iPad and mobile
- SVG diagrams for graphical models
- architecture that can expand to the full master's degree

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Deploy to GitHub Pages

The repository contains `.github/workflows/deploy.yml`.

1. Push the repository to GitHub as `unitn-master-ia`.
2. Open **Settings → Pages**.
3. Set **Build and deployment → Source** to **GitHub Actions** if GitHub has not already selected it.
4. Pushes to `main` build and deploy automatically.

The workflow automatically sets Astro's base path to `/unitn-master-ia`, so the project Pages URL works without hard-coded internal paths.

## Current Machine Learning resources

- A.P. — official class materials and recordings are kept in the private course platforms.
- F.M. — Moodle recordings & slides: https://didatticaonline.unitn.it/dol/course/view.php?id=44129

## Content convention

Lecture/slide content is presented normally. Added study material is explicitly marked as:

- **Further explanation**
- **Simplified definition**
- **Example**
- **Blackboard example**
- **Useful connection**

This makes it easy to distinguish source material from explanatory notes added for studying.
