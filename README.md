# CoreValley documentation

Source for https://docs.corevalley.ai — MkDocs Material.

- Pages: Markdown in `docs/`. Sidebar order and labels: `nav` in `mkdocs.yml`.
- Publish: push to `main`; `.github/workflows/deploy-docs.yml` builds and deploys to GitHub Pages.
- Preview locally:

  ```bash
  pip install -r requirements.txt
  mkdocs serve        # http://127.0.0.1:8000
  ```

`docs/CNAME` holds the custom domain. Do not delete it.
