# Python project template

This is a Python project template.

## Make it yours

After copying the template, you need to address the following TODOs.

### pyproject.toml

- [] Update the project `description`
- [] Update the project `name`
- [] Confirm desired Python version in `requires-python`
- [] Update the `Repository` and `Issues` URLs

## Development

### Install `uv`

The development of this project is managed with [uv](https://docs.astral.sh/uv/), "a single tool to replace `pip`, `pip-tools`, `pipx`, `poetry`, `pyenv`, `twine`, `virtualenv`, and more." You will need to install it. See the [uv installation instructions](https://docs.astral.sh/uv/getting-started/installation/).

### Install dependencies

```bash
uv sync
```

### Run formatter

```bash
uv run ruff format
```

### Run style checks

```bash
uv run ruff check
```

### Run dependency checks

```bash
uv run deptry src tests
```

### Run static type checks

```bash
uv run mypy
```

### Run tests

```bash
uv run pytest
```

### Build package

```bash
uv build
```