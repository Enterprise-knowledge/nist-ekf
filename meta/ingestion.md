# NIST Governance EKF Demo Ingestion

Document source sync, redaction, indexing, and artifact generation workflows here.

## Non-Markdown Source Conversion

Keep original non-markdown source files under `source/`. Use `markitdown` to generate markdown renderings under `artifacts/markdown/` before drafting curated concepts.

When `uv` is available, prefer a local `pyproject.toml`:

```sh
uv init --bare
uv add markitdown
```

When `uv` is unavailable, create a local virtual environment and install `markitdown` there:

```sh
python3 -m venv .venv
. .venv/bin/activate
python -m pip install markitdown
```

Generated markdown is an artifact, not canonical knowledge. Concepts under `knowledge/` should cite the original source path and may reference the generated markdown artifact when useful.
