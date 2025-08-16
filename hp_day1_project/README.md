# HP Model – Day 1 (Quantum Protein Folding Mini-Project)

This repo contains a **presentable, Colab-ready notebook** that implements the Day 1 lattice HP toy model for a 6-residue chain:

- Enumerate **all 284** valid self-avoiding 2D folds
- Score energies using **H–H contact** rules (non-consecutive lattice neighbors)
- Visualize top folds and an **energy distribution**

> Suggested sequence (you can change it inside the notebook): `H P H H P H`

## How to use in Google Colab
1. Upload this notebook to your Google Drive or GitHub.
2. Open it in Colab (File → Open notebook → GitHub or Drive).
3. Run cells from top to bottom. Figures will be saved in a `figures/` subfolder.

> Optional: If you publish to GitHub, add a Colab badge in your README like:
>
> `[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_NOTEBOOK_LINK_HERE)`

## Local Setup
```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```
Then open `HP_Day1_HP_Model.ipynb`, run all cells.

## Files
- `HP_Day1_HP_Model.ipynb` — The main notebook
- `requirements.txt` — Minimal dependencies
- `figures/` — Auto-created when you run; plots will be saved here

## License
MIT (or choose your preferred license).


## Notebooks
- `HP_Day1_TODO.ipynb` — Guided version with TODOs + tests
- `HP_Day1_HP_Model.ipynb` — Reference/baseline version
