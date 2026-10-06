# Workflows

| Workflow | Runs on | What it does |
| --- | --- | --- |
| [Publish the engine](pages.yml) | Pushes to `main` that change `assets.lock`, `site/` or the workflow. Also by hand | Downloads the pinned BusyTeX release, checks its SHA-256 and deploys it to GitHub Pages |
| [Markdown lint](markdownlint.yml) | Pull requests and pushes to `main` | Lints every Markdown file |
