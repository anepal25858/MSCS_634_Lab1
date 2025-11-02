Lab Summary

Purpose:
    The purpose of this lab was to explore, preprocess, visualize, and analyze the OpenPowerlifting dataset using Python in Jupyter Notebook. The lab focused on understanding relationships between lifters’ body weight, total lifted weight, and performance metrics through data visualization, cleaning, and statistical techniques.

Key Insights:

Visualization Findings:
    >A strong positive relationship was observed between BodyweightKg and TotalKg, indicating that heavier lifters generally lift more total weight.
    >Box plots and histograms revealed the presence of outliers among top-performing athletes and a right-skewed distribution of total lift values.

Statistical Measures:
    >The mean and median of lifting totals were close, suggesting moderate symmetry in the dataset.
    >Correlation analysis showed high correlations among the three main lift types (squat, bench, and deadlift) and their combined total.

Challenges and Decisions:

    >The dataset contained missing values and outliers, which required careful handling using mean imputation and the IQR method.
    >Columns like Wilks, Glossbrenner, and Goodlift caused unrealistic correlation values (>1), so they were excluded from the final correlation analysis.
    >Scaling and discretization needed additional imports (e.g., MinMaxScaler from sklearn) and adjustments to ensure accurate results.

