# Northern Light Airlines Promotional Campaign and Customer Segmentation Analysis

## Scenario
You are a data analyst for Northern Lights Airlines, a Canadian airline company. The company ran a promotional campaign from Feb-Apr 2018 to increase membership and the marketing team would like you to answer the following questions:

1. What impact did the campaign have on loyalty program memberships?
2. Was the campaign adoption more successful for certain demographics of loyalty members?
3. What impact did the campaign have on booked flights during summer?
4. How long does our customer stay before cancelling their subscription?
5. Conduct a segmentation analysis on our current customer database.

## Methodology
1. Data was first loaded in a jupyter notebook and then cleaned using the *pandas* library .
2. Cleaned data was then inserted to tables and then connected to create a database using SQL.
3. To get the impact of the campaign on the membership, a line graph was created visualizing the number of memberships overtime.
4. To verify whether the increase in membership was due to the promotional campaign, a one sample t-test was used. The population average was the monthly membership average prior to the start of the campaign.
5. To check if the campaign was more successful for certain demographics, the characteristics of the people who signed up were aggregated in a pivot table.
6. To get the impact of the campaign on the number of the flights the following summer (May-Aug),  a heat map was created to visualize the number of flights based on their enrollment date.
7. Average tenure was also computed for all those who have cancelled their membership.
8. Finally, customer segmentation was done  to check the current characteristics of the active membership pool.

## Results
1. What impact did the campaign have on loyalty program memberships?
* During the promotional campaign, year-on-year membership increased  51%, 39%, and 77% for February, March, and April, respectively.
* Additionally, the one-sample t-test resulted to p-value=0.007 which is less than p=0.05 and suggests that the null hypothesis can be rejected and the average memberships during the campaign is higher than the historical monthly memberships.
2. Was the campaign adoption more successful for certain demographics of loyalty members?
* Results showed that the campaign is most effective on  *Married male individuals who have a bachelor's degree* who made up 32% of the signups followed by *Married female individuals who have a bachelor's degree* accounting who made up 29% of the signups.
3. What impact did the campaign have on booked flights during summer?
* Those who signed-up during the campaign booked 19% of the flights during the summer of 2018.
4. How long does our customer stay before cancelling their subscription?
* Cohort analysis showed that our memberships stay 23 months on the average.
5. Conduct a segmentation analysis on our current customer database.
* RFM customer segmentation showed that our active members pool are made-up of:
	* About-to-sleep: 20%
	* Champions: 20%
	* Hibernating: 19.7%
	* At-risk: 14.7%
	* Potential Loyalists: 12.6%
	* Loyal Customers: 7.4%
	* Can't Lose Them: 5.7%
