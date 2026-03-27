# Audio & Annotation Demo

Anonymous supplementary demo page for double-blind review.

## Contents

- `index.html` — Static demo page (open in browser)
- `*.wav` — Audio recordings (4 Q-R pairs, 8 files)
- `*.TextGrid` — Praat multi-tier forced alignment annotations
- `*.PitchTier` — F0 contour annotations

## Deployment

### Anonymous Review (anonymous.4open.science)

1. Go to https://anonymous.4open.science
2. Create a new anonymous repository
3. Upload all files in this folder
4. The demo will be accessible at `https://anonymous.4open.science/r/<repo-id>/index.html`

### GitHub Pages

```bash
git init && git add . && git commit -m "demo"
git remote add origin <repo-url>
git push -u origin main
```

Enable Pages in Settings → Pages → Source: main / root.
