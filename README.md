
# Financial dataset
## 📊 Dataset Description

This dataset contains quarterly financial statement data for various U.S. companies, structured to support classification, clustering, and regression tasks in financial machine learning and data analysis.

### 🧾 Columns Explanation

| Column Name     | Description                                                                           |
| --------------- | ------------------------------------------------------------------------------------- |
| `name`          | The legal name of the company.                                                        |
| `sic`           | Standard Industrial Classification (SIC) code indicating the company's industry.      |
| `stprinc`       | The principal U.S. state (or Canadian province) where the company is registered.      |
| `Year`          | The year in which the financial data was reported.                                    |
| `Quarter`       | The fiscal quarter (1 to 4) in which the data was reported.                           |
| `Assets`        | Total assets held by the company at the end of the quarter (in USD).                  |
| `Liabilities`   | Total liabilities at the end of the quarter (in USD).                                 |
| `NetIncomeLoss` | The net income or loss reported for the quarter (in USD).                             |
| `Revenues`      | Total revenue generated during the quarter (in USD).                                  |
| `ProfitMargin`  | The ratio of net income to revenue. Calculated as `NetIncomeLoss / Revenues`.         |
| `DebtRatio`     | The ratio of total liabilities to total assets. Calculated as `Liabilities / Assets`. |
| `ROA`           | Return on Assets. Calculated as `NetIncomeLoss / Assets`.                             |
| `Label`         | Binary profitability label: `1` if profitable (positive NetIncome), `0` otherwise.    |

### 📌 Notes

* The financial values are expressed in absolute U.S. dollars.
* The dataset includes companies from various industries and regions, identified by `sic` and `stprinc` respectively.
* This dataset can be used for tasks such as:

  * **Classification** (e.g., predicting profitability)
  * **Clustering** (e.g., grouping companies based on financial health)
  * **Regression** (e.g., predicting revenues from financial metrics)



اگر بخوای همین متن رو به فارسی هم داشته باشی برای مستندسازی داخلی، فقط بگو.
