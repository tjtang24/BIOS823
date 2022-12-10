# Fall 2022 BIOS823 Final Project

## Overview

This is the repository for the Duke BIOS 823 Final Project (by TJ Tang). The topic for this project is to compare different machine learning / deep learning methods for image classifications.

## Dependencies (Python 3)

```
pip install -r requirements.txt
```

## Usage

The final report `Report.pdf` is fully reproducible from the Jupyter Notebook and LaTeX document by following the below steps:

- Create a `tables/` folder for `.csv` tables to be included in the report
- Create a `figure/` folder for `.png` figures to be included in the report
- Run `BIOS823_Final.ipynb`, which contains all necessary codes to generate results, tables, and figures for the report. The tables will be saved in the `tables/` folder, and the figures will be saved in the `figures/` folder. (`BIOS823_Final.pdf` is the pdf output for the Jupyter Notebook.)
- Compile `Report.tex`, which generates `Report.pdf` as the main report for this project.

## Other files

- `aaai23.bib`: bibliography in BibTeX
- `aaai23.sty`: LaTeX style
- `aaai23.bst`: bibliography style  
Note: The LaTeX template is from https://www.aaai.org/Publications/Templates/AuthorKit23.zip.


