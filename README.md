Crop Production Analysis Project

This project focuses on examining crop production trends across various states and districts in India over multiple years.

Analysis Process:

Data Loading: The dataset containing crop production information was imported from a CSV file.

Data Inspection: The dataset was reviewed to understand its structure, number of entries, column data types (numeric or text), and missing values.

Data Cleaning: Inconsistencies were resolved by trimming extra spaces in column names, standardizing city names for merging, and filling missing production values using the average yield for each crop and district.

Data Exploration: The analysis explored:

Crops with the highest average yield.

Crops with lower representation in the dataset.

Seasonal patterns in crop production and yield.

Yearly variations in average crop yield.

The crop and year with the highest yield, which was Coconut in 2018.


Data Merging: Crop production data was integrated with air quality data using city names as the common key.

Feature Engineering: New features were created, such as:

Pollutant Ratios (SO₂/NOx).

Calculated Yield (Production ÷ Area).


Data Validation: Data consistency checks were conducted to ensure there were no negative values for Area, Production, or Yield, and no instances where production existed without an associated area.


Key Findings:

Coconut had the highest average yield in 2018.

Pollutant ratios were computed, though many were missing due to limited overlap between crop and air quality datasets.

Calculated yields were generally close to the reported yields, with minor differences observed.


Conclusion:
This analysis highlights trends in crop productivity, seasonal fluctuations, and provides a foundation for further study into possible links between agricultural output and environmental conditions, provided more detailed datasets become available.
