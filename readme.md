# Google Play Store Analysis 📱

## 📌 Project Overview

This project explores the Google Play Store app market to uncover insights into app categories, ratings, installations, pricing, and user sentiment.

Using Python data analysis libraries, the project applies data cleaning, exploratory data analysis (EDA), statistical summaries, and data visualization to identify patterns and generate actionable recommendations for app developers.

## 🎯 Objectives

- Clean and prepare the datasets for analysis.
- Explore app categories, ratings, and installation counts.
- Compare free and paid applications.
- Analyze app pricing and estimated revenue.
- Investigate user review sentiment.
- Compare positive, negative, and neutral sentiment across app categories.
- Provide data-driven insights to support app development decisions.

## 🛠️ Tools & Technologies

- **Python** — Data analysis and preprocessing
- **Pandas** — Data manipulation and cleaning
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Jupyter Notebook** — Interactive analysis environment

## 📂 Project Structure

```text
Google-Play-Store-Analysis/
│
├── data/
│   ├── googleplaystore.csv
│   └── googleplaystore_user_reviews.csv
├──screenshots
├── playstoreanalysis.ipynb
└── README.md
```

_Note: The filenames and folder structure above represent the expected project organization. Adjust them if your actual repository differs._

## 📊 Analysis Performed

### 1. Data Cleaning and Preprocessing

- Inspected dataset structure and data types.
- Identified and removed duplicate app records.
- Handled data quality issues in app ratings.
- Examined missing values and prepared relevant columns for analysis.

### 2. Exploratory Data Analysis

- Examined app distributions across categories.
- Analyzed app ratings and installation counts.
- Investigated pricing differences between free and paid apps.
- Compared app categories using visualizations.

### 3. Pricing Analysis

- Compared free and paid applications.
- Explored the distribution of paid app prices.
- Estimated potential revenue by category using app prices and installation counts.

### 4. User Sentiment Analysis

- Analyzed existing positive, negative, and neutral review labels.
- Calculated the percentage distribution of user sentiment.
- Compared sentiment percentages across app categories.
- Identified categories with relatively high positive and negative sentiment.

## 🔍 Key Findings

- **Positive sentiment dominated:** 64.04% of analyzed reviews were positive, while 21.29% were negative and 14.67% were neutral.
- **Highest positive sentiment:** The COMICS category recorded the highest positive sentiment percentage at 86.67%.
- **Highest negative sentiment:** The GAME category recorded the highest negative sentiment percentage at 35.47%.

These findings describe the analyzed datasets and should not be interpreted as representative of every app or user on Google Play.

## 💡 Business Recommendations

1. **Study successful categories:** Investigate apps in categories with high positive sentiment to understand which features and user experiences customers appreciate.
2. **Address user dissatisfaction:** Examine negative reviews in categories such as GAME and SOCIAL to identify recurring usability, performance, or functionality issues.
3. **Evaluate market opportunities carefully:** Combine sentiment analysis with competition, ratings, installation counts, pricing, and development costs before choosing a category for a new app.

## ⚠️ Limitations

- Missing values and data quality issues may affect some analyses.
- Installation counts are presented as rounded ranges, so revenue estimates are approximate rather than actual earnings.
- Sentiment findings depend on the available review sample and its existing sentiment labels.
- Not every review could be matched to an app category, so unmatched reviews were excluded from category-level sentiment comparisons.
- Observed patterns do not establish causation or guarantee future app success.

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Ensure the CSV datasets are placed in the correct `data/` directory.
4. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `playstoreanalysis.ipynb` and run the cells in order.

## 👨‍💻 Author

**Majd Zouaoui**

Data Analytics | Python | Exploratory Data Analysis

## 📄 License

This project is intended for educational and analytical purposes. Refer to the original dataset source for its licensing and usage conditions.
