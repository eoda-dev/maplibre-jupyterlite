# MapLibre JupyterLite

```bash
uv sync
source .venv/bin/activate

jupyter lite build --contents content --output-dir dist
cd dist
python -m http.server
```

