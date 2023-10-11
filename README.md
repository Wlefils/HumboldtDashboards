# Executive Summary
This project involved creating two dashboards designed using Excel and Tableau, with the goal of assisting stakeholders in making pivotal decisions for cities in Humboldt County, California. Key financial and demographic insights across eight cities the county were visualized. The financial dashboard, based on the data from each city’s Annual Comprehensive Financial Report, provides a clear, concise snapshot of their fiscal health via a suite of calculated financial KPIs for FY 2021. The demographic trends dashboard, powered by a decade's worth of data from the U.S. Census Bureau, reveals each city’s demographic shifts over time. This project emphasized my technical skills and my commitment to aiding stakeholders in making informed decisions by providing accessible, data-driven tools.

#### Technical Skills Used
* Excel/Google Sheets (initial implementation)
* Tableau (final deliverable)

## Key Findings
![image](https://github.com/Wlefils/HumboldtDashboards/assets/98787088/bdf0ea8c-6084-49e9-8a49-4e1cdb1212ec)
[Interactive Tableau Dashboards here](https://public.tableau.com/views/HumboldtCountyCitiesDashboard/HumboldtCounty10-YearDemographicTrends?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)<br>
[Google Sheets alternative here](https://docs.google.com/spreadsheets/d/1CLqB5KhHkbXOVqWspcsF-ReAd5riIrxw/edit?usp=sharing&ouid=100312081914865605951&rtpof=true&sd=true)

#### Financial Indicators
The biggest takeaway from the financial KPIs is that **Humboldt County's largest city, Eureka, is in a precarious position.** While Eureka has a viable current ratio, its long-term debt and operating margin indicate significant financial struggles ahead. The city is primarily struggling due to its high expected future pension costs. From 2011 to 2021, Eureka cut more than a dozen positions with the police department to reallocate funding to its pension debt. **Eureka's yearly pension payments will increase annually until 2040, and will inevitably lead to further reductions in city services.** **Arcata and Fortuna are in much better financial health** in the short and medium term, but these cities could also experience difficulties as their pension debt balloons in the coming decades. **The smaller cities that provide fewer services are in relatively stable financial condition**, with low debt burdens and strong operating margins. Ferndale's revenues suffered considerably as a result of the pandemic, but the city's financial health is expected to recover in the near future.

#### Demographic Insights
**Humboldt County's population has stagnated in the decade from 2011 to 2021.** The largest population center of Eureka has seen a decline of 1%. **Blue Lake has seen a disastrous decline of over 30%**. Arcata, the second largest city, has experienced respectable growth of over 9%, outpacing the state as a whole. However, **Arcata's population increase has caused its median rent to increase by over 33%, outpacing gains in household and per capita income**. Given the context of Cal Poly Humboldt seeking to double enrollment by 2028, it seems likely that this trend will continue, and may affect the nearby areas of Eureka and the unincorporated McKinleyville (not featured on this dashboard). Fortuna has seen population growth, significant income growth, and reasonable rent increases. However, its median home values have increased by only 4%. Trinidad is an interesting case, as it has experienced large increases across the board, particularly a rent increase of over 125%. Despite this, Trinidad is the only city to see home values decline, and by a striking 22.8%. Due to Trinidad's small population, there may be some noise in the data here as a result of a small sample size. 

**Overall, the dashboards tell us that Humboldt County, especially Eureka, is struggling.** The cities are failing to attract more residents, and home values are stagnating relative to the rest of state's housing market. In the largest population centers, income has increased, but only by about the same amount as rent. In the next two decades, Eureka and potentially Arcata and Fortuna will be forced to cut critical services to pay pension debt obligations.

## Background
### Introduction to Humboldt County and Its Cities
Nestled in the verdant reaches of far Northern California, Humboldt County is home to several cities each with their unique financial and demographic characteristics: Eureka, Arcata, Fortuna, Ferndale, Rio Dell, Blue Lake, and Trinidad. As California has grown in population and economic relevance in the last two decades, this region has unfortunately stagnated and even declined in some areas.
### Problem Statement
Analyzing financial and demographic data is crucial for cities. It helps them manage their budgets, plan for the future, and ensure they meet the needs of their residents. By understanding key financial metrics and demographic trends, city leaders and their constituents can make better decisions about policies and initiatives moving forward.
Despite financial and demographic data being publicly available, there was no simple way for stakeholders to explore, compare, and analyze this information across all of the cities in the county. This project aimed to fill this gap by creating dashboards that provide clear, interactive data visualizations. This tool allows stakeholders, including city officials and policymakers, to quickly understand the data and use it to make informed decisions. Additionally, citizens of Humboldt County can look at the dashboards to gain a clearer understanding of the financial health of their respective cities.
### Objective
The primary goal behind developing these dashboards was straightforward: to provide a functional, intuitive tool that allows users to explore, understand, and compare both financial and demographic metrics across the seven cities within Humboldt County. The financial dashboard provides a glimpse into the fiscal health of the cities for FY 2021, while the demographic dashboard showcases key population and household trends from 2011 to 2021.
The dashboards were designed with a wide array of users in mind, including city officials, policymakers, researchers, and citizens, ensuring that the insights derived are accessible and useful to a diverse audience. The dashboards are interactive tools that empower users to tailor their data exploration according to their specific questions.
The ultimate expectation from these dashboards is to serve as a reliable and accessible data resource that facilitates informed decision-making. By enabling users to visualize and compare various metrics across the cities, I hope the dashboards can foster a data-driven approach towards policymaking, strategic planning, and community discussions.
### Data Collection
#### Financial Data
The financial data was extracted from the Annual Comprehensive Financial Reports of each city, specifically from the Statement of Net Position and the Statement of Activities to calculate financial KPIs for FY 2021. The key ratios computed include the Current Ratio, Unrestricted Net Position Cushion, Debt Burden Ratio, Long-Term Debt to Total Net Position, Operating Margin Ratio, and Debt Per Capita (in US dollars).
#### Choosing and Calculating Financial Ratios
I decided upon six financial KPIs that best represented the financial health of the cities. Each of these sheds light on different aspects of fiscal stability and sustainability. Here’s a glimpse into the specific ratios and my rationale behind choosing them, as well as how to interpret the results:
##### Current Ratio (Total Current Assets/Total Current Liabilities)
This is a measure of liquidity that describes the ability of a city to pay its current debts as they come due. This is calculated by dividing current assets by current liabilities. In the private sector, any current ratio above 2.0 is considered a healthy benchmark. Governments are generally more conservative, so somewhere around 2.5 is more typical. A current ratio below 1 is cause for serious concern, as it signals that the city is unable to meet its short-term obligations.
##### Unrestricted Net Position Cushion (Total Unrestricted Net Position/Total Assets)
This is a measure of comparing the unrestricted net position (the amount of net position not included in the net investment in capital assets, i.e., assets that are not earmarked and can be used for expenses or any other legitimate purpose) as a percentage of Total Assets. This can tell us the cushion a city has against unexpected expenses or revenue shortfalls. In general, a healthy benchmark is approximately 0.15.
##### Debt Burden Ratio (Total Liabilities/Total Assets)
The debt burden ratio assesses the proportion of total liabilities to total assets. A ratio significantly below 0.4 suggests a very strong financial position, indicating assets considerably outweigh liabilities. Ratios significantly higher than this become a cause for concern.
Long-Term Debt to Total Net Position (Total Long-Term Liabilities/Total Net Position)
This metric measures the relationship between a city’s long-term debt and its net position. In general, a reasonable benchmark for this ratio is less than 1, which demonstrates that the net position is greater than the long-term debt. Smaller ratios are more indicative of financial health.
##### Operating Margin Ratio (Changes in Net Position/Total General Revenues)
The operating margin ratio measures a city’s operational surplus relative to its general revenues. Unlike private enterprise, governments are not seeking to maximize their profit margins. However, they can’t continue to serve their citizens adequately when consistently operating at a loss, either. Therefore, a healthy benchmark for this ratio is around 0.05; a slightly positive value is desirable.
##### Debt Per Capita (Total Liabilities/Total Population)
This represents the per-person debt (in USD) within a municipality. This ratio is best analyzed when comparing similar cities in terms of size and location. There aren’t any standardized benchmarks for what constitutes an appropriate, healthy debt per capita amount.  
These ratios were chosen and calculated to provide a comprehensive view of each city's financial health, enabling stakeholders to derive meaningful insights and make informed decisions.

#### Demographic Trends Data
Demographic data was pulled from the U.S. Census Bureau Website, specifically from the annual American Community Survey, covering a decade (2011-2021). The metrics I focused on were population, number of households, Inflation-Adjusted Per Capita Income, Inflation-Adjusted Median Household Income, Median Monthly Gross Rent, and Median Home Value.

#### Demographic Indicators
The U.S. Census Bureau collects a wide swath of data each year via their annual American Community Survey. While this information isn’t as comprehensive as each decade’s census, it does provide numerous metrics to examine. For this project, I chose to look primarily at demographic indicators that related to the economic health of the communities. Thus, I decided to focus on population, number of households, inflation-adjusted median household income, inflation-adjusted per capita income, median monthly gross rent, and median home value. I found these metrics to be the most relevant to the average household’s experience, and understanding how each of these KPIs has changed over time tells us how residents are being affected.

#### Dashboard Design and Development
##### Initial Implementation in Excel
The first iterations of the dashboards were built in Excel. Excel was chosen due to its wide accessibility and familiarity among most stakeholder demographics. The Excel version was then exported to Google Sheets, which allows users who don’t have Excel or Tableau downloaded to intuitively access and understand the dashboard. 

To construct this initial version, data from each city’s financial statements were compiled into different sheets. This includes their complete FY 2021 Statement of Activities and Statement of Net Position. The Balance Sheet and Program Revenues were also included, although these sheets were not used in the final computation of the KPIs included on the dashboard.

The raw financial data from each city’s Annual Comprehensive Financial Report was manually input into Excel. Similarly, the demographic data from the U.S. Census Bureau was also manually entered into the Excel file. Once the data was entered, I was left with a solid foundation for accurate KPI calculations and subsequent visualization.

![image](https://github.com/Wlefils/HumboldtDashboards/assets/98787088/48f894a8-d9ac-4a0c-86b4-b0c818108b38)


The six financial ratios, as detailed previously, were calculated using simple Excel functions. Formulas were crafted to compute each KPI, ensuring precision and consistency across the data set. Excel provided the capability to perform these calculations efficiently and accurately across multiple data points, pulling data from different sheets to calculate the ratios on another sheet. I then created a table on this sheet, calculating the aforementioned KPIs for each city in one central location.
##### Designing Interactive Visualizations
When crafting the financial dashboard in Excel, I used its visualization tools, such as bar charts, to visualize the financial data effectively. I integrated interactive elements, particularly a drop-down menu, to allow users to customize their data view, facilitating a user-friendly experience that enabled easy comparison and analysis across the cities.

![image](https://github.com/Wlefils/HumboldtDashboards/assets/98787088/ae083540-1389-43c1-a908-03b0e134acf3)


To faciliate a deep dive into each city's financial and demographic data, I created summary tables for each city. These tables allow the user to quickly identify the overall change in each metric from 2011 to 2021 and the average annual change during this period. I have also provided detailed annual breakdowns for each year for users who appreciate more granularity.

![image](https://github.com/Wlefils/HumboldtDashboards/assets/98787088/499dda7a-2157-44fe-9f48-b4c6851801ef)


While the Excel/Google Sheets implementation of these dashboards proved useful, I felt that Tableau's features would allow me to create more compelling versions that would further assist users in understanding the cities' situations, particularly in the case of the demographic information. After I'd completed the initial implementation, I imported the Excel file into Tableau and created a separate version of the dashboards that is more aesthetically appealing and intuitive.

![image](https://github.com/Wlefils/HumboldtDashboards/assets/98787088/6cc42cf6-b0e8-49d5-a9a7-6bf6e74e6dc4)


## Conclusion
**Eureka is in a very precarious situation.** Its population has remained stagnant for over 50 years, and has seen decline in the last decade. Inflation-adjusted per capita income and median household income have increased (by 2.71% and 2.70% annually), but only slightly faster than rents have increased during the same time period *(2.37% annually). Property values have similarly increased (0.76% annually), but far slower than the the rest of California, and slower than most of the surrounding cities as well. The aforementioned **pension debt obligations pose a major threat to the continued viability of Eureka as a full-service city.**

**Arcata is in good financial health**, with a steadily increasing population at a rate of 0.9% annually from 2011-2021, higher than the overall growth rate of California during the same period. Both the inflation-adjusted, per capita income and median household income have seen steady annual increases of 2.6% and 2.2% respectively, while median home values have increased by 0.8% and monthly housing costs have gone up by 3.2%. The city's quick ratio improved YOY from 2020 to 2021, indicating a more solvent financial position, however, the city's leverage, debt service to total expenditures, and debt per capita relative to income per capita all increased. The city's primary sources of revenue are grants, sales and use taxes, and property taxes, while expenditures are primarily focused on law enforcement, streets and highways, and city administration. The city also receives material grants from federal, state, and county agencies. Despite the increase in debt, the city's total assets exceeded total liabilities by nearly $109 million in 2021. 

**Fortuna is also in good financial health**. The city’s population increased 4.9% from 2011 to 2021, averaging a 0.5% annual growth rate, higher the state’s average. Both the inflation-adjusted, per capita income and median household income have seen steady annual increases of 3% and 3.7% respectively, while median home values have increased by 0.4 per year% and monthly housing costs have gone up by 3.1% annually. The city’s primary sources of revenue are grants, sales and use taxes, and motor vehicle in-lieu (VLF) funding from the state; property taxes make up only a small portion of revenues. The city’s primary expenditures are in the areas of law enforcement, streets and highways, and city administration. Fortuna has benefitted from the upside of the recovery from the COVID-19 Pandemic. The city continues to remain conservative, but optimistic, in its projections for the next fiscal year, anticipating continued, stable revenue growth.

**Humboldt County's cities are stagnating demographically and economically**. The largest city of Eureka has the worst future outlook, primarily due to its large pension obligations. Arcata is at risk of continued, rapid rent increases due to an influx of students attending the recently rebranded Cal Poly Humboldt and the current lack of housing available. Fortuna appears to be in the best condition overall, with stable growth in both population and income, although its property values are lagging behind. The smaller cities are experiencing varying conditions. Blue Lake's recent drastic population reduction is of significant concern (dropping by over 30% in ten years). Ferndale's negative operating margin is a recent event primarily caused by a large decrease in revenues during the pandemic, and is expected to recover in the next two fiscal years. Rio Dell appears to be in a strong position relative to the other small cities, although the deflation in median household income and median rent is worth noting. Trinidad's small population makes it difficult to draw firm conclusions about its condition.


### External Links
* [Tableau Dashboard](https://public.tableau.com/views/HumboldtCountyCitiesDashboard/FinancialKPIs?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
* [Google Sheets Dashboard](https://docs.google.com/spreadsheets/d/1CLqB5KhHkbXOVqWspcsF-ReAd5riIrxw/edit?usp=sharing&ouid=100312081914865605951&rtpof=true&sd=true)
* [LinkedIn](https://www.linkedin.com/in/will-lefils-57b838132/)
* Resume
* [Portfolio Homepage](https://wlefils.github.io/)
