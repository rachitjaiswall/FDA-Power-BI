# FDA Adverse Events Analysis - Power BI Project

## Overview

This Power BI project analyzes adverse events reported to the FDA (Food and Drug Administration), primarily focusing on food items and related products. The dashboard provides insights into the distribution of health-related incidents across different industries, age groups, and severity levels.

https://www.google.com/imgres?q=fda&imgurl=https%3A%2F%2Fpharmaoffer.com%2Fwp-content%2Fuploads%2F2023%2F10%2FFDA-jpg.webp&imgrefurl=https%3A%2F%2Fpharmaoffer.com%2Fblog%2Ffood-and-drug-administration-what-is-the-fda%2F&docid=HRJrLoV-VRynXM&tbnid=0ACeqJBCC8TULM&vet=12ahUKEwj5-cvejeSIAxWzkK8BHZzcM3IQM3oFCIIBEAA..i&w=1000&h=571&hcb=2&ved=2ahUKEwj5-cvejeSIAxWzkK8BHZzcM3IQM3oFCIIBEAA

## Data Source

The dataset contains information from the FDA's CAERS (Center for Food Safety and Applied Nutrition Adverse Event Reporting System). Each row represents a unique adverse event report, detailing the associated product, outcomes, and symptoms experienced by the affected individual.

## Key Features

1. **Total Reports and Industry Categories**
   - Displays the total count of reports (90,614) and the number of industry categories (38).

2. **Outcome Analysis by Age Group**
   - Visual breakdown of outcomes across different age groups (Adult, Children, Elderly, Infant and Toddler, Teenager, Young Adult).
   - Highlights the most common outcomes for each age group.

3. **Outcome Analysis by Industry Category**
   - Bar chart showing the distribution of reports across various industry categories.
   - Cosmetics and Foods/Dietary Supplements appear to be the top categories.

4. **Analysis of Event Outcomes**
   - Pie chart illustrating the proportion of different outcomes:
     - Non-serious injuries/illness (30.96%)
     - Other serious important medical events (30.65%)
     - Visited a health care provider (19.22%)
     - Hospitalization (11.68%)
     - Visited an ER (7.49%)

5. **Filters**
   - Gender filter
   - Outcomes filter
   - Product Role filter (Concomitant, Suspect)

## Insights

- Adults are the most affected group across all outcome categories.
- Non-serious injuries/illness is the most common outcome, followed closely by other serious important medical events.
- The cosmetics industry has the highest number of reports, followed by foods/dietary supplements.
- The dashboard allows for detailed analysis by filtering on gender, specific outcomes, and product roles.

## How to Use

1. Open the Power BI file (`FDA_Adverse_Events_Analysis.pbix`) using Power BI Desktop.
2. Use the filters on the left to narrow down the data by gender, outcomes, or product role.
3. Hover over the charts for more detailed information.
4. Click on elements in one chart to cross-filter the other visuals.

## Future Enhancements

- Include time-based analysis to identify trends over years.
- Add more detailed breakdowns of specific symptoms reported.
- Incorporate geographical data if available for regional analysis.

