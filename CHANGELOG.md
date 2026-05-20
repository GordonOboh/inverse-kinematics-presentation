# Changelog

A record of all changes made to get the repository into its current state.

## Structure

```
inverse-kinematics/
├── README.md          ← Clean repo landing (links to Pages site)
├── CHANGELOG.md
├── .gitignore
└── docs/              ← GitHub Pages source (set main/docs in repo settings)
    ├── index.md       ← Homepage with embedded video
    ├── Inverse Kinematics.mp4
    ├── Inverse Kinematics-1.pdf
    └── Inverse Kinematics.pptx
```

## Changes Made

### 1. Relocated media into `docs/`
All presentation files (`.mp4`, `.pdf`, `.pptx`) were moved from the repo root into `docs/`. This keeps the repo root clean while giving GitHub Pages a single source for served assets.

### 2. Root `README.md` → clean redirect
The root README is a lightweight landing page with a link to the Pages site. No embedded media — just a clear call to action for GitHub.com visitors.

### 3. `docs/index.md` → Pages homepage
The full presentation overview with embedded video lives here. This is what visitors see at `gordonoboh.github.io/inverse-kinematics-presentation/`.

### 4. Link fixes
- Media paths updated from `../` (parent directory references) to local paths inside `docs/`

## Key Settings

- **GitHub Pages source**: `main /docs` (set in repo Settings > Pages)
- **No file duplication**: Everything lives in one place inside `docs/`
