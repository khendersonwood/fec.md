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
!['PT2.JPG', 'Pivot Table Table for Question #2'](/PT2.JPG)

</br> 

## Question 3: What percentage of the tobacco industry???s donations does Philip Morris account for? How much is it? 
* Step 1: sort industry Z-->A, copy and paste all tobacco values to seperate sheet
* Step 2: sort donors Z -->A to identify all donations made by Phillip Morris **2,070,000** </br>
*  !['T2.JPG', 'Tobacco Values for Phillip Morris'](/T2.JPG)
* Divide Phillip Morris contributions (2,070,000) by total (2,820,000) = (2,070,000/2,820,000) = **73.40% of tobacco contributions were from Phillip Morris** </br>
!['T1.JPG', 'Tobacco Contributions Sum'](/T1.JPG)

## Question 4/5 : Describe (in two to three sentences ??? no need for a detailed story pitch) one potential story from this dataset that you???d find promising if this were a project you were working on. Give it a headline. Include up to three types of sources you would call to report out the story and a few of the questions you might ask. What data might be suitable to join with this data to provide context or additional stories? Give me two examples.</br>

### What one man can do: How Phillip Morris was the single biggest donor to the 1995 Political Campaign
* This story would be about how Phillip Morris is the biggest single contributor in this politcal campaign, what this means for tobacco companies and to invesitgate if any laws around tobacco production are swayed becuase of this 
* Data
  * 2014 Surgeon Report: The Health Consequences of Smoking https://www.cdc.gov/tobacco/data_statistics/sgr/50th-anniversary/index.htm
  * CPI for Smoking & Tobacco: https://fred.stlouisfed.org/series/CUUR0000SEGA
 * Sources:
   * Tobacco Lobbying, Open Secrets: https://www.opensecrets.org/industries/indus.php?ind=A02
   * https://www.theatlantic.com/business/archive/2015/04/how-corporate-lobbyists-conquered-american-democracy/390822/
   * https://pubmed.ncbi.nlm.nih.gov/12856736/
   * https://tobaccocontrol.bmj.com/content/8/2/196
