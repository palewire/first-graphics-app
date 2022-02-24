A step-by-step guide to publishing a standalone story from a dataset.

- Demonstration: TK
- Documentation: [https://palewi.re/docs/first-visual-story/](https://palewi.re/docs/first-visual-story/)
- Issues: [https://github.com/palewire/first-visual-story/issues](https://github.com/palewire/first-visual-story/issues)

## Contributing to the docs

The documentation for this site is published via [Sphinx](https://www.sphinx-doc.org/en/master/) and written in [Markdown](https://www.markdownguide.org/) files in the [tutorial directory](/tutorial/).

An edit there followed by push to the master branch on GitHub will trigger the docs being redeployed to [https://palewi.re/docs/first-visual-story/](https://palewi.re/docs/first-visual-story/).

### Running the docs locally

- If you're using [pipenv](https://pipenv.pypa.io/en/latest/) (recommended), start a virtual environment with `pipenv shell`
- Install dependencies with `pipenv install --dev`
- Run `make docs`. You'll be able to see your local version of the docs at localhost:8000

## TODO: Editing the example site

The demonstration site at TK is published via TK, following the instructions in the tutorial. The files on the web are available here in the `docs` folder. Changes made there will go live following a push to the master branch on GitHub.
