# ESG-Analysis

The climate crisis is one of the greatest global challenges today. However, support for pro-environmental policies is often lacking. One factor driving environmental attitudes and behaviours is residence, which assumes that residing in a city or in countryside should have an impact on pro-environmental stances and action (Gifford, Nilsson 2014). On one hand, some scholars proposed that residents of rural areas are more likely to be negatively impacted by climate change (Arndt et al. 2022), have a stronger connection to nature and feel a moral responsibility, making them more pro-environmental (Berenguer and Corraliza 2005, Gifford and Nilsson 2014). On the other hand, some studies show evidence to the contrary (e.g. Anderson and Krettenauer 2021), and propose that the availability of environmental initiatives, education and socialization in the cities makes urban residents more pro-environmental (Yu 2014, Lowe and Pinhey 1982).

## Data

To test our hypothesis, we employ data from the European Social Survey (ESS) Round 8 from 2016 (ESS ERIC. 2023. ESS8). The ESS is a cross-national survey covering most European countries and measures a wide array of public attitudes on political and social issues. The ESS Round 8 covers 23 European countries. As our scope is limited to countries that geographically lie entirely in Europe we exclude Israel and the Russian Federation but keep all other countries (Austria, Belgium, Switzerland, Czechia, Germany, Estonia, Spain, Finland, France, United Kingdom, Hungary, Ireland, Iceland, Italy, Lithuania, Netherlands, Norway, Poland, Portugal, Sweden, Slovenia). Within each participating country, the survey employs random probability sampling (ESS ERIC, 2024). This means that it should reflect the socio demographic makeup of the sampled countries, allowing us to generalise to the entire country and rule out selection biases usually associated with non-random sampling. However, as the countries included in the ESS classify as so-called ‘WEIRD’ countries, we should refrain from generalizing our results to populations beyond Europe.

## Variables

**DV 1: Environmental attitudes**
- How worried are you about climate change? (1-5 scale, variable name: '**wrclmch**')
- How much have you thought about climate change before today? (1-5 scale, variable name: '**clmthgt2**')
- How good or bad do you think the impact of climate change will be on people across the world? Please choose a number from 0 to 10, where 0 is extremely bad and 10 is extremely good? (0-10 scale, reverse-coded by the authors to range from 0 (good) to 10 (bad), variable name: '**ccgdbd_reversed**')

**DV 2: Environmental behaviours**
- If you were to buy a large electrical appliance for your home, how likely is it that you would buy one of the most energy efficient ones? (0-10 scale, variable name: '**eneffap**')
- There are some things that can be done to reduce energy use, such as switching off appliances that are not being used, walking for short journeys, or only using the heating or air conditioning when really needed. In your daily life, how often do you do things to reduce your energy use? (1-6 scale, variable name: '**rdcenr**')
- To what extent do you feel a personal responsibility to try to reduce climate change? (0-10 scale, variable name: '**ccrdprs**')

**World Bank Data about Educational Attainment**
- Educational attainment, at least completed lower secondary, population 25+, total (%) (cumulative)
## Hypotheses


**Sub-question 1:** How do urban and rural residents differ in their pro-environmental attitudes?
- H1.0: There is no difference in the environmental attitudes of urban and rural residents.
- H1.A: There is a difference in the environmental attitudes of urban and rural residents.

**Sub-question 2:** How do urban and rural residents differ in their pro-environmental behaviors?
- H2.0: There is no difference in the environmental behaviour of urban and rural residents.
- H2.A: There is a difference in the environmental behaviour of urban and rural residents.

_Additionally,_ the difference in environmental attitudes and behaviours between rural and urban residents may differ between countries, for instance because of different cultures, political debates, or infrastructure. Thus, to identify if there are European countries where the gap is greater or smaller in regards to our main relationship of interest, we ask a third sub-question.

**Sub-question 3:** What are country-level differences in environmental attitudes and behaviours?
- H3.0: There is no difference in the gap of environmental attitudes/behaviours of urban and rural residents between countries.
- H3.A: There is a difference in the gap of environmental attitudes/behaviours of urban and rural residents between countries.

_Further_ diving into context effects, countries with lower educational attainment may have larger urban-rural disparities in environmental education. This would also lead to a greater division in environmental attitudes and behaviours, between cities and the countryside, as some authors postulate that environmental education is the main factor mediating this relationship (Yu 2014). Thus, we ask a fourth sub-question.

**Sub-question 4:** Does the overall level of educational attainment in a country influence the urban-rural differences between environmental attitudes and behaviors?
- H4.0: There is no difference in the gap of environmental attitudes/behaviours of urban and rural residents between countries with high or low educational attainment.
- H4.A: There is a difference in the gap of environmental attitudes/behaviours of urban and rural residents between countries with high or low educational attainment.

**References**

Anderson, Daniel J., and Tobias Krettenauer. 2021. "Connectedness to Nature and Pro-Environmental Behaviour from Early Adolescence to Adulthood: A Comparison of Urban and Rural Canada" Sustainability 13, no. 7: 3655. https://doi.org/10.3390/su13073655

Arndt, Christoph, Daphne Halikiopoulou, and Christos Vrakopoulos. 2022. “The Centre-Periphery Divide and Attitudes towards Climate Change Measures among Western Europeans.” Environmental Politics 32 (3): 381–406. doi:10.1080/09644016.2022.2075155.

Berenguer, Jaime, José Corraliza, and Rocío Martín. 2005. "Rural-Urban Differences in Environmental Concern, Attitudes, and Actions." European Journal of Psychological Assessment 21 (2): 128–138. https://doi.org/10.1027/1015-5759.21.2.128.

ESS ERIC. 2024. Sampling.
https://www.europeansocialsurvey.org/methodology/ess-methodology/sampling

ESS ERIC. 2023. ESS8 - integrated file, edition 2.3 [Data set]. Sikt - Norwegian Agency for Shared Services in Education and Research. https://doi.org/10.21338/ess8e02_3.
Wu, Huiping, and Shing-On Leung. 2017. “Can Likert Scales Be Treated as Interval Scales?—A Simulation Study.” Journal of Social Service Research 43 (4): 527–32. doi:10.1080/01488376.2017.1329775.
Gifford, Robert, and Andreas Nilsson. 2014. “Personal and Social Factors That Influence Pro-Environmental Concern and Behavior: A Review.” International Journal of Psychology 49 (3): 141–157. https://doi.org/10.1002/ijop.12034.

Lowe, George D., and Thomas K. Pinhey. "Rural-urban differences in support for environmental protection." Rural Sociology 47, no. 1 (1982): 114.
Yu, Xueying. “Is Environment ‘A City Thing’ in China? Rural–Urban Differences in Environmental Attitudes.” Journal of Environmental Psychology 38 (June 2014): 39–48. https://doi.org/10.1016/j.jenvp.2013.12.009. 
