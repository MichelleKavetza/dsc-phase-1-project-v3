# Aviation Accident Risk Analysis

## Overview
This project analyzes aviation accident data to support stakeholders in identifying low-risk flights and improving aviation safety. By focusing on accident trends, geographic patterns, and flight purposes, the analysis provides actionable insights for safer travel and operations.

The final dataset was prepared for Tableau visualization, presenting key insights interactively for stakeholders such as passengers, airlines, and regulators.

### Business Understanding
Stakeholders
Passengers: Interested in safer travel options.
Airlines: Aiming to enhance operational safety and customer confidence.
Aviation Authorities: Focused on minimizing aviation risks and improving safety regulations.

### Key Business Questions
How have accident trends changed over the years for different aircraft makes?
Which states have higher or lower accident counts?
How does the flight purpose (e.g., commercial, personal) impact accident frequency?

### Data Understanding and Analysis
Source of Data
Primary Dataset: Aviation Safety Network.
Supplementary Dataset: US State Codes for geographic mapping.

### Description of Data
The dataset includes:

Aircraft Details: Make, model, and type (e.g., Amateur Built).
Accident Information: Date, location, severity, and flight purpose.
Geographic and Temporal Features: State, city, month, and year.

### Data Preparation
Feature Engineering:
Split location data into City and State.
Added new columns for Month and Day.
Outlier Handling:
Removed extreme outliers using the IQR method.
Filtering:
Focused on data post-1982 to ensure relevance.
Enrichment:
Mapped state abbreviations to full names using US State Codes.

### Visualizations
1. Accident Trends per Year by Aircraft Make
Description: A line chart showing the number of accidents over time for the top 5 aircraft makes.
Purpose: To assess how accident trends have evolved for leading manufacturers.

Key Insight:
Accident counts for some manufacturers like Cessna have steadily declined, suggesting improved safety measures.

2. Accidents by State
Description: A bar chart highlighting the number of accidents per state.
Purpose: To identify safer regions and assess the geographic distribution of accidents.

 Key Insight:
States like Alaska and California report higher accident counts, potentially due to challenging terrain or traffic.
Safer states include Nevada and North Dakota, with consistently fewer accidents.

3. Accidents by Flight Purpose
Description: A bar chart or pie chart categorizing accidents by flight purpose (e.g., personal, commercial, cargo).
Purpose: To evaluate which flight types pose the greatest risk.

Key Insight:
Personal flights account for the highest number of accidents, likely due to less stringent operational controls compared to commercial flights.

### Conclusion
Key Findings
Yearly Trends: Accident rates for many aircraft makes have declined over time, reflecting advancements in safety.
State Analysis: Certain states exhibit higher risks, suggesting the need for targeted safety measures.
Flight Purpose: Personal flights have higher accident frequencies, emphasizing the importance of training and maintenance for non-commercial aviation.

### Recommendations
Safer Aircraft Makes: Consider flying with manufacturers showing improved safety records, such as Cessna.
Choose Regions Carefully: Avoid states with high accident counts if possible.
Enhance Personal Flight Safety: Encourage stricter regulations and safety checks for personal aircraft.