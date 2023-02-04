

You can interact with the dashboard here: https://app.powerbi.com/MobileRedirect.html?ctid=0d208db3-39f6-4f17-b3f4-89883d314820&reportPage=ReportSection&Context=share-report&bookmarkGuid=5e5079c6-f283-4f4b-b4aa-ef9a4d96a3cd&action=OpenReport&reportObjectId=cb7c89bd-c045-43c9-8b7c-f7726f743936&groupObjectId=6d28cb0d-ffee-4bab-a727-e5c1c937d6b7&pbi_source=mobile_ios

Restaurant ratings in Mexico by real consumers from 2012, including additional information about each restaurant and their cuisines, and each consumer and their preferences.

The file upon downloading is a CSV file which i loaded into Power BI Query Editor where few manipulations were done. The file contained 5 datasets:

	Consumer_preferences csv: The table contains customer information.

	Consumer csv: This table contains customer cuisine preferences.

	Ratings csv: The dataset includes restaurant details

	Restaurant Cuisines csv: The table contains cuisines offered by each restaurant.

	Restaurants csv: The table contains cuisines offered by each restaurant.



Relationships were created among these datasets using primary and foreign keys for proper analysis.

POWER BI DESKTOP: having done the above, i then closed and apply, this took me to the Power BI Desktop where the following simple DAX - Data Analysis Expression were performed:

	Distinct count of customers

	Distinct count of cuisines

	Distinct count of restaurants

REPORTS

I used CARD to show:

	Distinct count of customers 
	Distinct count of cuisines
	Distinct count of restaurants
	Average overall rating
	Average Food rating
	Average service rating

I used BAR CHART to show:

	Overall ratings of each restaurants
	Top 10 most preferred cuisines by customers
	Least preferred cuisines by customers

I used COLUMN CHART to show:

	Food and Service rating of each restaurants (stacked column chart)
	Occupation of the customers

I used PIE CHART to show city where customers reside and DONUT Chart for Marital status of customers.

ROW CARD to show each restaurant and price category.

LINE CHART for customers transportation method and inserted SLICERS to drill through the dashboard.

INSIGHTS

a) There are 127 restaurants in 3 states and majority are in San Luis Potosi (92 restaurants).

b) 62.32% of customers reside in San Luis Potosi

c) Majority of customers that patronize these restaurants fall into the student category and are single

d) Top 3 most preferred cuisines are Mexican, American and Cafeteria.

e) Tortas Locas Hipocampo is the highest-rated restaurant.

f) From the analysis, customers prefer closed area as this affected service ratings of restaurants that do not.

g) Since, majority of the customers are students, i was able to deduce that restaurants that allow smoking have higher ratings than restaurants that do not.

h) 12 restaurants are high-priced, 45 medium-priced and 36 restaurants are low-priced. Majority of students prefer medium-priced restaurants.

i) Also, customers prefer restaurants that offer alcohol service- wine and beer section.

j) Restaurants that have valet parking space have the highest food and service rating.

RECOMMENDATIONS

a) Students patronize these restaurants the most so restaurants should offer discounts or special students’ entry

b) The average food rating of 1.21/2 shows people are pleased with their dining experience. However, some restaurants have low service rating so they should try and improve their service experience e.g having valet parking space

c) American Cuisine and Cafeteria are the second and third most preferred cuisine respectively and there are few restaurants that offer these cuisines. Restaurants can improve business in that segment as well
