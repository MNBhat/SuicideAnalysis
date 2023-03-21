## Section 1 Motivation and Purpose

Our role: Data Science research group interested in suicide rates

Target audience: Research students in mental health, mental health practitioner 

Mental health crisis is now rise with the increase in the possibilities of suicide  among people. Student doing research in mental health, practitioners  are trying to understand the rate of the suicide among people, if there are any patterns in the suicides  and the factors associated with it. Our dashboard aims to provide an interactive tools for users to observe the rates of the suicide across world and countries separately. We aim to explore the prevalence of  suicides among various age groups, gender and the countries. We will provide the visualization to analyze the pattern in the suicides rate across the years , and further explore it  by gender, age and gdp of the country.

## Section 2 Description of Data
In this project , we are using the Suicide Rate Overview dataset ate which is available on [Kaggle](https://www.kaggle.com/datasets/russellyates88/suicide-rates-overview-1985-to-2016). This data set has been compiled from the other datasets linked in time and place, using United Nations Development program, World Health Organization Suicide prevention, WHO along with World Bank, world development factors  being a few. The dataset , contains the suicide information for years 1985 to 2016, however in per dataset we would be using since 2006 due to the memory requirements. The dataset has the following features :
- Country 
- Year 
- Sex -(As given in dataset)
- Age - age group of the people 
- Suicide nos -  number of suicides in the particular year
- Population  - population in the year 
- suicides/100k pop - suicide per 100k population
- Country-year - year and country 
- HDI for year - human development index for that year 
- Gdp_for_year - gdp for that year 
- Gdp_per_capita - gdp per capita for that year 
- Generation - generation belonging

For our analysis, we would be using the features: `country`, `year`, `sex`, `age`, `suicides/100k pop`, `gdp_per_capita`.

## Section 2 Research Questions and usage Scenarios

Some of the questions that could be potentially answered by the dashboard could be as : 
- Are suicide rates more prevelant in certain age groups? 
- Is suicide rate in a country impacted by its gdp?
- Are suicide rates decreasing or increasing in a country?
- Is suicide  more common in a certain gender ? 
- Which country has a highest suicide rate ?

Usage Scenario can be described as follows: 

Bella is a graduate student (or a practitioner) who wants to conduct research on the suicide rate in various age groups throughout numerous nations. This research could aid her in coming up with strategies to connect with people and provide them with assistance.
She wants to know if younger people are more likely to commit suicide than older people so she can focus on that group with preventive measures, as each group has diverse needs and would require a distinct kind of intervention. She also wonders whether the rates are varying with the nation's GDP. Our app assists her in providing insight into suicide across nations, subsequently separated by age, gender, and GDP of the country. Bella can select a particular country that interests her, and suicide rates for that country will be plotted across the years. Further, to know about the suicide rate by gender, age, or GDP, she can select them from a drop-down option, and suicide rates would be broken down by that group. She can check the worldwide rates by gender and age as well.



