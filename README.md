# MedSDoH (Medical Social Determinants of Health)

## Installation Guide

### 1. Clone the Repository

Clone the [project repository](https://github.com/OHNLP/MedSDoH) and navigate to the project directory:

```bash
git clone https://github.com/OHNLP/MedSDoH.git
cd MedSDoH
```

### 2. Set Up a Python Environment

It is recommended to use a [Conda virtual environment](https://docs.conda.io/en/latest/miniconda.html) to prevent conflicts with your existing Python setup.

1. Create a new Conda environment using the provided `environment.yml` file:

   ```bash
   conda env create -f environment.yml
   ```

2. Activate the newly created environment:

   ```bash
   conda activate med_sdoh
   ```

---

## SDoH Category Definitions

Refer to the [SDoH category definitions](https://github.com/OHNLP/MedSDoH/wiki/SDoH-category-definition) for details on the classification used in this study.

---

## Annotation and Results Visualization

For manual annotation or reviewing annotation results, use [MedTator](https://medtator.ohnlp.org/).

---

## Running the SDoH Tagger

Run the SDoH tagger using the provided [Jupyter notebook](https://github.com/OHNLP/MedSDoH/blob/ce84a921b63a89b66fe1c6da0f9e630a4e29fbbf/notebooks/run_model.ipynb).

---
