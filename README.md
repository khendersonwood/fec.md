# Intro to Markdown & Documentation: Campaign Finance Data

## First: Clean Data
* Step 1: Upload to Open Refine --> Create Project
* Step 2: Cluster data, search for spelling misatkes, remove trailing and leading white space
* Step 3:Sorted cities A --> Z
 * Changed BETHELEHEM --> BETHLEHEM
 * Changed American Airlines donation city from Dallas/FortWorth --> Fortworth where their headquarters are
 * Changed NEWYORKROOK --> New York
 * Adjusted capitlization in Research Traingle & RESEARCH Triangle to match (ALL CAPS)
 * Changed SONNYWALE --> SONNYVALE
* Step 4: Sorted through zip codes
 * Added a zipcode to American Airlines row 
 * Added zipcode to Johnson Co, NY, NY: 10016

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
**Answer: The tobacco industry contributes most to the Republican party and the media/entertainment indsutry contributes most to the Democratic party** </br>

