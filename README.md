Project 4 




Introduction:

Homelessness in the USA had been a persistent issue affecting hundreds of thousands of individuals and families. Factors contributing to homelessness include a lack of affordable housing, poverty, unemployment, mental illness, substance abuse, and systemic issues such as racial and economic inequality.

Several cities and states have implemented various strategies to address homelessness, including providing emergency shelters, supportive housing, and services such as mental health care, substance abuse treatment, and job training.

Non-profit organizations, local governments, and federal agencies have been working together to combat homelessness through initiatives like the U.S. Interagency Council on Homelessness and programs such as Housing First, which prioritizes providing permanent housing as a first step to addressing homelessness. However, despite these efforts, homelessness continued to be a significant challenge, exacerbated by factors like the COVID-19 pandemic, economic downturns, and natural disasters.

Goal:
Predicting Overall Homelessness in the year 2024:
In this project we gathered most of the information from the U.S Department of Housing and Urban Development (HUD) (https://www.hud.gov/press/press_releases_media_advisories) to find out approximately the overall rate of homelessness in the United States from the years 2007 to 2023. 

Process:
We started by using Microsoft Excel to separate the tab by each year of data. All the CSV used were combined and moved to the Resource file. In the years 2014-2023 there were some additional categories added that were then combined to be modified as one category for the database such as “Gender questioning”, and “Neither male nor female”. 
Pandas was used to combine the CSV’s containing data from 2014-2023. Empty cells were removed and column names were changed to be more legible. A new file was created in SQL then was used in PgAdmin to create a database. The database was connected to pandas to perform the predictions. Tableau was utilized to create a story of the overall project.
Within this process there was enthralling information displayed from the year 2021. That being that from the year 2020 to 2021, there was an astounding drop in homelessness of about 200,000 cases. According to an article (https://qz.com/2123706/us-homelessness-went-down-in-2021) this is because those cases were reported “sheltered” homeless in temporary housing such as emergency shelters which was reported by HUD. Many articles such as (https://www.nbcnews.com/politics/white-house/federal-pandemic-relief-prevented-rise-homelessness-housing-agency-say-rcna101267) suggest that the pandemic of COVID-19 had a large role to play. This is because there was a large federal pandemic relief by allowing and providing resources such as child tax credit, emergency rental assistance, unemployment benefits, and a national eviction moratorium.
By the year 2022 the number of homelessness was back up by almost 200,000 as shown below. Some research provided by (https://www.housingfinance.com/news/homelessness-spikes-12-in-latest-count_o) suggests that the median for renting rates in the US from years 2021-2022 had increased by over 9% which resulted in a new surge of homelessness for more vulnerable populations. This article also points out how the federal rental assistance provided for the pandemic had run its course leaving lots of individuals and families in difficult financial circumstances once again.


Row Labels	Sum of Population	Sum of Overall Homeless	% of population
2007	         301,231,207.00 	                                641,665.00 	0.21%
2008	         304,093,966.00 	                                635,445.00 	0.21%
2009	         306,771,529.00 	                                624,598.00 	0.20%
2010	         309,321,666.00 	                                630,806.00 	0.20%
2011	         311,556,874.00 	                                618,611.00 	0.20%
2012	         313,830,990.00 	                                616,556.00 	0.20%
2013	         315,993,715.00 	                                584,483.00 	0.18%
2014	         318,301,008.00 	                                570,514.00 	0.18%
2015	         320,635,163.00 	                                558,573.00 	0.17%
2016	         322,941,311.00 	                                544,084.00 	0.17%
2017	         324,985,539.00 	                                545,566.00 	0.17%
2018	         326,687,501.00 	                                547,264.00 	0.17%
2019	         328,239,523.00 	                                562,184.00 	0.17%
2020	         331,454,351.00 	                                575,714.00 	0.17%
2021	         332,048,977.00 	                                379,813.00 	0.11%
2022	         333,271,411.00 	                                577,778.00 	0.17%
2023	         334,914,895.00 	                                649,535.00 	0.19%



Limitations: 
When HUD predicts the population growth, they use sophisticated formulas with various dataset which include the prediction of High immigration, low immigration, and medium immigration, in addition to this they use death and birth rate predictions. 
