
# 📊 Superstore Sales and Profit Analysis (Jupyter Notebook)

This project analyzes sales and profit data from the **Sample - Superstore** dataset using **Pandas** and **Plotly** inside a **Jupyter Notebook**. It includes interactive charts and visual insights across time, categories, and customer segments.

---

## 📁 Dataset

- **File:** `Sample - Superstore.csv`  
- **Source:** Public retail dataset (commonly used in data analysis practice)  
- **Records:** 9,994 orders  
- **Columns:** 21 columns (e.g., Order Date, Category, Sales, Profit, Segment, etc.)

---

## 🧰 Tools & Libraries

- `pandas` → Data manipulation and cleaning  
- `plotly.express` → Quick and interactive visualizations  
- `plotly.graph_objects` → Advanced and layered plots  
- `plotly.io` and `plotly.colors` → Global chart theming and styling

---

## 🧪 Key Features

### 🔹 Data Preparation
- Load the CSV with proper encoding
- Convert string dates to datetime format
- Add new columns like **Order Month**, **Order Year**, and **Day of Week**

### 📈 Visualizations Included

| Chart Type         | Insight                                        |
|--------------------|------------------------------------------------|
| Line Chart         | Monthly Sales Trend                            |
| Donut Chart        | Sales by Product Category                      |
| Bar Chart          | Sales by Sub-Category                          |
| Line Chart         | Monthly Profit Trend                           |
| Donut Chart        | Profit by Category                             |
| Bar Chart          | Profit by Sub-Category                         |
| Grouped Bar Chart  | Sales & Profit by Customer Segment             |
| Data Table         | Sales-to-Profit Ratio per Segment              |

---

## 📊 Business Insights

- Which months drive the most revenue and profit?
- What product types contribute most to performance?
- Which customer segment is the most profitable?
- Where is the sales-to-profit ratio most efficient?

---

## ▶️ How to Run This Notebook

1. Clone this repository or download the `.ipynb` notebook and dataset.
2. Make sure `Sample - Superstore.csv` is in the same folder as the notebook.
3. Install required libraries using pip (if not already installed):

```bash
pip install pandas plotly
```

4. Open the Jupyter Notebook:

```bash
jupyter notebook
```

5. Run all cells step-by-step and explore the visual output.

---

## 📂 Project Structure

```
superstore-analysis/
├── Sample - Superstore.csv
├── Superstore_Analysis.ipynb
└── README.md
```

---

## 📬 Contact

For questions or feedback, feel free to open an issue or reach out.

---

✅ This notebook is beginner-friendly and a great addition to a data analyst portfolio!
