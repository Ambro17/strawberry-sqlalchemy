# Strawberry-Sqlalchemy

## Features
- Define models from alchemy
- Relay Support

## Dev Setup
```
python3 -m venv .venv
source .venv/bin/activate
pip install -U pip pip-tools
pip-sync requirements.txt requirements-dev.txt
```

## Publish
```bash
rm -rf dist/* && \
python3 -m build && \
twine upload dist/*
```