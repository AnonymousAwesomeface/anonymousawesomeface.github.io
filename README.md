# OmniFaceRig Project Page

Anonymous project page for SIGGRAPH Asia 2026 submission #2550.

## Deployment

This folder is self-contained. To deploy to GitHub Pages:

```bash
cp -r project_page/ /path/to/<anon>.github.io/
cd /path/to/<anon>.github.io/
git add . && git commit -m 'project page' && git push
```

## Contents

- `index.html` — main page (hero, abstract, video, dataset, results, pipeline)
- `paper.pdf`, `supplemental.pdf`
- `assets/` — figures and video
- `dataset_viewer/` — interactive GLB renderer (populated separately)
- `.nojekyll` — disables Jekyll on GitHub Pages
