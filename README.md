# nickquam.com

Static personal landing page for Nick Quam, hosted on GitHub Pages at
[nickquam.com](https://nickquam.com).

## Purpose

This site is the personal front door for Nick's current work:

- [Astretto](https://astretto.com) - focused consumer software studio
- [Checkout](https://checkoutrankings.com) - native iPhone grocery rankings app

## Architecture

The project intentionally stays lightweight:

- `index.html` contains the markup, styling, and tiny year script.
- `CNAME` maps GitHub Pages to `nickquam.com`.
- There is no build step, package manager, framework, or generated output.

## Local Preview

From the repo root:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deploy

GitHub Pages deploys from `master`:

```bash
git push origin master
```
