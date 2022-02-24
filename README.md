# Intro to Markdown & Documentation: Campaign Finance Data

## First: Clean Data
* Step 1: Upload to Open Refine --> Create Project
* Step 2: Cluster data, search for spelling misatkes, remove trailing and leading white space
* Step 3: Sort cities A --> Z
  * Changed BETHELEHEM --> BETHLEHEM
  * Changed American Airlines donation city from Dallas/FortWorth --> Fortworth where their headquarters are
  * Changed NEWYORKROOK --> New York
  * Adjusted capitlization in Research Traingle & RESEARCH Triangle to match (ALL CAPS)
  * Changed SONNYWALE --> SONNYVALE
* Step 4: Sorted through zip codes
  * Added a zipcode to American Airlines row 
  * Added zipcode to Johnson Co, NY, NY: 10016
* Step 5: Sorted through dates & Deleted duplicate columns:
  * Bristol-Myers Squibb, 3/21/96, $100,000
  * Scripps, Edward Wyllis, 7/31/96, $125,000
  * RJ Reynolds Tobacco, 10/17/96, $100,000
  * Senate Republican Campaign Cmte, 10/18/96, $100,000
  * Friess, Foster, 10/21/96, $100,000
  * Union Pacific Corp, 10/21/96, $100,000
  * Brown & Williamson Tobacco, 10/23/96, $100,000
  * California Republican Party, 10/24/96, $675,000
  * Lauder, Ronald S, 10/25/96, $100,000
  * Senate Republican Campaign Cmte, 10/25/96, $100,000
  * Senate Republican Campaign Cmte, 10/28/96, $100,000
  * Murdoch, Anna M, 11/1/96, $250,000
  * Cafaro, John J, 11/7/96, $100,000
  * New York Republican State Cmte, 12/21/96, $1,500,000
  


## Question 1: Which industries contributed the most to the Republican and Democratic parties? How much was contributed to each party?
* Step 1: Open data sheet in Open Refine
* Step 2: Cluster & Sort through data, remove trailing and leading white space 
* Step 3: Identify possible external and internal issues
  * Party "3" is included, which is the Natural Law Party, There's a "republican/conservative" category under the sectors
* Step 4: Import to excel
* Step 5: Freeze top row
* Step 6: Create Pivot Table
!['PT1.JPG', 'Pivot Table Table for Question #1'](/PT1.JPG)
* Step 7: Copy and paste data from pivot table #1 to another data set
* Step 8: Sort Rows D & A from Z --> A </br>
**Answer: The Republican/Conservative indsutry contributed the most to the Republican party at $5,039,000 and the media/entertainment indsutry contributed most to the Democratic party at $1,880,000.** **In total, the Democratic Party recieved $21,553,578 and the Republican Party Recieved $27,199,000 </br> ** </br>

## Question 2: How much did donors from the Misc. Business sector contribute to the Democratic party? Which donors were based in Miami Lakes, FL? (Remember to give me the answer and the steps you took to get the answer.)
* Step 1: Create Pivot Table
  * Rows: Sector, Columns: Party, Values: Amount **The Misc. Business sector contributed $3,520,000 to the Democratic Party
 * Step 2: Copy and paste all Misc Business donations to a seperate spreadsheet, sort party Z-->A to seperate D & R donations, search (apple F) for "Miami Lakes" entry and find **2 donations were from Miami Lakes from Windmere Corp**
!['PT2.JPG', 'Pivot Table Table for Question #1'](/PT2.JPG)
