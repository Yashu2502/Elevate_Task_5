# Exploratory Data Analysis (EDA)

## Missing Value Handling
- **Numerical columns:** Missing values were replaced with the median to avoid the influence of outliers.
- **Categorical columns:** Missing entries were filled with the most frequently occurring (mode) value for each column.

## EDA Process
- Explored the overall structure of the data using `.info()` and `.describe()` to understand its composition.
- Visualized feature distributions using **histograms** and **boxplots** to spot trends and unusual patterns.
- Identified and examined outliers present in the numeric features.
- Studied the relationships between different features through **pairplots** and a **correlation heatmap**.

## Key Insights
- **Age** and **Income** stand out as major factors influencing customer purchase behaviors.
- Some **product categories** dominate the sales, indicating customer preferences.
- Several features show strong interconnections, offering valuable opportunities for predictive modeling.

## Conclusion
- The dataset has been thoroughly cleaned without losing any records.
- It is fully prepared for the next stages of predictive modeling and deeper business analysis.
