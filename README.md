# Python Repo Template

A lightweight GitHub template for starting new Python projects using [UV](https://github.com/astral-sh/uv).

## Features
- Preconfigured `.gitignore` for Python projects
- Pre-commit hooks for linting and type-checking

## Usage

### 1. Clone repo

Create a new repository from this template:

```bash
gh repo create myproject --template SL2000s/python-template
cd myproject
```

### 2. Set up pre-commit

Install [pre-commit](https://pre-commit.com) (via pip, uv, or your system package manager):

```bash
uv tool install pre-commit
pre-commit install
```

### 3. Initialize your Python project

Install [uv](https://github.com/astral-sh/uv) if you don’t have it already, then create a new Python library package:

```bash
uv init --lib
```

Replace `--lib` with:

* `--app` for an application
* `--app --package` for a packaged application
