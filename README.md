# Git Workshop — Team Wall

A simple static website used for the Git & GitHub workshop.

## How to add your group card

Open `index.html` and find this comment:

```html
<!-- ADD YOUR GROUP CARD BELOW THIS LINE -->
```

Copy the template below and paste it there:

```html
<div class="card">
  <div class="card-badge">Group A</div>
  <div class="avatar">A</div>
  <h2>Your Name</h2>
  <p class="role">Your Role / Dept</p>
  <p class="bio">A short sentence about your group.</p>
  <div class="tags">
    <span>Tag1</span>
    <span>Tag2</span>
  </div>
</div>
```

Change:
- `Group A` → your group name
- `A` inside `.avatar` → first letter of your group name
- `Your Name`, `Your Role`, bio, and tags → your actual info

## Project structure

```
gitworkshop/
├── index.html          ← main page (edit this)
├── style.css           ← styles (do not edit)
├── README.md           ← this file
└── .github/
    └── workflows/
        └── deploy.yml  ← auto-deploys on push to main
```

## Deployment

Pushing to `main` automatically publishes the site via GitHub Actions → GitHub Pages.
