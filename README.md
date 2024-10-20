# codememaybe-site

This is the site where all the static pages will be served.

To build and run it locally on your machine, you would first need an installation on Python 3.0+ and the main [documentation](https://github.com/mbvgua/codememaybe-docs) repo on your local machine. Then create a virtual environment and install [mkdocs](https://www.mkdocs.org/), our Static Site Generator of choice!

1. Clone the repository

```bash
    git clone https://mbvgua.github.io/codememaybe-site/
```

2. Create and activate the virtual environment

```bash
    python -m venv .venv
    source .venv/bin/activate
```

3. Install mkdocs

```
    pip install mkdocs
```

4. Build the site

```bash
    mkdocs gh-deploy --config-file ../codememaybe-docs/website/mkdocs.yml --remote-branch gh-pages
```
