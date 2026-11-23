# Useful Commands

Add a dependency:
```bash
uv add package
```

Add a development dependency:
```bash
uv add --dev package
```

Synchronise environment:
```bash
uv sync
```
Check code:
```bash
uv run ruff check .
```
Format code:
```bash
uv run ruff format .
```
Run tests:
```bash
uv run pytest
```