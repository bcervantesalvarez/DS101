# DS 101 · GitHub Learning Module
*A 1-credit micro-course for undergraduates*

This repository houses a complete, four-part Canvas/Quarto package that  

1. **Explains** what GitHub is and why it matters,  
2. **Teaches** the fundamentals (branches, pull requests, issues, etc.),  
3. **Applies** those skills by building a Quarto portfolio on GitHub Pages, and  
4. **Assesses** mastery through individual and collaborative assignments.  

---

## 📑 Module Map

| Part | Canvas Page / Activity | Folder |
|------|------------------------|--------|
| **1 · Introduction** | What GitHub is & why we care | `01-introduction/` |
| **2 · Learning Module** | Deep-dive tutorial · 2 readings · 10-question quiz | `02-learning-github/` |
| **3 · Application** | Workshop: build a Quarto portfolio (setup included) | `03-application-portfolio/` |
| **4 · Assignments** | • Individual repo • Team workflow • *Extra credit*: personal site | `04-assignments/` |

> **Sequential requirement**: Readings → Quiz ≥ 80 % → Workshop → Assignments.

---

## 🌳 Folder Structure
```text
ds101-github-module/
├── index.qmd                     # Optional home/index for GitHub or Quarto site
│
├── 01-introduction/              # 📘 Module 1: Overview of GitHub and its value
│   └── intro.qmd
│
├── 02-learning-github/           # 🛠️ Module 2: Git & GitHub fundamentals
│   ├── lesson.qmd                # Main step-by-step lesson
│   ├── readings/                 # Pre-reading resources
│   │   ├── article-01.pdf
│   │   └── article-02.pdf
│   └── quiz/                     # 10-question reading & concept check
│       ├── quiz-bank.yaml
│       └── quiz-instructions.md
│
├── 03-application-portfolio/     # 🌐 Module 3: Build your Quarto portfolio
│   ├── setup-guide.qmd           # Pre-workshop Git & RStudio setup
│   ├── build-portfolio.qmd       # Full guide to creating a Quarto website
│   └── sample-site/              # Optional starter files for student demo sites
│
├── 04-assignments/               # 📝 Final assignments (individual + team)
│   ├── individual-repo/          # Create a personal repo and push changes
│   │   ├── instructions.qmd
│   │   └── rubric.md
│   ├── collaboration-repo/       # Collaborate with classmates via GitHub
│   │   ├── instructions.qmd
│   │   └── rubric.md
│   └── extra-credit-portfolio/   # Bonus: Publish your Quarto site
│       ├── instructions.qmd
│       └── rubric.md
│
└── _resources/                   # 🎨 Shared design resources
    └── css/canvas-overrides.css # Custom styles for Canvas/HTML rendering
```

## 📁 Folder Structure Overview

This repository contains all the materials for the **DS 101 GitHub Module**, part of a 1-credit introductory data science course for undergraduate students. Each section corresponds to a major learning component in the Canvas module.

---

### `01-introduction/`

This is where students begin their journey.

- `intro.qmd` – Source file for the Introduction page (Quarto)
- `intro.html` / `intro.pdf` – Rendered versions of the Introduction
- `intro_files/` – Supporting assets (e.g., images or CSS) for the Introduction

---

### `02-learning-github/`

This section contains the main GitHub and Git lesson.

- `lesson.qmd` – Full lesson from Git install to first commit
- `lesson.html` / `lesson.pdf` – Rendered versions for Canvas or web
- `lesson_files/` – Quarto-generated files for rendering
- `quiz/` – 10-question comprehension quiz after completing the reading and lesson
- `readings/` – Linked or embedded readings that explain what GitHub is and how the terminal works

---

### `03-application-portfolio/`

This section helps students build their **live portfolio website**.

- `build-portfolio.qmd` – Walks students through creating and customizing a Quarto site
- `build-portfolio.html` / `.pdf` – Rendered outputs of the guide
- `build-portfolio_files/` – Assets for the build guide (images, styles)
- `setup-guide.qmd` – A pre-workshop setup guide (installing Git, connecting RStudio, PATs)
- `setup-guide.html` / `.pdf` – Rendered versions for quick access
- `setup-guide_files/` – Setup guide support folder

---

### `04-assignments/`

This folder contains all student assignments, including templates and grading rubrics.

#### `individual-repo/`

- `individual.qmd` – Assignment instructions to create a personal GitHub repo and push content
- `individual.html` / `.pdf` – Rendered views for submission and grading
- `individual_files/` – Support folder for rendered content

#### `collaboration-repo/`

- Group assignment focused on GitHub collaboration
- Students clone each other's repos, make edits, and push/pull changes as a team

#### `extra-credit-portfolio/`

- Instructions for creating and submitting a published Quarto portfolio website
- Bonus credit for customizing the portfolio beyond the basics

---

### Root Files

- `README.md` – You're reading it! Overview of the course module structure
- `LICENSE` – Open license terms for reuse or adaptation
- `rubric.md` – Grading rubric used for assignments and extra credit evaluations

---

## 🔁 Workflow Reminder

Each `.qmd` file is written in **Quarto** and can be rendered into HTML or PDF.  
Render using:

```bash
quarto render filename.qmd
```



---

## 🚀 Quick Start
```bash
# Clone the teaching materials
git clone https://github.com/bcervantesalvarez/ds101-github-module.git
cd ds101-github-module

# Preview any .qmd in RStudio, VS Code, or terminal
quarto preview index.qmd
```
**Canvas tip:** Upload each rendered HTML (or paste Markdown) into its matching Canvas page, and import `quiz-bank.yaml` through **Quizzes → Import** (QTI 1.2).

---

## 📝 Grading Snapshot

| Assignment | Points | Key Criterion |
|------------|-------:|---------------|
| Individual repo | 40 | Instructor can `git clone` & required file exists |
| Team workflow  | 40 | All members pull, push, & resolve merge cleanly |
| Reading quiz   | 20 | Score ≥ 80 % (unlocks Part 3) |
| **Extra credit** | +10 | Live Quarto site with About + Projects pages |

Rubrics live beside each assignment in `04-assignments/`.

---

## 🤝 Contributing

Issues and PRs are welcome—especially typo fixes, new quiz questions, or accessibility improvements.

---

## 📜 License

Creative Commons **CC-BY-SA 4.0**. Share and adapt with attribution to *Brian Cervantes Alvarez*; keep derivatives under the same license.

---

_Built with [Quarto](https://quarto.org) · Managed on GitHub · Documentation generated by ChatGPT o3_
