# ML Projects

A personal collection of machine learning (ML) projects performed through Kaggle competitions.

Each project lives in its own subfolder with its own data, notebooks, and notes.
The repo grows as new competitions and datasets are explored.

## Prerequisites

Software tools needed to be installed:

- Git
- Python
- Pip
- Kaggle CLI
- Python & Jupyter VS Code extension
- `ipykernel` in `venv`

## Repository Structure

```
ml-projects/
├── README.md                  
├── .gitignore  
└── titanic/ 
    ├── .gitkeep                 
    ├── README.md
    ├── data/  
    └── titanic.ipynb      
```

## Projects

| # | Project | Type | Status |
|---|---------|------|--------|
| 1 | Titanic | Classification | 🚧 In Progress |

## General workflow

1. Create new folder within the repository and navigate the terminal to it
2. `kaggle auth login` to log into Kaggle
3. `kaggle competitions download -c competition_name -p ./data` to download zip file with source files
4. `unzip ./data/.zip -d ./data` to unzip the file in data folder
5. Create new notebook (`.ipynb`) and start coding