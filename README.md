\# CIS480 Semiconductor Market Analysis



\## Project Overview



This academic capstone project analyzes historical performance and risk for five semiconductor companies: AMD, Broadcom (AVGO), Intel (INTC), NVIDIA (NVDA), and Taiwan Semiconductor Manufacturing (TSM), using SPY as a broad-market benchmark.



\*\*Analysis period:\*\* January 2021–December 2025



\*\*Tools:\*\* Python, Jupyter Notebook, pandas, NumPy, yfinance, and Power BI.



\## Research Question



How did the cumulative returns, annualized volatility, and maximum drawdowns of the five selected semiconductor stocks compare with SPY during 2021–2025?



The analysis is descriptive, not predictive.



\## Analytical Measures



\- \*\*Cumulative Return:\*\* Total percentage change over the observation period.

\- \*\*Annualized Volatility:\*\* Sample standard deviation of daily returns multiplied by the square root of 252.

\- \*\*Maximum Drawdown:\*\* Largest percentage decline from a previous running price peak.



\## Reproducibility



Use a compatible Python 3 environment with Jupyter support.



1\. Create and activate a virtual environment.

2\. Install dependencies with `python -m pip install -r requirements.txt`.

3\. Open `notebooks/CIS480\_Final\_Master\_Analysis.ipynb` in Jupyter.

4\. Execute the notebook in order.



The notebook retrieves historical market data through yfinance and saves generated CSV files in the local `outputs/` folder. The folder is excluded from Git.



The notebook was tested in an isolated Python environment with yfinance 1.7.0, pandas 3.1.0, and NumPy 2.5.4. The dependency versions are recorded in `requirements.txt`.



\## Validation Results



The controlled execution completed successfully.



\- 7,530 security-date observations

\- 1,255 trading dates

\- Six securities: AMD, AVGO, INTC, NVDA, TSM, and SPY

\- 15 expected analytical columns

\- Zero missing adjusted closing prices

\- Zero duplicate security-date records

\- All 18 displayed KPI results reconciled with the original project baseline to two decimal places



These results describe the tested execution, not a guarantee that future data downloads will produce identical values.



\## Data Availability and Rights



Historical market data was retrieved using yfinance, which accesses Yahoo Finance data.



Raw and processed historical market-price datasets, generated KPI CSV files, and Power BI files containing embedded data are not distributed in this repository.



Users must obtain data independently and comply with the applicable provider terms. Public availability of financial data does not automatically grant redistribution rights.



Generated CSV files are stored locally in `outputs/` and excluded from Git.



\## Limitations



The study includes five selected semiconductor companies and SPY, which is a broad-market benchmark rather than a semiconductor-sector index. Results depend on the historical observation window, adjusted-price methodology, and source-data revisions.



Historical performance does not predict future returns. This project is for educational purposes and is not investment advice.



\## Project Team



\- Luis Ramirez

\- Rey Guirette

\- Colen Wilson



\## Project Status



Public-release preparation is in progress. The original capstone repository and historical project evidence remain privately preserved.
## License

The original software developed by Luis Ramirez, Rey Guirette, and Colen Wilson for this project is licensed under the MIT License. See the LICENSE file for details.

This license does not apply to third-party historical market data obtained through Yahoo Finance or yfinance. Users are responsible for complying with applicable data-provider terms and permissions. Generated datasets and Power BI files containing embedded market data are not distributed in this repository.