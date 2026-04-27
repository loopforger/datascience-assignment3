Global Terrorism Data Analysis (1970–2017)
 Project Overview
This project analyzes global terrorism data from 1970 to 2017 to uncover patterns in terrorist activities, including trends over time, geographic distribution, attack methods, and the overall impact in terms of casualties, property damage, and ransom demands.

The dataset contains over 180,000 recorded incidents and provides detailed information on attack characteristics, locations, and outcomes.

 Objectives
Analyze trends in terrorist attacks over time
Identify the most affected countries, regions, and cities
Examine attack methods and weapon usage
Evaluate the impact of attacks (casualties, property damage, ransom)
Visualize patterns using multiple graph types
 Dataset Description
The dataset includes the following key attributes:

Date Information: Year, month, and day of the attack

Location Details: Country, region, and city

Attack Information: Type of attack (e.g., bombing, assassination)

Weapon Details: Weapons used in the attack

Target Information: Type of target (civilians, military, etc.)

Impact Metrics:

Number of people killed (nkill)
Number of people wounded (nwound)
Property damage (property)
Ransom involvement (ransom, ransomamt)
 Technologies Used
Python

Libraries:

pandas (data manipulation)
numpy (numerical operations)
matplotlib (visualization)
seaborn (advanced visualization)
tabulate (formatted tables)
 Analysis Performed
1. Event Specifics:
Detailed records of each terrorist attack, including date, location, and the nature of the incident (e.g., assassination, bombing, hostage-taking).

2. Geographic and Demographic Information:
Insights into the geographic regions affected, including country, region, and city specifics, as well as details about targeted groups or individuals.

3. Attack Details:
Information on the attack methods used, weapons involved, and the nature of the attack (e.g., explosive, incendiary, or armed assault)

4. Impact Assessment:
Data on casualties, including the number of killed or wounded, and any property damage or ransom demands associated with the attacks.

 Visualizations
The project includes multiple types of visualizations:

Line charts (trend analysis)
Bar charts (comparisons)
Pie charts (proportions)
Heatmaps (relationships between variables)
Scatter plots (correlations)
Box plots (outlier detection)
Histograms (distribution analysis)
 Data Preprocessing
Missing values in nkill and nwound replaced with 0
-9 values in property column treated as unknown and removed
Ransom-related fields handled conditionally
 Key Insights
Terrorist attacks have increased significantly in the 21st century
Attacks are concentrated in specific regions (Middle East, South Asia)
Bombings/explosions are the most common attack type
Most attacks result in low casualties, but a few extreme events dominate totals
Property damage is a frequent consequence of attacks
Ransom-related incidents highlight economic motivations
 Conclusion
This project provides a comprehensive analysis of global terrorism trends, highlighting key patterns in geography, attack methods, and impact. The findings can support further research in security, policy-making, and risk assessment.
