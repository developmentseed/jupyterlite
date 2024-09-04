## Developer Documentation

```bash
uv run jupyter lite build --contents content --output-dir dist
```

Then start a CORS-enabled server from the `dist` directory.

```bash
cd dist
npx http-server --cors
```
