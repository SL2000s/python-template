# Python Repo Template

A simple template to start from in Python projects.

## Features
- Preconfigured `.gitignore`
- Pre-commit hooks (`ruff`, `mypy`)

## Usage

Create a new repo from this template:

```bash
gh repo create myproject --template SL2000s/python-template
cd myproject
```

Install pre-commit and run:
```bash
pre-commit install
```

Install UV Python package and project manager, and initialize a library by running:
```bash
uv init --lib
```
Replace the `--lib` flag with `--app` for applications, or `--app package` for packaged applications.
