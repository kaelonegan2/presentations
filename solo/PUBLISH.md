# Publish Instructions

Use these commands to publish this exported deck to a separate public repository:

```bash
# From this export folder
git init
git add .
git commit -m "Publish presentation"
git branch -M main
git remote add origin <public-repo-url>
git push -u origin main
```

This export contains only review-ready artifacts (`index.html` + `assets`).
