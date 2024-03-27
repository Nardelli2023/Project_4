Project 4 

TABLEAU LINK: https://public.tableau.com/app/profile/aygul.nardelli/viz/USHomelessnesstrend/HomelessnessUSA?publish=yes






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


![image](https://github.com/Nardelli2023/Project_4/assets/145957737/cbf63af2-b130-4272-ab00-a25e75a21077)




Limitations: 

When HUD predicts the population growth, they use sophisticated formulas with various dataset which include the prediction of High immigration, low immigration, and medium immigration, in addition to this they use death and birth rate predictions. According to the data, we can only predict about 35% of accuracy towards future homelessness.


Conclusion: 

-The model performs relatively well for the Midwest region with a precision of 0.62 and a higher recall of 0.38.

-The South region also has a decent precision of 0.41 but a slightly lower recall of 0.36.

-The West region has a high recall of 0.53 but a low precision of 0.23, indicating that the model tends to overpredict the West region.

-The Northeast region has the lowest performance with the lowest precision and recall among all regions.

Overall, based off our data analysis provided by HUD, it is difficult to predict the future rate of homelessness in the US. The model might benefit from further tuning or a different approach to improve its performance, especially for the Northeast and West regions. With many different factors influencing surges and declines, it would be a challenge to predict the accuracy based on the information we have utilized for this project.

Additional Sources:

https://www.huduser.gov/portal/sites/default/files/pdf/2023-AHAR-Part-1.pdf"The 2023 Annual Homelessness Assessment Report (AHAR) to Congress"Data Reports Show that Surge in Homelessness Was Averted During COVID-19 National Emergency | HUD.gov / U.S. Department of Housing and Urban Development (HUD)HUD.gov / U.S. Department of Housing and Urban Development (HUD) |chatGPTThe National Alliance to End HomelessnessHomelessness in America: Statistics, Analysis, & Trends | Security.orghttps://www.census.gov
https://endhomelessness.org/homelessness-in-america/who-experiences-homelessness/youth/#:~:text=Youth%20homelessness%20is%20often%20rooted%20in%20family%20conflict.,systems%20are%20also%20more%20likely%20to%20become%20homeless.

