# Gadget Sales: Pandas Filtering & Sorting Practice

A beginner-friendly practice project where I solve a question bank on a gadget sales dataset using **Python and Pandas**. The focus is on filtering rows and sorting results in different ways.

## Files

| File | Description |
|------|-------------|
| `gadget_sales.csv` | The dataset (500 orders, 13 columns) |
| `Gadgets_Practice.ipynb` | Jupyter Notebook with all questions and my solutions |

## About the Dataset

The dataset contains gadget orders placed between **January 2024 and May 2025** across 6 store locations (Tokyo, Sydney, Berlin, London, Mumbai, New York).

| Column | Description |
|--------|-------------|
| `Order_ID` | Unique ID of the order |
| `Order_Date` | Date the order was placed |
| `Product_Category` | Accessories, Gaming, Smart Home, Wearables, Audio |
| `Product_Name` | Name of the product |
| `Quantity_Ordered` | Number of units ordered |
| `Unit_Price` | Price of one unit (in $) |
| `Store_Location` | Store where the order was placed |
| `Payment_Method` | Debit Card, Credit Card, PayPal, Crypto |
| `Customer_Rating` | Rating given by the customer (26 values are missing) |
| `Is_Express_Shipping` | `True` if express shipping was used |
| `Discount_Percent` | Discount given on the order (for example 0.10 = 10%) |
| `Return_Status` | No Return, Pending, Completed |
| `Warehouse_Code` | Warehouse that fulfilled the order (WH-1 to WH-5) |

## Topics Covered

1. **Basic Filtering & Sorting**: single-condition filters with `sort_values()`
2. **Multi-Criteria Filtering**: AND / OR logic using `&`, `|`, `isin()` and `between()`
3. **Advanced Sorting**: multi-level sorting with mixed ascending/descending order
4. **Date-Based Filtering**: `pd.to_datetime()` and the `.dt` accessor (month, year, date ranges)
5. **Calculated & String Filtering**: new calculated columns, `str.contains()`, and handling missing values with `isna()`

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/jkartik28/pandas-gadget-sales-practice.git
   ```
2. Install the requirements:
   ```bash
   pip install pandas jupyter
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Gadgets_Practice.ipynb
   ```

> **Note:** Keep `gadget_sales.csv` in the same folder as the notebook, and run the cells from top to bottom, because some cells depend on earlier ones (for example, the date conversion in Section 4).

## Tools Used

- Python
- Pandas
- Jupyter Notebook

## Author

**Kartik**
GitHub: [@jkartik28](https://github.com/jkartik28)