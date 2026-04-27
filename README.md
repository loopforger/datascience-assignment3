Global Terrorism Data Analysis (1970–2017)
Project Overview
This project analyzes global terrorism data from 1970 to 2017 to uncover patterns in terrorist activities, including trends over time, geographic distribution, and attack methods. By synthesizing over 180,000 recorded incidents, the study evaluates the broader impact regarding casualties, property damage, and ransom demands.

Objectives
Analyze global trends in terrorist attacks over five decades.

Identify the most affected countries, regions, and cities.

Examine the evolution of attack methods and weapon usage.

Quantify the impact of attacks through casualty and economic metrics.

Visualize complex data patterns using diverse statistical plots.

Dataset Description
The dataset encompasses key attributes including:

Temporal Data: Year, month, and day of the incident.

Geographic Data: Country, region, and city.

Incident Specifics: Attack types, weapon details, and target categories.

Impact Metrics: Fatality counts (nkill), injury counts (nwound), property damage, and ransom details.

Technologies Used
Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, and Tabulate.

Data Preprocessing
Replaced missing values in casualty columns (nkill/nwound) with 0.

Filtered unknown values (-9) from property damage records.

Handled ransom-related fields conditionally to ensure statistical integrity.

Analysis & Visualizations
The analysis covers event specifics, geographic shifts, and impact assessments. Visualizations include:

Trend Analysis: Line charts and histograms for temporal distribution.

Categorical Comparisons: Bar and pie charts for attack and weapon types.

Statistical Relationships: Heatmaps for variable correlation, scatter plots, and box plots for outlier detection.

Key Insights
Temporal Surges: A significant increase in recorded incidents during the 21st century.

Regional Concentration: Activities are heavily concentrated in the Middle East, South Asia, and North Africa.

Tactical Trends: Bombings and explosions remain the most frequent attack method.

Economic Impact: Beyond human casualties, property damage and ransom incidents highlight the economic motivations of perpetrator groups.

Conclusion
This project provides a comprehensive overview of global terrorism trends, highlighting critical patterns in geography and methodology. The findings serve as a foundation for research in security studies, policy-making, and international risk assessment.
