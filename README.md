
1.	Overview of datasets obtained.
	
In this project, we are going to use two independent datasets. The first one is Citi Bike Trip Histories which provides the details of each trip on daily basis. The other dataset is the Daily Cases, Hospitalizations and Deaths provided by Government of NYC to track the trend of COVID-19. 

2.	Identify the business problem and its context. 

(a)	Context: COVID has triggered significant changes in consumer behaviour in many aspects. Most if not all facilities that are typically used for physical exercise have closed, leaving many consumers looking for alternatives. Also, many consumers are weary of using public transportation due to risk of COVID infections in crowded spaces.

(b)	Business Problem: The change in consumer behaviour has the potential to significantly disrupt the current and future demand of bike sharing programs. Plans to expand the program created before the start of the COVID pandemic may no longer reflect current demand.

(c)	Solution: This project will bring together several datasets related to bike-sharing programs in North America in order to understand the extent of the impact of consumer behaviour on the demand for bike-sharing in general. Based on the change in demand and a review of the plans for future expansion, suggestions and predictions will be made to adjust plans accordingly.

(d)	Methods: This project is going to be implemented in Python. Besides techniques 1 and 6 which are Descriptive Analytics and AI Implementation, we are going to use technique 2, Supervised learning models. Because we have two large datasets so that we have plenty training data to compared with and to improve the accuracy. Also, since we are trying to make suggestions and predictions, supervised learning models are more suitable for this project. 

3.	Description of the data available.

(a)	Data sources: Since both datasets have date variable, we are going to merge these two datasets by same dates so that we can connect the bike sharing trips with the trends of COVID-19. 

a.	Citi Bike Trip Histories: https://www.citibikenyc.com/system-data

b.	Daily Cases, Hospitalizations and Deaths: https://www1.nyc.gov/site/doh/covid/covid-19-data-trends.page#epicurve

(b)	Main Variables: 

a.	Citi Bike Trip Histories: 

i.	Trip Duration (seconds).

ii.	Start Time and Date.

iii.	Stop Time and Date.

iv.	Start Station Name.

v.	End Station Name.

vi.	Station ID.

vii.	Station Latitude/longitude.

viii.	Bike ID.

ix.	User Type (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member).

x.	Gender (0=unknown, 1=male, 2=female).

xi.	Year of Birth.

b.	Daily Cases, Hospitalizations and Deaths:

i.	CASE_COUNT: Daily count of confirmed cases citywide.

ii.	PROBABLE_CASE_COUNT: Daily count of probable cases citywide.

iii.	DEATH_COUNT: Daily count of confirmed deaths citywide.

iv.	PROBABLE_DEATH_COUNT: Daily count of probable deaths citywide.

v.	HOSPITALIZED_COUNT: Daily count of hospitalized cases citywide.

(c)	Data quality and relevancy: These two datasets focus on New York City only and could be merged by matching same dates. Both data sources are reliable and updated periodically: the COVID one is under control of NYC government and is updated daily to reflect new data entries; the Citi Bike Trip one is undated monthly, and it has it own monthly operation reports on website as well. We believe these two dataset could be a great source to reveal the complicated impact brought by COVID-19 on the demand of NYC bike sharing program. 
