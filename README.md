# Wind SCADA Analysis

- Created by Francisco Salas
- version: 0.1.0
- Date: 2021-02-03
- username : franksalas

## Description
An analysis of wind turbine SCADA dataset from kaggle

## Setup environment
Create enviroment from file
```bash
conda env create -f environments/base_environment.yml
```
## Activate environment

```bash
conda activate scada
```

## Update environment

```bash
$ conda env update --prefix ./env --file environment.yml  --prune

pip freeze > requirements.txt
```
## Folder Structure
```
.
├── data
│   ├── final
│   ├── interim
│   └── raw
├── environments
│   ├── base_environment.yml
│   └── README.md
├── notebooks
│   └── EXAMPLES.ipynb
├── notes
├── README.md
├── report
│   └── graphs
└── src
    └── start.py

```