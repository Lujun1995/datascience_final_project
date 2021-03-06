Data science final project proposal
================
Yun He, Jun Lu, Chu Yu, Chunxiao Zhai, Haoran Hu
2018-11-4

The tentative project title
---------------------------

Obesity rate in New York City School Children : the problem of misclassification and under-estimation in Asian group.

The group members (names and UNIs)
----------------------------------

Chunxiao Zhai UNI: cz2544, Jun Lu UNI: jl5297, Haoran Hu UNI: hh2767, Yun He UNI: yh3094 Chu Yu UNI:cy2522

The motivation for this project
-------------------------------

It has been long recognized that childhood overweight and obesity will continue to adulthood. Strongly associated with diabetes, cardiovascular disease, cancer, and mental social wellbeing, obesity is among top public health concerns in the US and around the world. We found several projects monitoring weight and obesity rate in schools, along with diets and behavior data. Big efforts have been made to fight the obesity pandemic, the obesity rate in NYC school children have dropped. But is it a true drop or just demographic change?

The genetic background play a major role in the development of obesity along with diet and lifestyle. Researches have found that asian children and adults have significantly lower obesity rate than other races by current BMI criteria (overweight (BMI ≥25 kg/m2) or obese (BMI ≥30 kg/m2)) \[1\], however the risk to develop type 2 diabetes has been increasing among asians around the world. Researches suggest that to evaluate risk of disease, the BMI cut-off values should be lower for asians due to higher body fat percentage and higher percentage of visceral/peripheral distribution (overweight (BMI ≥22-23 kg/m2) or obese (BMI ≥25-28 kg/m2)) \[2\].

There is a great heterogeneity among different Asian groups \[3\]. With change in immigration trends in recent years, we are interested in examining if current decline in NYC school student obesity rate is affected by changes in school demographic features and misclassification of weight status in Asian population \[4\]. If the popularity of behavior causes of obesity like sugery drinks and lack of physical activity have not changed, have we really get the rapid increase of obesity rate in control ? If the misclassification of weight status in Asian resulted in under-diagnosis of overweight and obesity and delayed medical intervention, what is the potential loss and medical cost caused by this problem ?

\[1\] <https://www.cdc.gov/nchs/products/databriefs/db288.htm> \[2\] <http://care.diabetesjournals.org/content/38/1/150> \[3\] <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4410367/> \[4\] <https://www.apiahf.org/resource/obesity-and-overweight-among-asian-american-children-and-adolescents/>

The intended final products
---------------------------

We expect to map the obesity rate across school district along with the student demographic change in recent years in New York city. It will be a challenge to match demographic data and geographic information in different datasets.

We want to compare overall health of students in schools with different scores, location and other factors:

First, we plan to build a shinny map to describe the geographical distribution of the schools and their obesity rates. Then make plots to demonstrate if there is association in students obesity rate with school meals, school scores, try to build a progressive regression model consider covariants of age, gender, race and social-economical status. All the visualization will be made in R.

As is written above, we are intended to provide a product with diverse plots describing the over three datasets visually, and then build a website to present our results of exploring the data. According to the requirements, we will also submit our reports about the project. Hope finally we can present a clear and logical product to interpret our results of the project.

The anticipated data sources
----------------------------

Our anticipated data source is several datasets on adolecent obesity provided by "Health data NY" website, which is an open data site maintained by the New York State Department of Health devoted to providing access to health data.\[3\] We also found a dataset on NYC Opendata, which provides information of each school in New York city. In total, we got the following datasets:

1.A school demographic dataset. This dataset shows information of students such as sex ratio, race ratio, etc.link: <https://data.cityofnewyork.us/Education/2013-2018-Demographic-Snapshot-School/s52a-8aq6>

2.Datasets containing the prevalence of obesity among students in a certain county. <https://www.health.ny.gov/prevention/obesity/statistics_and_impact/student_weight_status_data.htm> <https://health.data.ny.gov/Health/Student-Weight-Status-Category-Reporting-System-20/rygz-8yax>

3.NYC community health datasets: <https://www1.nyc.gov/assets/doh/downloads/excel/episrv/2015_CHP_PUD.xlsx> <https://a816-healthpsi.nyc.gov/epiquery/>

4.A dataset showing location of each school.link: <https://data.cityofnewyork.us/Education/2017-2018-School-Locations/p6h4-mpyy>

5.Cencus data about Asian population: <https://www.census.gov/prod/cen2010/briefs/c2010br-11.pdf>

The planned analyses / visualizations / coding challenges
---------------------------------------------------------

We plan to focus on three main problems:

1.  find the tendency of how the obesity rate in different school districts change over years considering the demographic changes.
2.  visualize the school location and corresponding obesity rate on the map.
3.  find the overall association between students' obesity rate and nutritional and lifestyle factors (sugary drinks, exercise time etc).

The planned timeline
--------------------

| Date                | Plan                                  |
|---------------------|---------------------------------------|
| November 12 7:00 pm | Project review meeting                |
| November 12-15      | Read and clean the data               |
| November 15-18      | Exploratory analyses                  |
| November 19-23      | Linear model analyses                 |
| November 24-26      | Write a report                        |
| November 27-30      | Build a website and make a screencast |
