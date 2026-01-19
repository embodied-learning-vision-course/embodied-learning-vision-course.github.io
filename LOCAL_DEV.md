# Local Development with Docker

## Quick Start

```bash
docker-compose up
```

Site will be at http://localhost:4000 with live reload.

## Manual Docker Command

```bash
docker run --rm -v "$PWD:/srv/jekyll" -p 4000:4000 jekyll/jekyll:4.4.1 jekyll serve --livereload --force_polling
```

## Why Docker?

The `eventmachine` gem (needed for Jekyll's live-reload) doesn't compile on macOS due to missing C++ headers. Docker uses Linux where it works fine.

## GitHub Actions

Pushes to `main` or `2026` branches automatically build and deploy via GitHub Actions.
