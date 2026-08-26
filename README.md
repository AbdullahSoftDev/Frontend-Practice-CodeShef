# Frontend Practice — CodeShef

A growing collection of standalone HTML/CSS practice files, built while working through frontend layout, styling, and form-building exercises. Each file is a **self-contained mini-task** — no build tools, no bundler, no dependencies. Just open the `.html` file directly in a browser and it runs.

This repo isn't a polished project — it's a working log of hands-on frontend reps: layout systems, semantic structure, forms, tables, and small interactive details, practiced one focused exercise at a time before layering on frameworks or heavier JavaScript.

---

## 🎯 Why This Repo Exists

Frontend fundamentals (flexbox, semantic HTML, accessible forms, responsive layout) are easy to gloss over once frameworks are in the picture. This repo is deliberate practice at the raw HTML/CSS layer — building the same kinds of components (forms, cards, tables, hero sections) enough times, in plain markup, that the underlying patterns become second nature. That foundation is what makes framework work (React, Tailwind, etc.) faster and more intentional later.

---

## 🗂 What's Inside

Every exercise lives as its own `.html` file at the repo root — the filename describes the task. Grouped by theme:

### 🧱 Layout & Flexbox
| File | Focus |
|---|---|
| `Flexbox.html` | Core flexbox container/item behavior |
| `Flexbox with justify-content.html` | Controlling horizontal alignment/spacing with `justify-content` |
| `An image at the top.html` | Basic image + layout composition |
| `An image at the top with title.html` | Adding a heading alongside an image block |
| `An image at the top with title with short paragraph.html` | Extending the composition with body copy |
| `An image at the top with title with short paragraph copy and a button.html` | Adding a call-to-action button to the layout |
| `An image at the top with title with short paragraph copy and a button and animation.html` | Layering in a hover/entrance animation |
| `A box with a border and rounded corners copy.html` | Border, border-radius, and box styling basics |

### 📝 Forms
| File | Focus |
|---|---|
| `Login.html` | Basic login form structure |
| `Simple Sign-Up Form.html` | Sign-up form fields and layout |
| `Task - Simple Contact Form.html` | Contact form with validation-friendly structure |
| `Task - Build an Event RSVP Form.html` | RSVP-style form with multiple input types |
| `Build a User Profile Form.html` | Profile form with grouped fields |
| `How to use radio buttons and checkboxes to give users a choice in a form.html` | Radio buttons & checkboxes for single/multi-choice inputs |

### 📊 Tables
| File | Focus |
|---|---|
| `Task - Student Information Table.html` | Structured tabular data with semantic table markup |
| `Build a Conference Schedule Table.html` | Table layout for scheduling/event data |
| `Task 1 - Creating a Student Report Card.html` | Report-card style structured table |

### 🎴 Components
| File | Focus |
|---|---|
| `build me a card component with a hover effect.html` | Card component with a hover-state transition |

### 🛠 Workshop Exercises
| File | Focus |
|---|---|
| `WorkshopBeforeFixed.html` | Starting point of a workshop debugging/fix exercise |
| `WorkshopAfterFixed.html` | Fixed/completed version of the same exercise |
| `Frontend new.html` | Additional general frontend practice |

*(This table is updated as new exercises are added — check the file list in the repo for the most current set.)*

---

## 🧠 What Each File Practices

Across the exercises, the recurring skills being reinforced are:

- **Semantic HTML** — using the right tags (`<form>`, `<table>`, `<fieldset>`, `<label>`, etc.) instead of generic `<div>`s everywhere
- **Flexbox layout** — alignment, spacing, and responsive-friendly structure without relying on floats or manual positioning
- **Form design & accessibility** — proper `<label>`–input pairing, grouped fields, appropriate input types (`radio`, `checkbox`, `email`, etc.)
- **Table structure** — `<thead>`, `<tbody>`, and row/column semantics for genuinely tabular data
- **Basic styling** — borders, border-radius, spacing, and simple hover/transition effects
- **Incremental composition** — several files build the *same* layout step by step (image → image+title → image+title+paragraph → +button → +animation), intentionally, to isolate what each added piece changes

---

## 🛠 How to Use This Repo

Clone it and open any file directly — no setup required:

```bash
git clone https://github.com/AbdullahSoftDev/Frontend-Practice-CodeShef.git
cd Frontend-Practice-CodeShef
```

Then just open any `.html` file in a browser (double-click it, or use an editor extension like VS Code's "Live Server" for auto-reload while editing).

No `package.json`, no build step, no external dependencies beyond what's linked directly in each file (if anything).

---

## 📌 Notes on Organization

This repo is intentionally **flat** (all files at the root) since each exercise is small and self-contained. As the collection grows, exercises may get reorganized into themed subfolders (`/forms`, `/layout`, `/tables`, etc.) — for now, the table above serves as the index.

---

## 👤 About

**Muhammad Abdullah** — CS student and full-stack AI developer, building frontend fundamentals alongside daily [DSA practice](https://github.com/AbdullahSoftDev/Leet-Code-Submissions).

- GitHub: [@AbdullahSoftDev](https://github.com/AbdullahSoftDev)
