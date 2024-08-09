# HR-Analytics

**Project Overview**
This Power BI project analyzes employee attendance data, integrating information from multiple months to provide insights into attendance metrics. The project includes calculations for key performance indicators (KPIs) such as presence %, work-from-home (WFH) %, and sick leave (SL %) to evaluate employee attendance and performance.

**Data Sources**
The data is sourced from an Excel file with the following sheets:

June 2022 Attendance List: Attendance data for June 2022.
May 2022 Attendance List: Attendance data for May 2022.
April 2022 Attendance List: Attendance data for April 2022.
Attendance Key: Key for interpreting the attendance data.

**Data Transformation**
This involved consolidating information from multiple sheets, ensuring proper data formatting, and organizing the data structure to facilitate analysis. Key steps included merging data, setting the correct column headers, cleaning up any inconsistencies, and normalizing the data for better analysis.

**Measures/Calculated Columns**
Using DAX (Data Analysis Expressions), the following measures and calculated columns were created:

Total Working Days: Calculates the total number of working days.
Present Days: Counts the number of days an employee was present.
WFH Count: Counts the number of days an employee worked from home.
Presence %: Calculates the percentage of days an employee was present out of the total working days.
WFH %: Calculates the percentage of days an employee worked from home.
SL %: Calculates the percentage of days an employee took sick leave.

**Report**
The Power BI report features the following KPIs and visualizations:

Presence %: Displays the percentage of days an employee was present.
WFH %: Shows the percentage of days an employee worked from home.
SL %: Illustrates the percentage of days an employee took sick leave.
Interactive Elements: Includes slicers and filters to explore data across different dimensions.

