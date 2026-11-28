# aixinli

Personal website of Aixin (Katherine) Li. GitHub Pages serves the `main` branch at https://katherine0723.github.io/aixinli/.

- `index.html`: the home page. It loads the cohort map data from `data/`.
- `path.html`: the "More about me" page.
- `.nojekyll`: Pages serves the files as they are, with no Jekyll build.

## Preview locally

The map data is fetched over HTTP, so use a static server rather than opening the file:

    python3 -m http.server 8000

Then open http://localhost:8000/.

## Checks

CI runs an offline check of local links (lychee) and HTML validation (html-validate, standard preset) on pushes to `main` and on pull requests.
