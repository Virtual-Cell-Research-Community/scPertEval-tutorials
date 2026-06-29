# scPertEval-tutorials

Jupyter notebook tutorials for [scPertEval](https://github.com/Virtual-Cell-Research-Community/scPertEval).

These notebooks are fetched automatically by the scPertEval docs build and rendered at
https://scperteval.readthedocs.io under the **Tutorials** section.

## Adding a tutorial

1. Place your notebook under `notebooks/`.
2. Name it with a numeric prefix so ordering is deterministic, e.g. `notebooks/01_cli_walkthrough.ipynb`.
3. Commit and push — the next docs build will pick it up automatically.

## Running locally

```bash
pip install scperteval[dev]
jupyter lab notebooks/
```

## Planned tutorials

| Notebook | Status |
|---|---|
| `01_cli_walkthrough.ipynb` | planned |
| `02_python_api.ipynb` | planned |
| `03_extending.ipynb` | planned |
