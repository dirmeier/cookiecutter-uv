# `uv` cookiecutter template

[![Project Status](http://www.repostatus.org/badges/latest/concept.svg)](http://www.repostatus.org/#concept)

> My template for Python apps built with `uv`

## About

This repository implements a template for a minimal Python package that uses `uv`+Setuptools for packaging and dependency management.

## Installation

1) Install `cookiecutter` first and then:

    ```bash
    cookiecutter gh:dirmeier/cookiecutter-uv
    ```

2) After having created a project, install all dependencies using `uv`(https://github.com/astral-sh/uv):

    ```shell
    uv sync --all-extras
    ```

3) Init a GitHub repo using

   ```shell
   git init
   git remote add origin git git@github.com:{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}.git
   ```

4) Install `pre-commit` and `gitlint` via:

   ```shell
   pre-commit install
   gitlint install-hook
   ``` 

5) Create a new branch for development via:

    ```shell
   git checkout -b my-new-feature
    ```
6) Develop code, implement unit tests and write documentation.
7) Test everything via

   ```shell
   make format
   make lints 
   make tests 
   make docs
   ```

8) Commit your changes using a informative commit message. Read [this](https://cbea.ms/git-commit/) for help.
9) Push your changes to your feature-branch and create a pull-request.
10) Squash-merge your changes onto main or, ideally, clean up your commit history and rebase onto main.
11) Don't forget to create tags and releases.

## Author

Simon Dirmeier <a href="mailto:sfyrbnd @ pm me">sfyrbnd @ pm me</a>
