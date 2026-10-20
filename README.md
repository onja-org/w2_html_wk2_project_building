# HTML - PROJECT BUILDING: About Learning HTML

**Estimated time:** 5 hour 30 minutes

**Block:** HTML · Week 2


You've learned a lot about HTML during this week. Now it's time to share what you've learned. In this exercise, you need to create a website that can help others learn HTML.


- [Sections](#sections)
- [Pages](#pages)
- [Getting started](#getting-started)
- [How to check your work](#how-to-check-your-work)
- [Some hints](#some-hints)

## Sections

The website will be broken up into the following sections:

- Elements
- Rules
- Tips

## Pages

We won't be creating all the possible pages in this website. Instead, we'll be building at least the following 6 example pages:

- Homepage
- List of all the HTML5 elements
- List of all HTML rules
  - Nesting rules in detail
  - Attribute rules in detail
- Tips for writing HTML

### The homepage

The homepage needs to:

- introduce the website to the user, explaining what the website is about
- have a brief description of HTML
- offer links to the various sections.
- finish off with your details as the author. How do people know who wrote this website? How can they get in touch with you?

### List of HTML rules page

There are many rules for coding or writing HTML. List as many rules as you can, ideally around 15, one sentence per rule.

Two of the rules need to be links to their own pages:

- The nesting rules
- The attribute rules

Example rules to consider: proper nesting, closing tags, semantic elements, attribute syntax, DOCTYPE declaration, meta tags, void elements, etc.

#### Nesting rules page

In this page, you'll need:

- a link back to the list of rules
- a heading, giving this rule a title
- a description of this rule
- a "Don't do this!" code example of nesting
- a "Do this instead" code example of nesting

#### Attribute rules page

In this page, you'll need:

- a link back to the list of rules
- a heading, giving this rule a title
- a description of this rule
- a "Don't do this!" code example of using attributes
- a "Do this instead" code example of using attributes

### List of elements page

In this page, we need:

- a good title
- a definition of an HTML 'element' and what bits make up an 'element'
- a list of commonly used HTML5 elements, organized by **category** (e.g. sectioning, text content, forms, media) rather than one long undifferentiated list
  - Gather as many as you can, ideally around 90. You do not need to get every variant
  - Recommended: use a table with columns like `Element`, `Purpose`, `Self-closing?`, or group elements in sections with headings
  - Pick the ones you think are most important to teach. You don't need to recreate the entire MDN spec

**Quick reference:** See `lab/elements-reference.md` in this repo for a starter list of elements organized by category, or [MDN's HTML element reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) for the complete, canonical list.

### Tips for writing HTML page

This page is a chance to get personal. Give your reader at least 3 tips on how to write HTML. Think:

- How to write HTML quicker
- What tools to use
- How to make sure your work is high-quality

## Getting started

**Prerequisite:** this lab assumes you're already comfortable with Git branching and SSH setup from earlier lessons — you'll need both from step 2 onward.

1. Create a public repo called: `learning-html`, and add a `README.md`
1. Copy and clone the SSH URL for this new repo in a directory on your computer, preferably in `~/code/html`.
1. Create and push the `gh-pages` branch, and enable 'GitHub Pages' on that branch in the repo settings.
1. Add the URL for this website to the `README.md` file
1. Use `main` as your default development branch, only merging to `gh-pages` when you're ready to publish your changes.
1. In your repo root, create an `index.html` file (you can start from the scaffold in `lab/index.html`) and link it to your other pages (rules, elements, tips)
1. Get coding!

**Expected repo structure:**yes

```
w2_html_wk2_project_building/
├── lab/
│   ├── elements-reference.md
│   └── index.html
├── README.html
└── README.md
```

You don't need to match this exactly — organize how it makes sense to you.

## How to check your work

This project is practice, so nobody grades it. Use this checklist to check your own work:

- **Your use of English** (Spelling, Grammar) — proof-read your text before you finish
- **Your code cleanliness** (Is it easy to read, and free of garbage?)
  - ✅ Good: Proper indentation, semantic elements, closing tags, descriptive file/variable names
  - ❌ Bad: Inconsistent indentation, unnecessary `<div>` wrappers, missing closing tags, inline styles mixed with structure
- **Your use of HTML elements** (Did you use the correct HTML element? Could you have used an HTML element where there is none?)
  - Example: Use `<nav>` for navigation, `<article>` for self-contained content, `<table>` for tabular data
- **Your Git commits, pushes, branch use** — meaningful commit messages, regular commits, use of main/gh-pages branches

Also watch out for:

- **404s for any of your links** — test every link
- **validation errors in the W3C validator** — Warnings are OK, but errors should be fixed

## Some hints

- **Try to be consistent** — same indentation, same navigation structure on every page, consistent link naming
- **Keep your HTML clean and easy to read** — use proper indentation (2-4 spaces per level), avoid unnecessary divs, use semantic elements
- **Spell-check and proof-read your English** — check for typos and grammar mistakes
- **Validate and test your work** — use [W3C Validator](https://validator.w3.org/) to check for errors; test every link
- **Do your URLs make structural and meaningful sense?** — file names should reflect content (`elements.html`, not `page2.html`)
- **Document your folder structure in the README.md** — explain how students (or your future self) should run and develop this site
- **Link to your own pages when relevant** — if you write about an element, link to it in your elements page
- **Commit frequently with meaningful messages** — e.g., `git commit -m "Add elements page with table structure"` not just `git commit -m "update"`

*HTML · Week 2 · Coding System Wave 2*