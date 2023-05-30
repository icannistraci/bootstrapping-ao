# Bootstrapping parallel anchors for relative representation

<p align="center">
    <a href="https://github.com/icannistraci/bootstrapping-ao/actions/workflows/test_suite.yml"><img alt="CI" src=https://img.shields.io/github/workflow/status/icannistraci/bootstrapping-ao/Test%20Suite/main?label=main%20checks></a>
    <a href="https://icannistraci.github.io/bootstrapping-ao"><img alt="Docs" src=https://img.shields.io/github/deployments/icannistraci/bootstrapping-ao/github-pages?label=docs></a>
    <a href="https://github.com/grok-ai/nn-template"><img alt="NN Template" src="https://shields.io/badge/nn--template-0.2.3-emerald?style=flat&labelColor=gray"></a>
    <a href="https://www.python.org/downloads/"><img alt="Python" src="https://img.shields.io/badge/python-3.9-blue.svg"></a>
    <a href="https://black.readthedocs.io/en/stable/"><img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg"></a>
</p>

Expand limited semantic correspondences between domains to enable latent communication through relative representations


## Installation

```bash
pip install git+ssh://git@github.com/icannistraci/bootstrapping-ao.git
```


## Quickstart

[comment]: <> (> Fill me!)


## Development installation

Setup the development environment:

```bash
git clone git@github.com:icannistraci/bootstrapping-ao.git
cd bootstrapping-ao
conda env create -f env.yaml
conda activate bootstrapping-ao
pre-commit install
```

Run the tests:

```bash
pre-commit run --all-files
pytest -v
```


### Update the dependencies

Re-install the project in edit mode:

```bash
pip install -e .[dev]
```
