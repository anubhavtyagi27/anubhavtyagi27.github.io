# anubhavtyagi27.github.io

Personal portfolio — a landing page, project case studies, and (for now) my resume.
Live at <https://anubhavtyagi27.github.io>; will eventually move to
`portfolio.anubhavtyagi.com`.

Plain hand-written HTML with a single shared stylesheet — no build step, no
dependencies. Push to `main` and GitHub Pages deploys it.

## Structure

```
index.html               Landing: intro, links, featured projects
projects/                Projects index + one case-study page per project
resume/                  Resume (moves to anubhavtyagi.com when that site is live)
assets/css/main.css      Design system: tokens, typography, components
assets/js/main.js        Theme toggle + scroll reveal (progressive enhancement)
404.html                 Not-found page
```

## Adding a project

1. Create `projects/<slug>/index.html` — copy an existing case-study page and
   edit the hero, meta row, buttons, and prose sections.
2. Add a project card to `projects/index.html` (and `index.html` if featured).
3. Put screenshots in `assets/img/` and replace the placeholder block.
