# progesterone-receptor
This repository contains accompanying code for "Prediction of progesterone receptor binding potency, agonism and antagonism using machine learning models" by authors: Nemanja Milosevic, Natasa Sukur Milosevic, Svetlana Fa Nedeljkovic, Bojana Stanic, Nebojsa Andric

# Requirements

We use conda to manage dependencies. To replicate our environment use:

    conda env create -f conda-env.yml

# Structure

```
├── conda-env.yml -> conda environment
├── data -> training and validation data
│   ├── assay_2123.csv
│   ├── assay_2123_smiles.csv
│   ├── assay_2127.csv
│   ├── assay_2127_smiles.csv
│   ├── assay_2222.csv
│   ├── assay_2222_smiles.csv
│   ├── assay_2223.csv
│   ├── assay_2223_smiles.csv
│   ├── assays.csv
│   ├── Chemical list_experiments.csv
│   ├── dataset.csv
│   ├── inference
│   │   ├── 2222.csv
│   │   ├── 2223.csv
│   │   ├── all.csv
│   │   ├── Chemical List EDSP21LIST1-2021-12-28.csv
│   │   ├── Chemical List EDSP21LIST2-2021-12-28.csv
│   │   ├── Chemical List EDSPUOC-2022-06-16.csv
│   │   ├── Chemical list_experiments_with_smiles.csv
│   │   ├── Chemical List OSHA-2021-12-28.csv
│   │   ├── Chemical List UBAPMT-2021-12-28.csv
│   │   └── list1.csv
│   └── PubChem_bioassay_text_'progesterone receptor'.csv
├── model.ipynb -> main script
├── models -> trained models and results
│   ├── conf_matrix_1.csv
│   ├── conf_matrix_2.csv
│   ├── conf_matrix_3.csv
│   └── model_with_oversample_ago.13-0.08.weights.h5 -> model weights
├── README.md
└── requirements.txt -> all Python dependencies frozen versions

```
