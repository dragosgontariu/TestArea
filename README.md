# Project Background

# Introduction
<div align="justify">
  
With support from the [Canada Clean Energy and Forest Climate Facility (CCEFCFy)](https://www.worldbank.org/en/topic/climatechange/brief/canada-world-bank-clean-energy-and-forests-climate-facility), the [Geospatial Operational Support Team (GOST, DECSC)](https://worldbank.github.io/GOST) launched the project "Geospatial Assessment of Women Employment and Business Opportunities in the Renewable Energy Sector" in SIDS[^1]. The project aims to propose a novel methodology and generate a geospatial open-source tool for mapping the enabling environments for women in a country that can inform new energy projects to support the advancement of women's economic empowerment in SIDS while contributing to closing gender gaps in employment in the RE sector.

# Project Scope

## 1. Novel Analytical Framework

An extensive literature review, focusing on the barriers women face in securing jobs, particularly within SIDS, was conducted. This comprehensive review resulted in the formulation of a Multicriteria Evaluation (MCE) framework comprising 15 key factors, both spatial and non-spatial, that affect women’s job opportunities. These factors are categorized into three dimensions: **Contextual**, **Accessibility**, and **Place Characterization**. The latter two dimensions concentrate on geographical factors.

For a comprehensive understanding of the Analytical Framework and the associated methodology employed to evaluate women’s spatial access to employment opportunities, please refer to the Methodology Report available at the following link: [Methodology Report](https://documents.worldbank.org/en/publication/documents-reports/documentdetail/099121123091527675/p1792120dc820d04409928040a279022b42)


![Analytical Framework](https://github.com/worldbank/GEEST/blob/main/docs/New%20Pictures/framework.jpg)

## 2. Gender Enabling Environments Tool (GEEST)

Based on the Methodological Framework, the GEEST, an open-source plugin in QGIS, was developed for the automatic computation of the factors and dimensions. The GEEST characterizes communities based on women’s prospects to secure jobs or establish their own businesses within the RE sector. It aims to assist decision-makers in selecting optimal locations for RE projects, ensuring the maximum positive impact on communities and addressing gender disparities. Additionally, it provides insights for building the necessary infrastructure around RE projects to create enabling environments that enhance women’s participation in the RE sector in SIDS.

The GEEST generates raw score outputs for 15 factors outlined in the Analytical Framework. Each of the 15 factors, dimensions, and overall aggregate scores are assessed on a scale ranging from 0 to 5.

![Examples](https://github.com/worldbank/GEEST/blob/main/docs/New%20Pictures/3%20countries%20maps.png)



## 6. Study Case: Saint Lucia

The GEEST was tested Saint Lucia to assess its functionality. The selection of this country was strategic, considering its varied geographic region, size, population densities, and data availability. Testing the GEEST across such a broad range of conditions ensured that its usefulness, applicability, and functionality in different contexts could be accurately tested. The findings and insights derived from the GEEST implementation are documented in the Implementation Report, accessible through the following link: [Implementation Report Saint Lucia.docx](https://worldbankgroup-my.sharepoint.com/:w:/r/personal/civanescu_worldbank_org/Documents/Desktop/Work/Gender/TORs/Task%203/St%20Lucia%20-%20GEEST/Implementation%20Report/Implementation%20Report%20Saint%20Lucia.docx?d=wd12a9d054d5747f49788597e3fdc4ff8&csf=1&web=1&e=q6UcU0)

**GEEST Results in Saint Lucia**

            a. Contextual Dimension

The Contextual Dimension (CD) factors were evaluated using the World Bank's Women, Business, and the Law study, a reputable non-governmental resource that assigns country-level scores ranging from 0 to 100 based on the presence of relevant laws and regulations. Scores for factors in this dimension were standardized on a scale of 0 to 5, with 5 representing the most favorable environment for that specific factor.  

<img src="https://github.com/worldbank/GEEST/blob/main/docs/New%20Pictures/Contextual_new.png" alt="Contextual Image" width="600"/>


            b. Accessibility Dimension

The factors in the Accessibility Dimension were assessed using service areas through network analyses around key facilities, which defined varying levels of access. As anticipated, the highest levels of access to each factor are concentrated in urban centers. Women's Travel Patterns, which relate to essential services needed by women to fulfill their caregiving and household responsibilities, is the factor in this dimension with the fewest highly enabling areas. The latter underscores the need for environments that are better planned with the unique needs and responsibilities of women in mind. This includes ensuring that essential services, such as childcare, pharmacies, and grocery stores, are easily accessible to support women in their roles as caregivers and members of the workforce.

<img src="https://github.com/worldbank/GEEST/blob/main/docs/New%20Pictures/Acc.jpg" alt="Accessibility Image" width="600"/>


            c. Place Characterization Dimension

The Place-Characterization Dimension encompasses seven factors, each evaluated through distinct analytical methods. Notably, the analyses of factors such as Active Transport, Education, and Water and Sanitation reveal some areas where these elements fail to be even moderately supportive of women's access to employment.

<img src="https://github.com/worldbank/GEEST/blob/main/docs/New%20Pictures/PD.jpg" alt="Accessibility Image" width="600"/>


The overall enablement scores for Saint Lucia reveal that, although some areas in the northwest and south exhibit a somewhat supportive environment, the country largely lacks regions that are highly conducive to facilitating women’s access to employment opportunities. Notably, the area around the solar plant in Vieux Fort provides a moderately enabling environment for women's job access, but it still falls short of achieving the highest level of enablement.

<img src="https://github.com/worldbank/GEEST/blob/main/docs/New%20Pictures/WEE%20score%20solar.png" alt="WEE Score Solar" width="600">



When the enablement scores are combined with data on the distribution of women of working age, specifically those aged 35 to 39, across low, medium, and high population densities, it was observed that the most enabling areas on the island corresponded with regions of high female population. However, a few areas with very high population density were identified as having significantly low enablement scores. For example, the area surrounding the solar plant in Vieux Fort is characterized by a high female population density but is classified as only moderately enabling. 
</div>

<img src="https://github.com/worldbank/GEEST/blob/main/docs/New%20Pictures/3D%20Score%20map.png" alt="3D Score Map" width="1000">

[^1]: Eligible SIDS:
Antigua and Barbuda, Belize, Cabo Verde, Comoros, Dominica, Dominican Republic, Federated States of Micronesia, Fiji, Grenada, Guinea-Bissau, Guyana, Haiti, Jamaica, Kiribati, Maldives, Marshall Islands, Mauritius, Nauru, Niue, Palau, Papua New Guinea, Samoa, São Tomé and Príncipe, Solomon Islands, St. Lucia, St. Vincent and Grenadines, Suriname, Timor-Leste, Tonga, Tuvalu, Vanuatu


