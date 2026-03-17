# Embodied Learning and Vision Course Website

Course website for DS-GA 3001.003 / CSCI-GA 3033.115 at NYU.

**Live site:** [elvcourse.org](https://elvcourse.org)

## Local Development

Requires Ruby 3.3+ and Bundler.

```bash
bundle install
bundle exec jekyll serve
```

Preview at `http://localhost:4000`.

## Deployment

Pushes to the `2026` branch are automatically built and deployed to GitHub Pages via GitHub Actions.

## Structure

- `index.md` — Home page
- `content.md` — Lecture calendar and schedule
- `readings.md` — Reading list by module
- `projects.md` — Student project listings
- `staff.md` — Course staff
- `_staffers/` — Staff member profiles
- `2025/` — Archived previous year site
