# healthcare-dashboard
Healthcare Analytics with Power BI 
Step 1: Create a calculated column for the length of stay
1.	Go to the Modeling tab.
2.	Click on New Column.
3.	Enter the following DAX formula:

LengthOfStay = DATEDIFF('Table'[Date of Admission], 'Table'[Discharge Date], DAY)
