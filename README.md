# Austin Animal Shelter Data Analysis

This project explores and analyzes data from the Austin Animal Shelter (Austin Animal Center) to understand animal intakes, outcomes, and how the shelter is achieving its mission of ensuring live outcomes for at least 95% of animals.

# Project Overview

The Austin Animal Center provides shelter and care for thousands of animals each year.
This project uses three datasets;Intakes, Outcomes, and Stray Map to explore:

1. How the shelter is performing relative to its mission?
2. Which animals have the highest or lowest live outcome rates?
3. How long animals typically stay in the shelter?
5. What opportunities exist to improve adoption and foster outcomes?

# Datasets Used

Austin_Animal_Center_Intakes.csv; Details about animals entering the shelter.

Austin_Animal_Center_Outcomes.csv; Information about animals leaving the shelter.

Austin_Animal_Center_Stray_Map.csv;Locations of stray animals found in the community.

# Steps Performed

1. Data Loading and Inspection
   
Loaded the three datasets using pandas.

Inspected basic information with .info() and .head().

2. Data Cleaning
   
Standardized column names.

Converted date and time columns.

Merged intake and outcome datasets using animal_id.

Created new calculated fields:

length_of_stay_days (number of days between intake and outcome).

live_outcome (1 if adoption, transfer, or rescue; 0 otherwise).

3. Data Exploration
   
(a) Calculated key metrics:

Live Outcome Rate (%)

Median Length of Stay (days)

(b) Visualized:

Outcome type distribution

Length of stay distribution

Live outcome rate by species

Median length of stay by outcome type

4. Business Insights
   
Compared live outcome rates across animal species.

Identified which outcomes lead to longer stays.

Connected results to the shelter’s mission of achieving a 95%+ live outcome rate.

# Key Findings

The live outcome rate reflects how effectively the shelter meets its no-kill mission.

Median length of stay helps assess efficiency in placing animals in homes or foster care.

Species differences highlight which animals may need more targeted adoption efforts (e.g., cats may have lower live outcome rates than dogs).

Certain outcome types correspond to longer stays, suggesting process improvement opportunities.

# Recommendations

Focus outreach and foster programs on species with lower live outcome rates.

Streamline adoption processes for animals with long shelter stays.

Continue tracking live outcomes to ensure sustained mission success.


# Tools and Libraries

Python

Pandas

NumPy

Matplotlib

Seaborn

