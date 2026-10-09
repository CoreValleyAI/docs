# CoreValley docs host

This repository serves **https://docs.corevalley.ai/** through GitHub Pages.
It holds no documentation itself.

The docs are the docs build of
[CoreValleyAI/redesigned-portal](https://github.com/CoreValleyAI/redesigned-portal):
Markdown in `corevalley-docs/docs/`, sidebar order in `corevalley-docs/mkdocs.yml`,
built with `npm run build:docs`. Edit them there.

`.github/workflows/deploy-docs.yml` checks that repository's `main` every
15 minutes and rebuilds and deploys when it has moved. To publish at once:
Actions → **Deploy docs** → **Run workflow**.
