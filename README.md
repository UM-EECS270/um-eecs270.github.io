# EECS 270 GitHub Pages Starter

This starter is a plain Jekyll site for a **single-page EECS 270 course website** hosted on GitHub Pages.

It is now populated from the uploaded source files:
- `config.json` for course metadata, links, announcements, assignments, quiz URLs, lab URLs, final exam info, and the live week-by-week schedule
- `people.json` for faculty and staff cards
- `syllabus.md` for the syllabus source of truth
- `index.html` for section order and the live page structure

## What is split into YAML
- `_data/course.yml`
- `_data/navigation.yml`
- `_data/announcements.yml`
- `_data/resources.yml`
- `_data/schedule.yml`
- `_data/assignments.yml`
- `_data/people.yml`
- `_data/syllabus.yml`

## Source snapshots kept in the repo
- `config.source.json`
- `people.source.json`
- `index.source.html`
- `syllabus.source.md`

## Run locally
```bash
bundle install
bundle exec jekyll serve
```

## Publish on GitHub Pages
Push this folder to a GitHub repository and enable **GitHub Pages** from the repository root.
