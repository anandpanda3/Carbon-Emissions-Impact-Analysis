🌍 Carbon Emissions Impact Analysis
Project Overview
This project investigates the relationship between atmospheric CO₂ concentrations and global temperature anomalies from 1958 to 2022 using Python. By leveraging statistical analysis and clustering techniques, it identifies trends and correlations to inform climate policy and mitigation strategies.

🔍 Key Analyses & Findings
Correlation Analysis

Strong positive relationship between CO₂ levels and temperature anomalies:

Pearson Correlation: 0.955 (near-perfect linear relationship).

Spearman Correlation: 0.938 (consistent monotonic trend).

Granger Causality: Weak evidence (p=0.06 at Lag 1), indicating correlation without definitive causation.

Time-Series Trends

CO₂ Concentrations: Steady increase with an annual growth rate of 0.32 ppm/year, peaking at 421 ppm in 2022.

Temperature Anomalies: Gradual rise of 0.03°C/year, totaling +1.8°C since 1961.

Seasonal CO₂ Variations

Peaks in May due to low photosynthesis during winters.

Lows in September from enhanced plant activity during summers.

Lagged Effects & Predictive Insights

OLS Regression: Current CO₂ levels account for 94.9% of temperature variance.

Predictive Scenarios:

10% CO₂ Increase: +1.09°C temperature rise.

20% CO₂ Reduction: -0.63°C cooling effect.

Climate Pattern Clustering

Identified 3 Distinct Clusters reflecting different CO₂ and temperature combinations:

Low CO₂ & Temp (Pre-1980s)

Moderate CO₂ & Temp (1980s–2000s)

High CO₂ & Temp (Post-2010)

💡 Strategic Insights
Immediate Reductions: A 10–20% CO₂ cut could significantly reduce warming, aligning with IPCC targets.

Policy Prioritization: Focus on immediate reductions since lag effects are minimal.

Leverage Natural Carbon Sinks: Reforestation can help mitigate CO₂ peaks.

Real-Time Monitoring: Essential for proactive climate action.

🛠️ Tools & Techniques
Python Libraries: pandas, Plotly, Matplotlib, scikit-learn

Statistical Methods: Correlation analysis, OLS regression, Granger causality, K-means clustering

Visualization: Time-series plots, scatter plots, and cluster maps

📝 Conclusion
The project highlights a near-perfect correlation between rising CO₂ levels and global temperature increases, emphasizing the urgency of reducing emissions to mitigate climate change. Implementing strategic policies and enhancing carbon sinks can help achieve climate goals.

Dataset Reference: [https://statso.io/carbon-emissions-worldwide-case-study/]
