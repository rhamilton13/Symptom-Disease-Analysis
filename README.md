# Symptom-Disease Analysis

This project explores patterns in a medical dataset that maps various diseases to their associated symptoms. The goal was to better understand which symptoms appear most frequently, how symptoms vary between diseases, and which symptoms tend to occur together. This kind of analysis can help lay the groundwork for diagnostic models or decision support tools.

## Overview

- Cleaned and explored a real-world categorical dataset of symptoms and diseases
- Identified the top 20 most common symptoms across all records
- Analyzed the five most frequent symptoms for each disease
- Created a heatmap showing symptom co-occurrence (i.e., which symptoms appear together most often)
- Added scrollable views for long tables and used visualizations to make patterns easier to interpret

## Tools Used

- Python (Jupyter Notebook)
- pandas
- matplotlib
- seaborn
- scikit-learn (`MultiLabelBinarizer` for heatmap prep)

## Key Visualizations

- **Bar chart** showing the top 20 most frequently occurring symptoms
- **Heatmap** of symptom co-occurrence to highlight symptom clusters
- **Scrollable table** of top symptoms per disease for cleaner notebook presentation

## Key Takeaways

- A few symptoms (like fatigue, vomiting, and weight loss) appear across many different diseases
- Some symptoms are highly correlated and tend to appear together
- The dataset lends itself well to further work like classification modeling or dashboarding in tools like Power BI

## Next Steps (Optional Ideas)

- Build a classifier to predict disease based on symptoms
- Create an interactive dashboard for symptom filtering
- Incorporate severity levels or symptom duration if available

---

This project was built to demonstrate real-world data cleaning, analysis, and visualization techniques using Python. It’s meant to show how structured data can be explored and presented in a clear, accessible format.
