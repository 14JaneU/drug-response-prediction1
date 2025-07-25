# Drug Response Prediction Using Public Datasets
This project uses machine learning to predict Drug Sensitivity (IC50 values) in Cancer Cell Lines using Genomic Features such as gene expression and mutation data. The goal is to explore patterns in cancer pharmacogenomcis and build a predictive model using publicly available datasets. 

## Project Goals
- Download and clean drug response and gene expression data
- Train ML models to predict sensitivity to selected drugs
- Evaluate performance and visualize insights
- Share findings in a reproducible, well-documented notebook

## Data Sources
- [GDSC - Genomics of Drug Sensitivity in Cancer](https://www.cancerrxgene.org/)
- [CCLE - Cancer Cell Line Encyclopedia](https://portals.broadinstitute.org/ccle)

## Project Structure
```
drug-response-prediction/
│
├── data/              # Raw and processed datasets
├── notebooks/         # Jupyter notebooks
├── src/               # Scripts for data cleaning and modeling (optional)
├── README.md          # This file
└── .gitignore         # Files/folders to ignore in version control
```
## Tools Used
- Python (pandas, scikit-learn, matplotlib, seaborn)
- Jupyter Notebook / Google Colab
- GitHub
## License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
