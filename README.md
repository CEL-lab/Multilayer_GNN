# Multilayer_GNN
# Multilayer Graph Neural Networks for Grid Resilience

This repository contains the code and resources associated with the research paper **"Multilayer Graph Neural Networks for Enhancing Grid Resilience"**.

## Overview

We utilize incident data from OGE to construct a multilayer network representation of power grid infrastructure. Multilayer Graph Neural Networks (GNNs) are employed to address practical tasks to enhance grid resilience, including:

- **Predictive Maintenance**: Identifying substations requiring urgent maintenance.
- **Incident Classification**: Categorizing incidents by type or severity.
- **Substation Clustering**: Grouping substations based on similarity to inform targeted interventions.
- **Risk Assessment (Regression)**: Estimating incident risk levels for proactive management.

## Repository Structure

```
multilayer-gnn-grid-resilience/
├── data/                  # Dataset (OGE incident data, anonymized/synthetic)
├── models/                # Multilayer GNN model implementations
├── notebooks/             # Jupyter notebooks demonstrating workflows
├── scripts/               # Training and evaluation scripts
├── results/               # Experimental results and performance metrics
├── requirements.txt       # Python dependencies
└── LICENSE                # Repository license
```

## Requirements

- Python >= 3.8
- PyTorch
- PyTorch Geometric
- NetworkX
- Scikit-learn
- NumPy, Pandas

Install required packages:
```bash
pip install -r requirements.txt
```

## Quick Start

Clone the repository:
```bash
git clone https://github.com/your-username/multilayer-gnn-grid-resilience.git
cd multilayer-gnn-grid-resilience
```

Run the example notebook:
```bash
jupyter notebook notebooks/Example_Workflow.ipynb
```

## Citation

If you use this work in your research, please cite:

```bibtex
@article{yourname2024multilayer,
  title={Multilayer Graph Neural Networks for Enhancing Grid Resilience},
  author={Your Name and Collaborators},
  journal={Journal/Conference Name},
  year={2024},
}
```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
