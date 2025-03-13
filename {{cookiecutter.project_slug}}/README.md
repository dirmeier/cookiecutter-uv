# {{ cookiecutter.project_readme_title }}

[![status](http://www.repostatus.org/badges/latest/concept.svg)](http://www.repostatus.org/#concept)
[![ci](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/actions/workflows/ci.yaml/badge.svg)](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/actions/workflows/ci.yaml)
[![coverage](https://codecov.io/gh/ramsey-devs/ramsey/branch/main/graph/badge.svg?token=dn1xNBSalZ)](https://codecov.io/gh/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }})
[![code quality](https://www.codacy.com/)](https://www.codacy.com/)
[![documentation](https://readthedocs.org/projects/{{ cookiecutter.project_slug }}/badge/?version=latest)](https://{{ cookiecutter.project_slug }}.readthedocs.io/en/latest/?badge=latest)
[![version](https://img.shields.io/pypi/v/ramsey.svg?colorB=black&style=flat)](https://pypi.org/project/{{ cookiecutter.project_slug }}/)

> {{ cookiecutter.project_short_description }}

## About

TODO

## Example usage

TODO

## Installation

To install the package from PyPi, call:

```bash
pip install {{ cookiecutter.project_slug }}
```

To install the latest GitHub <RELEASE>, just call the following on the command line:

```bash
pip install git+https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}@<RELEASE>
```

Please do not directly install from the `main` branch, since these commits are not tested, but prefer using PyPI or a stable release.

## Contributing

Contributions in the form of pull requests are more than welcome. In order to contribute:

1) Clone {{ cookiecutter.project_slug }} and install  `uv` from [here](https://github.com/astral-sh/uv),
2) create a new branch locally `git checkout -b feature/my-new-feature` or `git checkout -b issue/fixes-bug`,
3) install all dependencies via `uv sync --all-extras`,
4) implement your contribution and ideally a test case,
5) test it by calling `make format`, `make lints` and `make tests` on the (Unix) command line,
6) submit a PR 🙂

## Author

{{cookiecutter.full_name}} <a href="mailto:{{cookiecutter.email}}">{{cookiecutter.email}}</a>
