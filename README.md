# Public Presentations

This repository hosts public, review-ready presentations generated and managed from a private build workflow.

## Why this exists
- Keep presentation creation structured and repeatable with agent-managed workflows.
- Publish only final artifacts for external review (`index.html` + assets).
- Provide simple public access via GitHub Pages.

## Structure
- Each presentation lives in its own folder (for example: `solo/`).
- Open the folder's `index.html` through GitHub Pages to view the presentation.

## Update flow
- Presentations are created and edited in the private source repository.
- A publish command exports and syncs the selected presentation folder here.

## Available presentations
- [psug-se26](./psug-se26/)
- [solo](./solo/)
