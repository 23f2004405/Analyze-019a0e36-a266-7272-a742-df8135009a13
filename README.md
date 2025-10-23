# Analyze-019a0e36-a266-7272-a742-df8135009a13

## Overview
You are given two attachments: execute.py and data.xlsx.

- Commit execute.py after fixing the non-trivial error in it.
- Ensure it runs on Python 3.11+ with Pandas 2.3.
- Convert data.xlsx to data.csv and commit it.
- Add a GitHub Actions push workflow at .github/workflows/ci.yml that:
  - Runs ruff and shows its results in the CI log
  - Runs: python execute.py > result.json
  - Publishes result.json via GitHub Pages
- Do not commit result.json; it must be generated in CI.

## Setup
Open `index.html` in a browser or visit the GitHub Pages URL.

## Features
- Single-page web application
- Self-contained HTML/CSS/JS
- Mobile-responsive

## Evaluation Criteria
- execute.py, data.csv, and .github/workflows/ci.yml exist
- result.json is NOT committed
- execute.py does not contain the typo "revenew"
- data.csv content equals data.xlsx (attachment)
- CI YAML has steps for ruff, executing execute.py, and Pages deploy
- GitHub Actions ran for this commit and logs show ruff + execute.py
- result.json is published on GitHub Pages

## License
MIT License

## Live Demo
https://23f2004405.github.io/Analyze-019a0e36-a266-7272-a742-df8135009a13/
