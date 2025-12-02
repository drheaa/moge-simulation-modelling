# Contributing Guidelines

Welcome to our MOGE Thesis repository! To keep things clean, organized, and chaos-free, please follow these rules when contributing.

## The Golden Rule

**Never push directly to main**

All work must be done in branches and merged through a Pull Request (PR).

## Branch Workflow

### 1. Update your local repo

Always start by pulling the latest updates:

```bash
git checkout main
git pull origin main
```

### 2. Create a new branch

Branch names should match what you're working on:

**Examples:**
- chapter2
- fix-simulation-code
- add-figures
- intro-edits

**Command:**
```bash
git checkout -b your-branch-name
```

### 3. Do your work normally

Edit files → save → test PDF → etc.

### 4. Commit your changes

Write clear commit messages:

```bash
git add .
git commit -m "Finish Section 2.1 exponential distribution"
```

### 5. Push your branch

```bash
git push origin your-branch-name
```

6. Open a Pull Request (PR)

Go to GitHub repo

Click “Compare & Pull Request”

Add a clear title/description

Tag teammates for review

No PR = No merge.

7. Someone reviews → approves → merge

Once reviewed, you can press Merge Pull Request.

## What NOT to do

- **No pushing directly to main**

- **No merging without review**

- **No committing generated files (PDFs, temp files, etc.)**

## Branch Naming Rules

Keep it short & meaningful:

- Feature: feat-chapter5-derivation

- Fix: fix-typo-cdf

- Update: update-simulation-plots

- Docs: docs-readme-update

## Folder Structure Discipline

Please put files in the correct folders:

```text
LaTeX chapters → chapters/

Figures → figures/

Python scripts → code/

Data → data/

References → references.bib
```

## Before merging into main, make sure:

1) LaTeX compiles with no errors

2) main.pdf builds correctly

3) No conflicts with existing work

4) Your branch is up to date:

```bash
git pull origin main
git merge main
```

## Final Notes

We’re building a whole thesis together, so let’s keep it clean, organized, and easy for everyone.

If something breaks, don’t panic. Just message in the GC and we’ll fix it 🔧

Happy contributing! 