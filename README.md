# microstructure_lob
Made for Limit Order Book lab and analysis

## Setup

Requires miniforge or mamba.

```bash
mamba env create -f environment.yml
conda activate lob
```

A Jupyter kernel named **Python (lob)** is registered for notebooks:

```bash
python -m ipykernel install --user --name lob --display-name "Python (lob)"
```

To update after editing `environment.yml`:

```bash
mamba env update -f environment.yml --prune
```
