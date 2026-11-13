# XRL-MODAL: Adaptive Intermodal Cold-Chain Transportation

An Explainable Multimodal Reinforcement Learning framework for adaptive intermodal cold-chain transportation across India. The project integrates heterogeneous transportation, weather, freight, cold-chain, and IoT datasets to develop intelligent, interpretable, and sustainable logistics optimization strategies.

## Project Overview

**XRL-MODAL** aims to investigate and develop explainable multimodal reinforcement learning approaches for optimizing intermodal cold-chain transportation.

The framework leverages heterogeneous datasets representing different transportation and environmental factors to support adaptive decision-making, efficient logistics planning, and improved cold-chain operations.

### Key Objectives

- Integrate heterogeneous multimodal transportation and logistics datasets.
- Develop reinforcement learning models for adaptive intermodal transportation.
- Optimize cold-chain transportation and logistics decision-making.
- Incorporate explainable AI techniques to interpret model decisions.
- Compare different reinforcement learning approaches and evaluate their performance.
- Promote efficient, resilient, and sustainable transportation operations.

## Project Guidelines

Follow the instructions below to configure the development environment and execute the project.

### 1. Install Astral UV

Install [Astral UV](https://docs.astral.sh/uv/getting-started/installation/), a fast Python package and project manager.

### 2. Navigate to the Project Directory

Open a terminal and navigate to the cloned repository:

```bash
cd <PROJECT_FOLDER_PATH>
```

### 3. Create a Virtual Environment

Create a virtual environment using Python 3.10:

```bash
uv venv --python=3.10
```

### 4. Activate the Virtual Environment

For Linux/macOS:

```bash
source .venv/bin/activate
```

For Windows (PowerShell):

```powershell
.venv\Scripts\Activate.ps1
```

### 5. Install Project Dependencies

Install the dependencies specified in `pyproject.toml` and synchronized through `uv.lock`:

```bash
uv sync
```

**Note:** `uv sync` installs the dependencies declared in the project configuration. There is no need to run `uv pip install -r pyproject.toml`, as `pyproject.toml` is not a requirements file.

### 6. Download the Dataset

Download the project dataset from Kaggle:

**Dataset:** [Multimodal Supply Chain Dataset](https://www.kaggle.com/datasets/debarghamitraroy/multimodal-supply-chain-dataset)

Extract the downloaded dataset into the project's `data/` directory.

Ensure that the dataset directory structure and filenames match the paths expected by the notebook.

## Project Structure

The repository is organized to support modular dataset processing, multimodal data integration, and reinforcement learning experimentation.

```text
XRL-MODAL/
│
├── data/
│   └── Dataset files and subdirectories
│
├── .venv/
│   └── Python virtual environment
│
├── code.ipynb
│   └── Main project implementation
│
├── pyproject.toml
│   └── Project configuration and dependencies
│
├── uv.lock
│   └── Dependency lock file
│
├── .python-version
│   └── Python version specification
│
├── .gitignore
│   └── Git exclusion rules
│
└── README.md
    └── Project documentation
```

## Execution

After completing the environment setup and downloading the dataset:

1. Activate the project virtual environment.
2. Open `code.ipynb` using Jupyter Notebook or JupyterLab.
3. Execute the notebook cells sequentially.
4. Follow the dataset validation and preprocessing stages.
5. Execute the multimodal reinforcement learning implementation and model evaluation stages.

## Technology Stack

- **Programming Language:** Python 3.10
- **Package Management:** Astral UV
- **Development Environment:** Jupyter Notebook
- **Machine Learning:** Python-based machine learning and reinforcement learning libraries
- **Data Processing:** Pandas, NumPy
- **Explainability:** Explainable AI techniques

## Dataset and Data Sources

The project primarily focuses on multimodal transportation and cold-chain logistics datasets relevant to the Indian transportation ecosystem.

The datasets support the integration and analysis of transportation networks, weather conditions, freight movement, cold-storage infrastructure, and IoT-based supply-chain information.

**Primary Dataset Repository:** [Kaggle – Multimodal Supply Chain Dataset](https://www.kaggle.com/datasets/debarghamitraroy/multimodal-supply-chain-dataset)

## Project Status

**Development and experimentation in progress.**

## License

License information will be added as the project evolves.
