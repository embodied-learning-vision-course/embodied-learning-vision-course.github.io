# Local Development

## ⚠️ Local Build Issues on macOS

The `eventmachine` gem has compilation issues on macOS. Use GitHub Actions for builds.

## Recommended: Use GitHub Actions

Push your changes to the `main` or `2026` branch and GitHub Actions will automatically build and deploy:

```bash
git add .
git commit -m "Your changes"
git push origin 2026
```

View the build at: https://github.com/embodied-learning-vision-course/embodied-learning-vision-course.github.io/actions

## Alternative: Docker (Has Issues)

**Note**: Docker has platform compatibility issues on arm64 Macs. Jekyll builds work on GitHub Actions (Linux).

If you want to try anyway:
```bash
docker-compose up
```

## GitHub Pages Deployment

The site auto-deploys when you push to `main` or `2026` branches.
