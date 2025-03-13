.PHONY: tests, lints, docs, format

tests:
	uv run pytest

lints:
	uv run ruff check {{cookiecutter.project_slug}} examples

format:
	uv run ruff check --select I --fix {{cookiecutter.project_slug}} examples
	uv run ruff format {{cookiecutter.project_slug}} examples

docs:
	cd docs && make html
