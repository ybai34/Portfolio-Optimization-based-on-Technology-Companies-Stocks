# Portfolio-Optimization-based-on-Technology-Companies-Stocks
This is the final project of DSCC 435 Optimization for Machine Learning course, 2023 Fall, University of Rochester.

This repository contains a collection of files for financial data analysis, portfolio optimization, and related documentation. Below is an overview of the purpose of each item:

## Project Structure

This repository is organized into several directories, each with a specific purpose in the project workflow:

### [Code](./Code)
Contains all Jupyter notebooks used for financial analysis and portfolio optimization.

- `Data_Analysis.ipynb`: Performs initial data cleaning and exploratory analysis.
- `Markowitz_Max_Sharpe.ipynb`: Optimizes portfolio for maximum Sharpe ratio.
- `Markowitz_companies_mean.ipynb`: Calculates mean returns for portfolio companies.
- Multiple notebooks for minimizing risk with different constraints.
- `Plot.ipynb`: Visualizes optimization results and financial data.
- `prox_2020.ipynb`: Applies Proximal Gradient Method with specific stock constraints.
- `risk_parity.ipynb`: Aims to achieve a risk parity portfolio.

Detailed information can be found in the [Code README](./Code/README.md).

### [Data](./Data)
Houses the dataset used for analysis in CSV format.

- `data.csv`: Contains 25,161 rows of stock market data from NASDAQ for companies like Apple, Microsoft, Meta, and others.

For more details, see the [Data README](./Data/README.md).

### [Report](./Report)
Includes all documentation and presentation materials for the project.

- `proposal.pdf`: Initial project proposal document.
- `report.pdf`: Final comprehensive report of the project.
- `slides.pptx`: Presentation slides summarizing the project.

Refer to the [Report README](./Report/README.md) for more information.

### Root Directory
The root directory contains this README and the LICENSE file.

## Data Source
The data for this project has been sourced from a publicly available dataset on Kaggle, which can be found [here](https://www.kaggle.com/datasets/khushipitroda/stock-market-historical-data-of-top-10-companies/).

## Contributing
Contributions are welcome! If you have suggestions or want to improve the project, please feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file in the [Report](./Report) directory for details.

---

Thank you for visiting this repository, and we hope the resources provided will be valuable in your quest for portfolio optimization.
