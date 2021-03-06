# Economic Inequality and its Dynamics in the United States

**Chun Hin Matthew So - chuns4@uw.edu**

**Sonia Yeh - tzuy3@uw.edu**

**Atreya Bhamidi - abhamidi@uw.edu**

**Johnny Carroll - jcarol17@uw.edu**       

*INFO-201: Technical Foundations of Informatics*  
*The Information School*   
*University of Washington*      
*Winter 2022*  

### Abstract
The COVID-19 pandemic has led to an unprecedented increase in economic inequality in the US. This broadening disparity underlies several social issues plaguing our country, and understanding it could hold the key to the well-being of many groups of people. To analyze trends in and formulate solutions to this inequality, we have looked at a group of datasets containing information on wealth distribution in the US.

**Keywords:** Economy, Inequality, Inequity, Wealth Distribution, Income Distribution, Race, Education, Age.

## Introduction

Throughout the past decade, economic inequality has intensified to levels never seen before.  While there are a variety of potential contributing factors - technological change, globalization, and unfair governmental policy shifts, among many others - financial crises such as the one brought by the COVID-19 pandemic have served to accelerate the widening of the gap between the poor and the rich. This is cause for great concern; with large sections of society being left behind with very little economic opportunity and mobility, countrywide economic growth is negatively impacted, political polarization is deepened, and communal tensions are stoked.

It is thus imperative that socially conscious data scientists analyze the issue of economic inequality. One common way to do so is to collect data regarding distribution of wealth which measures the wealth of a nation including real estate, consumer durables, private businesses, and other financial assets that are distributed among the population. In our project, we look at datasets containing information on wealth distribution by generation, race, education, and income strata. We hope to analyze these datasets to obtain trends in economic inequality over time and identify potential actionable solutions.

## Design Situation

* **Project Framing:**
  There was no preparing for the COVID-19 pandemic.  Closed businesses left individuals unemployed while also battling the everyday hardships of the pandemic such as illness, medical bills, and overall uncertainty.  Wealth inequality in the United States has always been high, but with the shock created by covid, our group wanted to examine the effects of the pandemic on this distribution.  By understanding how different groups of people were affected by the pandemic we are able to see if some people are systematically better or worse equipped for the pandemic.  Finally, the better we understand the needs of individuals, the more likely we are to be able to implement effective policies to help them in times of need.

* **Human Values:**
At the core of this project is the value that community brings to a group.  Communities provide individuals with a sense of belonging as well as a support system to help achieve individual goals.  These goals come from the inalienable rights to life and liberty that all people have.  In order to strengthen communities and empower individuals to achieve their goals, it is important to know which individuals may need additional support in order to gain equal opportunity. This sense of community is bolstered by the other core value of our project, equity. While inequality is incredibly difficult to completely snuff out, providing opportunities to those who need them forms the basis of equity and communal harmony.

* **Stakeholders:**
The primary stakeholders in this situation are the individuals that will be using this data.  These would be individuals such as policy makers and non-government organizations who design policies and social programs in order to support those who can???t support themselves.  Indirect stakeholders include the individuals who are unable to purchase everyday necessities due to hardship brought on by the pandemic. Other indirect stakeholders are individuals who have more than they might need as programs may target their money.    

* **Benefits and Harm:**
If intervention is taken, the group that was least prepared for the COVID-19 pandemic would likely become much more equipped for future situations as the intervention would likely be a program designed to provide relief funds for these people. This would keep communities working at maximum efficiency even when not all people are able to work. Upper Class families would likely be at least moderately impacted by any intervention as wealth would be redistributed, or systematic advantages would be reduced. Similarly, they may choose to move their capital elsewhere to avoid regulation. Finally, the government and nation as a whole would likely benefit from increased equality among constituents as this would promote financial and economic stability.

* **Background sources**
  - https://www.federalreserve.gov/econres/notes/feds-notes/wealth-inequality-and-covid-19-evidence-from-the-distributional-financial-accounts-20210830.htm
  - https://www2.deloitte.com/us/en/insights/economy/issues-by-the-numbers/covid-impact-on-income-inequality.html
  - https://www.cbpp.org/research/poverty-and-inequality/tracking-the-covid-19-economys-effects-on-food-housing-and)

## Research questions

Economic inequality is at the root of many social issues. By looking into such inequality, we are able to examine people???s quality of life and predict determinants of the health and well-being of individuals and families. Looking at how economic well-being in the United States varies with social factors such as age/generation, race/ethnicity, income levels, and education will give us a glimpse into the stratification of American society and a basis to formulate potential solutions to this pressing problem. Some guiding questions that formed the basis of our research are as follows:

1. How has the distribution of wealth in the United States changed over the last decade?

2. How does the distribution of wealth vary with an individual???s level of education? What are the education dynamics observed from the dataset?

3. How does the distribution of wealth vary with race? What are the racial or ethnic dynamics observed from the dataset?

4. How has the COVID-19 pandemic affected wealth and income distribution? How do these observed dynamics vary between the start (2019/2020) and the middle (2021) of the pandemic?


## The Data

The primary dataset, titled Distributional Financial Accounts (DFA) - Income Levels, consists of 14 variables/attributes (columns) and 517 observations (rows). The secondary datasets, DFA - Net Worth Levels, Race Levels, and Education Levels, are identical in dimensions and complexity. Each of these datasets contains the same variables but varies in observations based on the entries in the second column, ???Category.??? Thus, they are set up for comparative analysis along specific categorizations of interest.

* **Who or what is represented in the data?**

  The data paints a picture of the distribution of household wealth in the United States since 1989. It represents the household wealth statistics of 6500 families surveyed as part of the triennial Survey of Consumer Finances (and other families like them).

* **What is an observation? What variables are included?**

  Each observation contains data on net worth by category and fiscal quarter/year. Categories follow the titles of each of the datasets: the Networth Levels dataset contains categories ???Top1,??? ???Next9,??? ???Next40,??? and ???Bottom50,??? dividing households into groups based on percentiles of net worth. Similarly, the other datasets have categories dividing households into groups based on race, education levels, and income levels.

* **Each dataset has 14 variables:**
  1. Date: Year and Fiscal Quarter (ex: 1994:Q3)
  2. Category: Varies by dataset (ex: Bottom50, Asian)
  3. Net Worth: Assets - Liabilities, Dollars
  4. Assets: Dollars, with 6 subsections as additional variables
  5. Real Estate: Dollars
  6. Consumer Durables: Dollars
  7. Corporate Equities and mutual fund shares: Dollars
  8. Pension Entitlements: Dollars
  9. Private businesses: Dollars
  10. Other Assets: Dollars
  11. Liabilities: Dollars, with 3 subsections as additional variables
  12. Home Mortgages: Dollars
  13. Consumer Credit: Dollars
  14. Other liabilities: Dollars


* **Who collected the data? How was the data collection effort funded?**

  The data was collected by the National Opinion Research Center (NORC) at the University of Chicago, and is sponsored by the Federal Reserve Board in cooperation with the Department of the Treasury. Data from the SCF, is used by a multitude of organizations, from analysis by the Federal Reserve and news organizations to research by universities and economic research centers. More information the source of the data and the SCF can be found at this [link](https://www.federalreserve.gov/econres/aboutscf.htm).

* **How was the data validated and held secure? Is it credible and trustworthy?**

  The SCF website describes in detail their policies regarding data confidentiality and security. Per their [website](https://scf.norc.org/DataSecurityandPrivacy.html) they utilize a multi-tiered approach to manage issues associated with computer and data security. Personally Identifiable Information (PII) is used only to contact survey respondents and is fully anonymized before providing the data to the SCF sponsor, the Federal Reserve Board. In their surveys, the NORC is in compliance with several federal regulations on information security and management, primarily the Federal Information Security Management Act (FISMA) and many others.

  The NORC and Federal Reserve make concerted efforts to ensure that the study is representative of households from all economic strata. Households are randomly selected as per guidelines laid out in working papers on the [Federal reserve website](https://www.federalreserve.gov/econres/scf_workingpapers.htm) with the intention to represent the full range of households in the United States. As per the Federal Reserve, ???to maintain the scientific validity of the study, interviewers are not allowed to substitute respondents for families that do not participate. Thus, if a family declines to participate, it means that families like theirs may not be represented clearly in national discussions.??? Thus, the representativeness of the data is impacted by households that do not participate, but on the whole, there seem to be extensive measures taken to safeguard the credibility, security, and validity of the data.

* **How did you obtain the data?**

  Through a search for federal data on economic inequity, we came upon the Federal Reserve???s interactive data visualization titled ???Distribution of Household Wealth in the U.S. since 1989??? found at this [link](https://www.federalreserve.gov/releases/z1/dataviz/dfa/distribute/chart/#quarter:128;series:Net%20worth;demographic:networth;population:all;units:levels;range:2006.3,2021.3 ).

  The visualization offered publicly downloadable data sets on each of the categories mentioned above.

  Each observation contains data on net worth by category and fiscal quarter/year. Categories follow the titles of each of the datasets: the Networth Levels dataset contains categories ???Top1,??? ???Next9,??? ???Next40,??? and ???Bottom50,??? dividing households into groups based on percentiles of net worth. Similarly, the other datasets have categories dividing households into groups based on race, education levels, and income levels.

* **Each dataset has 14 variables:**
  1. Date: Year and Fiscal Quarter (ex: 1994:Q3)
  2. Category: Varies by dataset (ex: Bottom50, Asian)
  3. Net Worth: Assets - Liabilities, Dollars
  4. Assets: Dollars, with 6 subsections as additional variables
  5. Real Estate: Dollars
  6. Consumer Durables: Dollars
  7. Corporate Equities and mutual fund shares: Dollars
  8. Pension Entitlements: Dollars
  9. Private businesses: Dollars
  10. Other Assets: Dollars
  11. Liabilities: Dollars, with 3 subsections as additional variables
  12. Home Mortgages: Dollars
  13. Consumer Credit: Dollars
  14. Other liabilities: Dollars

* **Who collected the data? How was the data collection effort funded?**

  The data was collected by the National Opinion Research Center (NORC) at the University of Chicago, and is sponsored by the Federal Reserve Board in cooperation with the Department of the Treasury. Data from the SCF, is used by a multitude of organizations, from analysis by the Federal Reserve and news organizations to research by universities and economic research centers. More information the source of the data and the SCF can be found at this [link](https://www.federalreserve.gov/econres/aboutscf.htm).

* **How was the data validated and held secure? Is it credible and trustworthy?**

  The SCF website describes in detail their policies regarding data confidentiality and security. Per their [website](https://scf.norc.org/DataSecurityandPrivacy.html) they utilize a multi-tiered approach to manage issues associated with computer and data security. Personally Identifiable Information (PII) is used only to contact survey respondents and is fully anonymized before providing the data to the SCF sponsor, the Federal Reserve Board. In their surveys, the NORC is in compliance with several federal regulations on information security and management, primarily the Federal Information Security Management Act (FISMA) and many others.

  The NORC and Federal Reserve make concerted efforts to ensure that the study is representative of households from all economic strata. Households are randomly selected as per guidelines laid out in working papers on the [Federal reserve website](https://www.federalreserve.gov/econres/scf_workingpapers.htm) with the intention to represent the full range of households in the United States. As per the Federal Reserve, ???to maintain the scientific validity of the study, interviewers are not allowed to substitute respondents for families that do not participate. Thus, if a family declines to participate, it means that families like theirs may not be represented clearly in national discussions.??? Thus, the representativeness of the data is impacted by households that do not participate, but on the whole, there seem to be extensive measures taken to safeguard the credibility, security, and validity of the data.

* **How did you obtain the data?**

  Through a search for federal data on economic inequity, we came upon the Federal Reserve???s interactive data visualization titled ???Distribution of Household Wealth in the U.S. since 1989??? found at this [link](https://www.federalreserve.gov/releases/z1/dataviz/dfa/distribute/chart/#quarter:128;series:Net%20worth;demographic:networth;population:all;units:levels;range:2006.3,2021.3 ).

  The visualization offered publicly downloadable data sets on each of the categories mentioned above.


## Findings

We had hoped to use our research questions as guiding directives to analyze general trends in economic inequality in the US. The broad outcome of our analysis not unexpected but still quite alarming: *inequality in the United States has increased across various demographic metrics*.

For our first question, we wanted to look at **general patterns in wealth inequality in the last decade** (from 2011 to 2021). We found that there has been an increasing concentration of wealth among the top 1 percentile of income earners, with the bottom 20 percentile being left far behind and the gap between them widening. Here are some data points which give a quick view of the distribution of wealth, with the income percentile that each group constitutes along with the amount of wealth they possess.

>2011 - Top 1 percentile controls 21.14% of wealth
80-99 percentile controls 46.5% of wealth
Bottom 20% controls 3.4% of wealth
>
>2016 - Top 1% controls 24.2% of wealth
80-99 percentile controls 47.05% of wealth
Bottom 20% controls 2.27%
>
>2021 - Top 1% controls 26.9% of wealth
80-99 percentile controls 43.55% of wealth
Bottom 20% controls 2.8% of wealth

From this data, it is evident that wealth in the US is being more and more concentrated at the top, with just 1 percent of the population controlling upwards of a quarter of household wealth, increasing from a fifth in 2011. The 20% of the American population with the lowest income controls less than 3% of household wealth.

For our second question, we were looking at the concentration of wealth by level of education. We found that graduates of colleges or other higher education institutes controlled 87.8% of household wealth despite comprising only about 37.5% of the population. People whose highest level of education was high school controlled 10.6% of household wealth.

For our third question, we wanted to look at the distribution of wealth by race in the US. We found that the white racial group, which comprises 71% of the US population, controls 83.7% of the household wealth, while the black racial group, comprising 14.2% of the population, controls 4.3% of the household wealth. The Hispanic racial group, comprising 18.7% of the population, controls 2.7% of the household wealth.

Comparing trends across datasets for our fourth question, we found that the COVID-19 pandemic has exacerbated inequity in the US. The difference in the percentage share of wealth controlled by the top 1% and the bottom 20% was 24.01% in the 3rd Quarter of 2021, an increase from 2018's value of 21.09%.



## Discussion

From our observations and analysis of the datasets, we notice the magnitude and prevalence of specific groups of people controlling amounts of wealth disproportionate to their share in the US population  - the top 1% of income earners, a third of the US population that had a college level education possessing, the white population, and more. This has come at incredible cost to sections of the population that are not as prosperous - the working class, high school-educated or less-educated individuals, racial minorities, and others. The disparities are exacerbated by economic disruptions, especially large-scale ones such as the COVID-19 pandemic. It is further evident that economic inequities and their negative consequences are intersectional and cut across social, ethnic, and cultural divisions.

Based on our current assessment of the sociopolitical landscape in the US, we have identified some possible avenues for economic inequality reduction that might warrant consideration. Primarily, the rapid, pervasive digitization of the world economy induced by the pandemic has necessitated high-speed internet and computers for nearly all learning and working environments. However, access to such technology is dictated to a great extent by economic well-being, and is very limited for people in lower wealth strata. Therefore, technologists have the prime opportunity to improve technological equity through widening high-speed internet reach and programs such as renting out affordable computers near low-income areas. Educators, designers, and technologists can collaboratively utilize this broadened network to design and provide educational content to enable individuals from lower socioeconomic backgrounds to learn new skills, thus improving social mobility. Policymakers can use wealth distribution data to inform their processes of developing social programs such as such as subsidies toward affordable technology, rent and eviction moratoriums, public transportation systems, and unemployment assistance. Importantly, analyses of wealth distribution such as this would give policymakers an important reference point when redesigning taxation systems in the US.



## Conclusion

Economic inequity has increased dramatically over the last three decades, and its negative consequences are disproportionately suffered by disadvantaged groups - low income earners, racial minorities, and people with lower education levels, among others. These groups are most commonly on the receiving end of poverty, unemployment, lack of access to quality healthcare and food, and reduced educational and occupational prospects, all of which are self-reinforcing and intergenerational. Analyses of wealth distribution provide valuable insight to policymakers on potential steps to take to close the gap between the privileged and the struggling, and help inspire positive outcomes for victims of longstanding inequities.



## References

- Batty, M., Deeken, E., & Volz, A. H. (2021, August 30). Wealth inequality and covid-19: Evidence from the distributional financial accounts. The Fed - Wealth Inequality and COVID-19: Evidence from the Distributional Financial Accounts. Retrieved February 6, 2022, from
https://www.federalreserve.gov/econres/notes/feds-notes/wealth-inequality-and-covid-19-evidence-from-the-distributional-financial-accounts-20210830.htm

- Board of governors of the Federal Reserve System. (2017, March 16). Retrieved February 6, 2022, from https://www.federalreserve.gov/econres/aboutscf.htm

- Board of governors of the Federal Reserve System. (2021, February 23). Retrieved February 6, 2022, from https://www.federalreserve.gov/econres/scf_workingpapers.htm

- Board of governors of the Federal Reserve System. The Fed - Distribution: Distribution of Household Wealth in the U.S. since 1989. (2021, December 17). Retrieved February 6, 2022, from https://www.federalreserve.gov/releases/z1/dataviz/dfa/distribute/chart/#quarter:128;series:Net%20worth;demographic:networth;population:all;units:levels;range:2006.3,2021.3

- Buckley, P., Barua, A., & Samaddar, M. (2021, November 10). US income inequality after the pandemic. Deloitte Insights. Retrieved February 6, 2022, from https://www2.deloitte.com/us/en/insights/economy/issues-by-the-numbers/covid-impact-on-income-inequality.html

- NORC at the University of Chicago. (n.d.). Data security. SCF. Retrieved February 6, 2022, from https://scf.norc.org/DataSecurityandPrivacy.html
- Tracking the COVID-19 economy's effects on food, housing, and employment hardships. Center on Budget and Policy Priorities. (2021, November 10). Retrieved February 6, 2022, from https://www.cbpp.org/research/poverty-and-inequality/tracking-the-covid-19-economys-effects-on-food-housing-and
