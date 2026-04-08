# The Principal Voices Project

Source for [principal-voices-project.com](https://principal-voices-project.com), a research initiative surveying K–12 school principals nationwide.

The site is built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Adding a report

Create a new markdown file in `_reports/` with front matter:

```markdown
---
title: "Report title"
date: 2026-04-15
authors: ["Christopher Campos", "John Singleton"]
summary: "One-sentence summary that appears on the home page."
pdf: /assets/reports/your-report.pdf
---

Report body in markdown.
```

The report will automatically appear on the home page and at `/reports/<slug>/`.

## Investigators

- Christopher Campos, University of Chicago Booth School of Business
- John Singleton, University of Rochester
