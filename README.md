# Ichnos

An event ingestion, storage and search engine for security events. Ichnos (ἴχνος) means "track" or "trace".

Status: early development.

## Requirements

- [uv](https://docs.astral.sh/uv/) (installs Python 3.12 for the project)
- Docker

## Development

```sh
cd python
uv sync
uv run pytest
uv run ruff check .
```
