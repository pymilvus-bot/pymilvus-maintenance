# pymilvus-maintenance

State tracking repository for the pymilvus maintenance agent.

## Setup

This repo should live at `pymilvus-bot/pymilvus-maintenance` on GitHub (private).

```bash
cd ~/.pymilvus-maintenance
git init
git remote add origin git@github.com:pymilvus-bot/pymilvus-maintenance.git
git add .
git commit -m "Initial state"
git push -u origin main
```

## Files

- `state.json` — Tracks processed issues, attempted fixes, refactor history, and schedule state.
