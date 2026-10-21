# CL2 — Computational Lab II

SPPU BE AIDS Computational Lab II practicals.

## Contents

### Bioinformatics
- **Assignment 1** — Python script + Dockerfile
- **Assignment 2** — RNA analysis (`rna_analysis.py`, `rna.csv`) + Dockerfile

### Information Retrieval
- **Assignment 1** — Notebook
- **Assignment 2** — Notebook
- **Assignment 3** — Spam/Ham classification (`spam_ham_dataset.csv`)
- **Assignment 4** — Clustering on mall customers (`Mall_Customers.csv`)
- **Assignment 5** — Notebook

## Setup

```bash
pip install numpy pandas matplotlib seaborn scikit-learn nltk jupyter
jupyter notebook
```

The Bioinformatics assignments include Dockerfiles, e.g.:

```bash
cd "Bioinformatics/Assignment 1"
docker build -t cl2-bioinfo-a1 .
docker run --rm cl2-bioinfo-a1
```

## Source

Extracted from [Zade907/SPPU-BE-AIDS-LabPracticals](https://github.com/Zade907/SPPU-BE-AIDS-LabPracticals).
