# **BuenaOla Internship Coding Challenge**

## **Overview**
The objective of this project is to create a regression model that accounts for not only the financial potential but also the environmental impact of various companies.

## **Problem Statement**
It has become increasingly more apparently that the public values an organization's environmental and societal footprint. I have been tasked to explore non-traditional company data and attempt to explain the connection between the data and the financial situation of publicly traded companies in the Russell 2000. By utilizing financial data, environmental impact data, ESG Scores, employee data, employee reviews and public sentiment from news headlines, I hope to provide insight on the importance of non-traditional data in relation to a company's market cap.

## **Repository Contents:**

## **Data Dictionary**
|Feature|Type|Description|
|---|---|---|
|**name**|*str*|The name of the company.|
|**Year**|*int*|The year of the data collected.|
|**Country**|*str*|Country of the company's HQ.|
|**Industry (Exiobase)**|*float*|Exiobase industry category to which the company belongs to.|
|**Environmental Intensity (Sales)**|*float*|The monetized environmental impact of the company divided by revenue of that year.|
|**Environmental Intensity (Op Inc)**|*float*|The monetized environmental impact of the company divided by operating income of that year.|
|**Total Environmental Cost**|*float*|The total monetized environmental impact.|
|**Working Capacity**|*float*|Captures human health effects from climate change, air pollution, and toxicity.|
|**Fish Production Capacity**|*float*|Includes acidification, eutrophication, climate change, and toxicity|
|**Crop Production Capacity**|*float*|Captures soil degradation, air pollution, climate change, and land use.|
|**Meat Production Capacity**|*float*|Includes soil degradation, climate change, land use, and toxicity.|
|**Biodiversity**|*float*|Captures land use and toxicity.|
|**Abiotic Resources**|*float*|Environmental Impact from mining.|
|**Water production capacity (Drinking water & Irrigation Water)**|*float*|Captures climate change, land use, and water pollution.|
|**Wood Production Capacity **|*float*|Captures climate change, air pollution, and land use.|
|**SDG 1.5**|*float*|By 2030, build the resilience of the poor and those in vulnerable situations and reduce their exposure and vulnerability to climate-related extreme events and other economic, social and environmental shocks and disasters.|
|**SDG 2.1**|*float*|By 2030, end hunger and ensure access by all people, in particular the poor and people in vulnerable situations, including infants, to safe, nutritious and sufficient food all year round.|
|**SDG 2.2**|*float*|By 2030, end all forms of malnutrition, including achieving, by 2025, the internationally agreed targets on stunting and wasting in children under 5 years of age, and address the nutritional needs of adolescent girls, pregnant and lactating women and older persons.|
|**SDG 2.3**|*float*|By 2030, double the agricultural productivity and incomes of small-scale food producers, in particular women, indigenous peoples, family farmers, pastoralists and fishers, including through secure and equal access to land, other productive resources and inputs, knowledge, financial services, markets and opportunities for value addition and non-farm employment.|
|**SDG 2.4**|*float*|By 2030, ensure sustainable food production systems and implement resilient agricultural practices that increase productivity and production, that help maintain ecosystems, that strengthen capacity for adaptation to climate change, extreme weather, drought, flooding and other disasters and that progressively improve land and soil quality.|
|**SDG 3.3**|*float*|By 2030, end the epidemics of AIDS, tuberculosis, malaria and neglected tropical diseases and combat hepatitis, water-borne diseases and other communicable diseases.|
|**SDG 3.4**|*float*|By 2030, reduce by one third premature mortality from non-communicable diseases through prevention and treatment and promote mental health and well-being.|
|**SDG 3.9**|*float*|By 2030, substantially reduce the number of deaths and illnesses from hazardous chemicals and air, water and soil pollution and contamination.|
|**SDG 6**|*float*|Ensure availability and sustainable management of water and sanitation for all.|
|**SDG 12.2**|*float*|By 2030, achieve the sustainable management and efficient use of natural resources.|
|**SDG 14.1**|*float*|By 2025, prevent and significantly reduce marine pollution of all kinds, in particular from land-based activities, including marine debris and nutrient pollution.|
|**SDG 14.2**|*float*|By 2020, sustainably manage and protect marine and coastal ecosystems to avoid significant adverse impacts, including by strengthening their resilience, and take action for their restoration in order to achieve healthy and productive oceans.|
|**SDG 14.3**|*float*|Minimize and address the impacts of ocean acidification, including through enhanced scientific cooperation at all levels.|
|**SDG 14.c**|*float*|Enhance the conservation and sustainable use of oceans and their resources by implementing international law as reflected in UNCLOS, which provides the legal framework for the conservation and sustainable use of oceans and their resources.|
|**SDG 15.1**|*float*|By 2020, ensure the conservation, restoration and sustainable use of terrestrial and inland freshwater ecosystems and their services, in particular forests, wetlands, mountains and drylands, in line with obligations under international agreements.|
|**SDG 15.2**|*float*|By 2020, promote the implementation of sustainable management of all types of forests, halt deforestation, restore degraded forests and substantially increase afforestation and reforestation globally.|
|**SDG 15.5**|*float*|Take urgent and significant action to reduce the degradation of natural habitats, halt the loss of biodiversity and, by 2020, protect and prevent the extinction of threatened species.|

Further explanation on how these numbers were derived can be found at Harvard Business School's Research on Corporate Environmental Impact <a href="https://www.hbs.edu/impact-weighted-accounts/Pages/research.aspx">here</a>.

## **Conclusions & Recommendations**

## **Sources**
For Russell 2000 Financial Data:
https://www.suredividend.com/russell-2000-stocks/#excel

For Environmental Impact Data:
https://www.hbs.edu/impact-weighted-accounts/Pages/research.aspx

For ESG Scores:
https://www.refinitiv.com/en/sustainable-finance/esg-scores

For Employee Data & Growth Rates:
https://www.macrotrends.net/stocks/charts/WBT/welbilt/number-of-employees
