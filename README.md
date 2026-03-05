Delhivery Logistics: Operational Intelligence & Optimization
Executive Summary
Analyzed 140,000+ rows of trip-level data to identify systemic delivery delays. By comparing actual trip durations against OSRM (routing engine) predictions, I identified a statistically significant variance that impacts customer ETAs and operational costs.

Key Insights
The Delay Factor: On average, actual trips take 2.86x longer than system predictions.
Route Specificity: 'Carting' (local delivery) shows a higher delay factor (3.06x) compared to FTL (2.55x), suggesting urban congestion as a primary bottleneck.
Statistical Rigor: A paired T-Test confirmed the variance is statistically significant ($p < 0.05$).
Tech StackLanguage: Python (Pandas, NumPy)Visualization: Seaborn, MatplotlibStatistical Analysis: SciPy (Hypothesis Testing)
