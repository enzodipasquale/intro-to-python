# Intro to Python, NumPy, and PyTorch

This repository contains introductory Jupyter notebooks for learning:

- Python data structures and controls
- NumPy arrays and operations
- PyTorch tensors and automatic differentiation

These materials are part of the **Data and Computation** course in the NYU Economics PhD program. 


---

## Setup Instructions

```bash
python3 -m venv myenv
source myenv/bin/activate
pip install -r requirements.txt
python -m ipykernel install --user --name=intro-python --display-name "Intro Python"
```

## Notes

- All required packages are listed in `requirements.txt`.
- If you want to use `torchviz` to visualize computational graphs, you’ll need to install the Graphviz system binary (`dot`) separately.
