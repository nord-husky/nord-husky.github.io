# nord-husky.github.io

This repository is set up as a GitHub Pages publish repository for `blog.nord-husky.com`.

Only the generated static site in `docs/` is intended to be pushed.

## GitHub Pages Setting

Configure the repository to deploy from the default branch using the `/docs` folder.

## Publish Flow

1. Keep the Hugo source and theme locally.
2. Build the site with Hugo.
3. Push the generated `docs/` output to GitHub.

## Local Build

```bash
hugo
```

The site is configured with `publishDir = "docs"`, so each build refreshes the published output directly.

## Local Preview

```bash
hugo server
```
