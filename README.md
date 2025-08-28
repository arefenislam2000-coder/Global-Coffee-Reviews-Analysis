# ☕ Global Coffee Bean Analysis

This project provides a deep, data-driven exploration of the global specialty coffee market, using web scraping, data cleaning, transformation, and visualization. The goal is to extract insightful trends on coffee origins, roast levels, ratings, prices, and flavor profiles, offering value to both coffee enthusiasts and industry professionals. It also provides a reproducible workflow for coders and data scientists.

---

## Tools & Environment

- **Python (Google Colab)**: For data collection, cleaning, and analysis.
- **Pandas**: For data manipulation and transformation.
- **re (Regular Expressions)**: For extracting price, quantity, and currency.
- **Tableau**: For creating interactive dashboards for visualization.

**View the Interactive Dashboard:** [Tableau Public](https://public.tableau.com/app/profile/arefen.islam/viz/Global_Coffee_Beans_Analysis/Overview)

---

## Key Analysis Performed

1.  **Coffee Origins**: Count of varieties and average ratings.
2.  **Roast Levels**: Distribution, average sensory scores, and ratings.
3.  **Producing Countries & States**: Top performers by average rating.
4.  **Single Origin vs. Blends**: Comparison of quality and price.
5.  **Price Analysis**: Correlation between roast level, origin, and price.
6.  **Value Analysis**: Relationship between high price and high ratings.
7.  **Popularity**: Most frequently reviewed coffee beans.
8.  **Top Performers**: Identification of the highest-rated beans.

---

## Research Findings

### 1. Coffee Origins & Countries

-   **Most Prolific Origins (by number of reviews)**:
    -   **Huila Department, Colombia**: 265 reviews (Avg Rating: 93.47)
    -   **Sidamo, Southern Ethiopia**: 240 reviews (Avg Rating: 94.21)
    -   **Guji Zone, Oromia, Ethiopia**: 200 reviews (Avg Rating: 93.55)
-   > **Insight**: **Sidamo, Ethiopia** emerges as a top-tier origin, balancing a high number of reviews with the highest average rating among the leaders.

-   **Top Roaster Countries (by average rating)**:
    -   **Taiwan**: Avg Rating: 93.52
    -   **USA**: Avg Rating: 93.20

-   **Top Roaster States (by average rating)**:
    -   **Hawai’i, USA**: Avg Rating: 95.06
    -   **Chia-Yi County, Taiwan**: Avg Rating: 94.20

### 2. Roast Level Insights

-   **Distribution of Roasts**:
    -   **Light**: 47.3%
    -   **Medium-Light**: 45.3%
    -   **Medium**: 5.1%
-   > **Insight**: The specialty market overwhelmingly prefers lighter roasts to preserve the bean's original flavors.

-   **Roast vs. Quality**:
    | Roast Level | Avg. Sensory Score | Avg. Rating |
    | :---------- | :----------------- | :---------- |
    | Light | 8.75 | 93.76 |
    | Medium-Light| 8.61 | 93.14 |
    | Medium | 8.29 | 91.68 |
-   > **Insight**: **Lighter roasts consistently receive higher ratings** and sensory scores.

### 3. Single Origin vs. Blend

-   **Quality Comparison**:
    -   **Blends**: Avg. Sensory Score: 8.70, Avg. Rating: 93.54
    -   **Single Origins**: Avg. Sensory Score: 8.32, Avg. Rating: 91.74
-   > **Insight**: **Blends slightly outperform single origins** in both sensory scores and overall ratings in this dataset.

-   **Price Insights**:
    -   Blends are generally more expensive than single origins across most roast levels.

### 4. Price & Value Analysis

-   **Most Expensive Coffees**:
    -   **Paso Ancho, Panama**: ~$2500/100g (Medium-Light roast)
    -   **Boquete Region, Panama**: ~$2000/100g (Light roast)
-   > **Insight**: **Panama Geisha** coffees dominate the ultra-premium market segment.

-   **Price vs. Quality**:
    -   While the most expensive coffees can achieve top-tier scores (e.g., a $1272/100g coffee scored a 98), high quality is **not always tied to extreme prices**. For instance, a coffee priced at $293/100g also scored a 97.

### Exceptional Finding: Kahiko Orange – A Game Changer

The analysis uncovered a remarkable outlier:

-   **Coffee**: **Kahiko Orange (Blend)**
-   **Rating**: **98** (tied for the highest in the dataset)
-   **Sensory Score**: **9.6**
-   **Price**: **$44/100g**
-   > **Conclusion**: This coffee proves that **world-class quality can be achieved at an affordable price point**, challenging the common assumption that top-tier coffee must be prohibitively expensive.

---

## Overall Conclusion

1.  **Best Origin**: **Sidamo, Ethiopia** stands out for its high ratings and popularity.
2.  **Preferred Roast**: **Light roasts** are the clear favorite for quality and preference.
3.  **Best Type**: **Blends** show a slight edge over single origins in sensory scores and ratings.
4.  **Price & Quality**: Price is **not a reliable standalone indicator of quality**. While premium coffees are expensive, exceptional value exists.
5.  **Market Leader**: **Panama Geisha** coffees define the luxury end of the market.
6.  **Key Takeaway**: The discovery of **Kahiko Orange** highlights that exceptional quality can be accessible, disrupting traditional market views.

---

## How to Reproduce This Analysis

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/arefenislam2000-coder/Global-Coffee-Reviews-Analysis.git
    cd Global-Coffee-Reviews-Analysis
    ```

2.  **Run the Notebooks in Google Colab**:
    -   `Notebook/CoffeeReview_WebScraping.ipynb` (for web scraping )
    -   `Notebook/CoffeeReviews_DataProcessing_Transformation_Manipulation.ipynb` (for data cleaning)

3.  **Explore the Cleaned Dataset**:
    -   The final dataset is available at `Data/coffee_reviews_cleaned.csv`.

4.  **Visualize the Insights**:
    -   Open the files in the `Tableau` folder to view the interactive dashboards.

---

## Credits

-   **Data Source**: [CoffeeReview.com](https://www.coffeereview.com/ )
-   **Developed by**: [arefenislam2000-coder](https://github.com/arefenislam2000-coder )
