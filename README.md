# House Price Prediction

Data science coursework exploring house sale prices with pandas, scikit-learn, Matplotlib and Seaborn. The notebooks cover missing-value handling, exploratory analysis, categorical encoding, Linear Regression, Ridge, Lasso and K-Means clustering.

## Project files

| File | Purpose |
|---|---|
| [House_Price_Prediction.ipynb](House_Price_Prediction.ipynb) | Sectioned notebook with explanations and model comparisons |
| [dataScience.ipynb](dataScience.ipynb) | Analysis notebook containing saved execution outputs |
| [train.csv](train.csv) | Housing data, including the `SalePrice` target |
| [House_Price_Report_Badr_1.pdf](House_Price_Report_Badr_1.pdf) | Project report |
| PNG files | Exported charts and screenshots |

## Run locally

Python and Jupyter Notebook are required. Install the libraries used by the notebooks:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn notebook
jupyter notebook
```

Open either notebook from your downloaded copy of this repository. Both notebooks load `train.csv` using a relative path. Keep the notebook and CSV in the same folder and run cells in order.

## Notes

- The notebooks are related versions of the analysis, not separate deployed applications.
- The saved results belong to the recorded analysis. No fresh benchmark or package-version compatibility check is claimed here.
- The repository does not include a web app, prediction API or pinned dependency file.

## Example chart

![Sale price distribution](Sale%20Price%20Distribution.png)
