# 2026 LLM Zoomcamp

## Setup

Use Python 3.14.9 or later and uv 0.13.5 or later. The pinned development
interpreter is recorded in `.python-version`.

```sh
uv sync --locked
uv run main.py
```

The certifi minimum version addresses GHSA-6q48-6c7w-9gw2. Existing virtual
environments also need updated tooling: pip 26.2.2 or later (if pip is installed)
and uv 0.13.4 or later. Updating the project lockfile does not update a separately
installed pip or uv. Keep operating-system CA certificates updated as well.
