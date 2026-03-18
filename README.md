# test9

> BSE project workspace — data science & econometrics

## Team
- jane
- john

## Repository Structure

```
data/
  raw/        # Original, immutable source data
  processed/  # Cleaned / transformed datasets
notebooks/    # Jupyter notebooks (exploratory & final)
scripts/      # Reusable Python scripts & modules
outputs/
  figures/    # Charts and plots
  tables/     # LaTeX / CSV result tables
```

## Setup

```bash
# Create virtual environment
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Workflow

1. Raw data goes in `data/raw/` — never modify it directly.
2. Cleaning scripts live in `scripts/`; write outputs to `data/processed/`.
3. Analysis notebooks live in `notebooks/`; save figures to `outputs/figures/`.
4. Push AI-generated code via **Nexus** → branch `mvp-demo` → open PR.
