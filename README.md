# Bootstrapping parallel anchors for relative representation

[Slides](https://icannistraci.github.io/ao-presentation/) |
[OpenReview](https://openreview.net/forum?id=VBuUL2IWlq) |
[arXiv](https://arxiv.org/abs/2303.00721) |
[BibTeX](#bibtex)

<!-- <p align="center">
    <img alt="NN Template" src="./assets/teaser.gif">
</p> -->
![](./assets/teaser.gif)

[Irene Cannistraci](https://irene.cannistraci.dev/),
[Luca Moschella](https://luca.moschella.dev/),
[Valentino Maiorca](https://gladia.di.uniroma1.it/authors/maiorca/),
[Marco Fumero](https://gladia.di.uniroma1.it/authors/fumero/),
[Antonio Norelli](https://noranta4.com/),
[Emanuele Rodolà](https://gladia.di.uniroma1.it/authors/rodola/)

## Installation

```bash
pip install git+ssh://git@github.com/icannistraci/bootstrapping-ao.git
```


## Quickstart

[comment]: <> (> Fill me!)


## Development installation

Setup the development environment:
gut
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
