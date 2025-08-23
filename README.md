# Global Coffee Reviews Analysis

This project explores global specialty coffee reviews using **web scraping, data cleaning, and data visualization**.  
The workflow covers scraping raw data, transforming it into a structured dataset, and creating **interactive Tableau dashboards** to analyze insights on coffee origins, roast levels, ratings, prices, and flavor profiles.

---



## ⚙️ Python Environment and Packages

The project was developed in **Google Colab**.

### Required Libraries
```python
import pandas as pd
import re
from google.colab import files
````

### Package Usage

* **`google.colab`**

  * Upload/download files in Colab (`from google.colab import files`).

* **`pandas`**

  * Functions: `read_csv()`, `head()`, `drop_duplicates()`, `isnull().sum()`,
    `fillna()`, `apply()`, `to_datetime()`, `to_csv()`, `corr()`
  * Used for data cleaning, manipulation, and analysis.

* **`re` (Regular Expressions)**

  * Extracts price, quantity, and currency from strings:

    ```python
    match = re.search(r"(\$|NT\$|RMB|£|RM|HK\$)?(\d+\.?\d*)/(\d+\.?\d*)(oz|ounces|g|grams|kilogram|kg|capsules)?", price_str, re.IGNORECASE)
    ```

---

## 📊 Key Analyses

1. Coffee origins that produce the maximum beans
2. Distribution of roast levels
3. Roast level vs. average rating / sensory score
4. Top coffee-producing countries by average rating
5. Top coffee-producing states
6. Single origin vs blends
7. Correlation: Roast level vs price
8. Most expensive coffee combinations (Origin × Roast Level)
9. Price comparison: Single origin vs blends
10. Most reviewed coffee beans
11. Do expensive coffees really score higher?
12. The most expensive coffee beans
13. Top rated coffee beans

---

## ▶️ How to Run

1. **Clone the repo**

   ```bash
   git clone https://github.com/arefenislam2000-coder/Global-Coffee-Reviews-Analysis.git
   cd Global-Coffee-Reviews-Analysis
   ```

2. **Open Notebooks in Google Colab**

   * `Notebook/CoffeeReview_WebScraping.ipynb` → Scrape raw data
   * `Notebook/CoffeeReviews_DataProcessing_Transformation_Manipulation.ipynb` → Clean & transform data

3. **Install required packages (if needed)**

   ```bash
   !pip install pandas
   ```

4. **Explore the cleaned dataset**

   * Located in the `Data` folder.

5. **Visualize insights in Tableau**

   * Open files in the `Tableau` folder.

---

## 📝 Notes

* Dataset includes calculated fields like **price per 100g**, **average sensory score**, and **normalized roast levels**.
* Tableau dashboards include filters for **year, roast level, origin type, and rating**.
* Focus: **specialty coffee trends, price-value analysis, and flavor profiling** across global origins.

---

## 🙌 Credits

* **Data Source:** [CoffeeReview.com](https://www.coffeereview.com/)
* **Developed by:** [arefenislam2000-coder](https://github.com/arefenislam2000-coder)

---

```

---



