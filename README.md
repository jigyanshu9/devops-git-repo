# DevOps Git Project

A small Flask app used to demonstrate Git best practices: branching,
pull requests, tagging, and documentation.

## Tech Stack
Python, Flask, Docker, GitHub Actions

## Branching Strategy
- `main`: stable, production-ready code (tagged releases)
- `dev`: integration branch for completed features
- `feature/*`: one branch per feature, merged into `dev` via PR

## Getting Started
```bash
git clone https://github.com/<username>/devops-git-project.git
cd devops-git-project
pip install -r requirements.txt
python app.py
```

## Commit Convention
`feat:`, `fix:`, `docs:`, `chore:`, `ci:`

## Releases
See the Releases page and `docs/TASKS.md`.
