# Qmeet interactive guide

Two main features in one guide: Activity Snapshots and AI Courseware. Switch features at the top and choose Student or Teacher in the left sidebar.

## Publish with GitHub Pages

1. Create a GitHub repository or use an existing one.
2. Upload the contents of this folder to the repository root. Keep `index.html`, `guides`, `assets`, `videos`, `.nojekyll`, and `.github/workflows/pages.yml` together.
3. Open **Settings → Pages → Build and deployment → Source** and select **GitHub Actions**.
4. Open **Actions → Deploy GitHub Pages → Run workflow**, then select your default branch.
5. The deployed website URL appears under **Settings → Pages**.

The workflow also deploys automatically after pushes to `main` or `master`.

For manual browser uploads, upload `index.html` and each folder separately. Files are below GitHub’s 25 MB browser upload limit. The original 79 MB standalone HTML is intentionally split into reusable images and two guide pages. No build tool, dependencies, API keys, or external services are needed.

The site uses relative paths and supports both project Pages and root Pages. Videos are linked from the guide footer. Name Card screens intentionally preserve the original Korean interface.

## Local preview

Run `python3 -m http.server 8000` from this directory and open http://localhost:8000.
