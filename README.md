# Food_Services_Dataset_Project
American Food service dataset was shared , and various conclusion were made on - 

Business - Problem :
Shaun is a Sales Director, Food Services Division at a major Food & Beverages Manufacturer.
He has just been promoted into his role for top notch sales performance as well his keen analytic aptitude. 

“Opportunities Analysis” was determined 

The spreadsheet has 3 tabs, that have the following:
•	Total spend of his customers (restaurants) across various F&B categories, along with % share of purchases from Shaun’s company
•	Data about non-commercial establishments such as hospitals, schools across different geographic areas.
•	Retail outlets spread across similar geographies.

What to show in the Analysis:
•	Get a quick view of share of total spends and F&B spends for existing customers (restaurants)
•	What are the adjacent opportunities from the non-commercial establishments?
•	Get a view of retailer presence adjacent to his customers & prospects will help understand how much of these opportunities are being met / unmet.


Exploratory Data Analysis using Python – Pandas Library:

1.	We found that the Employee columns had a “Unknown” Value in unique counts.
Which cannot be used for analysis.

2.	The UNKNOWN employee rows have (5) Label Encoding in UNITS column, therefore output the ones whose units = 5

3.	We gave a variable name (un5) to all the restaurants with Unit = 5 as per LE.


4.	By using value_count () function we got to know that 5 TO 9 was the top count for 
UNITs = 5(1-9Units)

5.	Therefore, replacing UNKNOWN Employee row value with (5 to 9).

6.	Performed Label encoding to the no of Employee columns.

7.	Label encoding the Year in business column for better statistical findings
2 to 5 = 0
5 yr. plus = 1

8.	Replaced annual sales value to numeric type values rather than choosing Label Encoding, I replaced value by self for better understanding.

9.	In the Average-Check column, found the UNCODED value, replaced UNCODED with null and deleting the null row.

10.	AS all the Data Manipulation as well as Data cleaning operation were completed.


11.	Those data which were converted to (numeric format) using Label Encoding can now be easily used for statistical analysis

SHEET 1 - CONCLUSION FROM CUSTOMER RESTAURANTS:

1 - AMERICAN AND AMERICAN TRADITIONAL
2 - BAR & GRILL, BREW PUB, & EATERTAINMENT
3 - OTHER ETHNIC FOOD
have the most % share of F&B Purchases from Shaun’s company
•	Hence, we get the insight that these category restaurants must be approached so as to get Maximum percent of share in their purchases


SHEET 2 - CONCLUSION TO NON-COMMERCIAL SEGMENTS:
•	We have the adjacent opportunities from the non-commercial establishments to additionally sell into (Nursing Home) Market Segments in the city of WORCESTER 

•	We also have opportunity to sell into the Plymouth County due to high consumption of meals.


SHEET 3 - CONCLUSION TO RETAIL OUTLETS - SHEET 3 EDA :

•	Biggest opportunities in Retail Outlets are in Kentucky State.
•	Fish&Seafood Market Segment as well as different Gas stations must be our hit.


•	Opportunities in various segments can easily be studied using the (OPPORTUNITY ANALYSIS DASHBOARD) created using POWER BI.

