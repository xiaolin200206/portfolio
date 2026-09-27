# Portfolio — deploy to GitHub Pages (5 minutes)

Goal: make https://xiaolin200206.github.io/portfolio/ live again (the link already in your emails).

1. On GitHub: New repository → name it exactly `portfolio` → Public → Create.
2. Upload these files to the repo root: `index.html`, `Lin_Ding_Shan_Resume.pdf`
   (drag-and-drop on the repo page → "Add file" → "Upload files" → Commit).
3. Repo → Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.
4. Wait 1–3 minutes, open https://xiaolin200206.github.io/portfolio/

Later:
- Add a photo/video: put the file in the repo (e.g. `img/device.jpg`) and replace the
  "Device photo / 30-second field demo goes here" block in index.html with
  `<img src="img/device.jpg" alt="...">` (see the HTML comment there).
- New résumé: overwrite `Lin_Ding_Shan_Resume.pdf` with the same filename.
- Paper accepted / grower trials: edit the text in index.html directly; it's plain HTML, no build step.
