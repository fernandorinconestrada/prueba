# prueba

A simple Python project using pandas.

## Requirements

- Python 3.8+

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install pandas
```

## .gitignore

The following are excluded from version control:

- `.venv/` — virtual environment
- `__pycache__/` — Python bytecode
- `*.pyc` — compiled Python files
- `.DS_Store` — macOS metadata

## Run

```bash
python src/prueba/main.py
```

## Project Structure

```
prueba/
├── .venv/              # virtual environment
├── .gitignore
├── pyproject.toml      # project metadata and dependencies
└── src/
    └── prueba/
        ├── __init__.py
        └── main.py
```
