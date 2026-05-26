# Deutsch–Jozsa Algorithm — Notebooks

This repository contains Jupyter notebooks that demonstrate the Deutsch–Jozsa quantum algorithm and simple variations for learning and experimentation.

## Contents

- `dj_algorithm.ipynb` — Primary notebook implementing the Deutsch–Jozsa algorithm; designed to run locally using a classical simulator (no cloud account required).
- `dj_algorithm copy.ipynb` — Variant configured to connect to IBM Quantum backends for running on real devices or IBM simulators (requires Qiskit and an IBMQ account/token).

## Requirements

- Python 3.8+ recommended
- Jupyter Notebook or JupyterLab
- Typical Python packages: `numpy`, `matplotlib`, and a quantum SDK such as `qiskit` (if running on a quantum simulator or real backend)

You can create a virtual environment and install common dependencies with:

```bash
python -m venv .venv
.
# Windows
.venv\Scripts\activate
# macOS / Linux
source .venv/bin/activate
pip install --upgrade pip
pip install jupyterlab numpy matplotlib qiskit
```

If you prefer, create a `requirements.txt` with the exact pinned versions used in your environment.

## Usage

1. Open Jupyter Lab or Notebook in the repository root:

```bash
jupyter lab
```

2. Open `dj_algorithm.ipynb` and run the cells. The notebooks include explanatory text cells and runnable code cells that illustrate how the algorithm works on classical simulation and (optionally) on Qiskit's simulators/backends.

3. If using Qiskit with real IBM backends, follow Qiskit's authentication instructions to configure your API token. Note: `dj_algorithm copy.ipynb` is preconfigured to use IBM Quantum — install `qiskit-ibm-provider` and authenticate with your IBMQ token (e.g. via `IBMQ.save_account('MY_TOKEN')` or `IBMQ.load_account()`).

## Notes

- The notebooks are educational and meant for interactive exploration. They include comments and descriptive markdown cells to guide the reader.
- If you want me to add a `requirements.txt`, example scripts, or convert notebooks to polished HTML slides, tell me which option you'd like.

## Author

- Created for a personal demonstration of the Deutsch–Jozsa algorithm.

## License

- Specify a license if you plan to share the repository publicly (MIT is a common default).

