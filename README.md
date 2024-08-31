# KARAMOJA_UGANDA_AGRICULTURAL_ANALYSIS


![farmers-1](https://github.com/user-attachments/assets/bf3cb4c2-86f5-4cfd-8ef4-703300b7395e)


## **TABLE OF CONTENT**

1. Business Understanding
2. Business Overview
3. Data Understanding
4. Research Quiz
5. Importing Libraries
6. Loading Data

   i. Assigning the data to a variable

   ii. Exploring the data

8. Data cleaning
9. Data Engineering
10. Data Analysis (EDA)
    
    i. Univariate Analysis

    ii. Bivariate Analysis

11. Feedback Based on my research quiz
12.  Recommendation
13.   Conclusion
14.    Future work and data Engineering   

# **BUSINESS UNDERSTANDING**

Karamoja, the most food-insecure region of Uganda, faces significant challenges in agricultural productivity, due to intense droughts, pest infestations, and disease outbreaks. These factors have led to low crop yields, particularly for staple crops such as sorghum and maize.

While several NGOs are actively providing technical support and farm inputs to farmers in the region, their efforts are hampered by a lack of comprehensive visibility into the overall state of food security. NGOs often rely on localized information, which limits their ability to make informed decisions.

To address this issue, Dalberg Data Insights (DDI) has been requested to develop a food security monitoring tool that can support decision-making for one of the NGOs operating in Karamoja. The tool will leverage satellite imagery to remotely measure crop yields, providing a broader and more accurate understanding of the agricultural landscape in the region.

# **BUSINESS OVERVIEW**

Dalberg Data Insights (DDI) is collaborating with NGOs in Karamoja to enhance food security monitoring through data-driven insights. The methodology developed by DDI’s agri-tech team involves using satellite images to estimate crop yields for sorghum and maize, the two main staple crops in the region. The model has already been tested for the 2017 crop season, providing a foundation for further development.

The next step in this initiative is to create an interactive visualization tool that will serve as a prototype for the final Food Security Monitoring tool. This tool will allow users, specifically the NGO staff, to visualize crop yield data at different administrative levels (district and sub-county). The dashboard should include a map and offer flexibility in terms of how data is displayed, enabling more informed decision-making and resource allocation.

## **RESEARCH QUESTIONS**
The research questions which I will post below some of them will be answered here in this notebook and others in Tableau through Visualizations.

1. HOW CAN POPULATION IMPACT CROP YIELDS?
2. WHAT IS THE PERCENTAGE VALUE MEASURE BY SUBCOUNTY
3. WHICH IS THE BEST PERFORMING CROP AT KARAMOJA
4. WHAT IS THE POPULATION DENSITY OF KARAMOJA?
5. WHAT IS THE CROP PRODUCTION RATIO IN KARAMOJA?
6. WHAT IS THE RATE OF PRODUCTIVITY?
7. IS THERE ANY CORRELATION IN THE DATA?

## **DATA CLEANING**

In this I employed the use of statistical measures such as mean and mode in the filling of the missing values.

# **DATA ANALYSIS (EDA)**

The chart provided represent correlation and this is part of  bivariate analysis.

![CORRELATION](https://github.com/user-attachments/assets/93fbed58-09b1-4e74-bbf0-bf9ec450d184)

Below is the Key to the heatmap for better understanding of the correlation values

0 = This represents no correlation between the values

1 = This means that there is a pefect positive correlation of the data

0.5 = This means that there is a low positive correlation

0.9 = This means that there is a high positive correlation

-0.5 = This represents a low negative correlation

-0.9 = This represents a high negative correlation

-1 = This represents a perfect negative correlation

## **FEEDBACK BASED ON MY RESEARCH QUESTIONS**

In my analysis there is a major difference base on the performance of maize and sorghum in Karamoja. We see that:

1. Maize is the leading crop
2. Abim is the leading subcounty in reference to productivity and population which is at 1,518,982
3. Kabong is the leading district in reference to productivity and population which is at 2,131,662
4. There is correlation for example in sorghum and maize yield per hectare when compared to Area

# **CONCLUSION**
Based on the analysis of crop yield, area, and production data across different districts and sub-counties, it is evident that there are significant disparities in agricultural productivity within the region. Certain areas, such as KAABONG, show potential for increased yield with optimized resource allocation and improved farming practices. Conversely, regions with consistently low yields could benefit from adopting alternative crop types or investing in sustainable farming techniques.

The analysis highlights the need for targeted interventions that account for regional differences in soil quality, climate, and available resources. Implementing data-driven decision-making tools and integrating additional datasets (e.g., weather and soil) will provide more accurate insights and improve agricultural productivity in the region. Future work could focus on predictive modeling to forecast crop yields under different scenarios and to inform policy and resource allocation decisions.

# **RECOMMENDATION**

1. Optimized crop yield management by the farmers.
2. Targeted resource allocation by the NGO at Karamoja to flatten the curve.
3. Address disparities in crop production for higher yields.
4. Encourage crop diversification that will enable income stabilization and reduce risks to be encountered by farmers.



# **FUTURE WORK AND DATA ENGINEERING**

For future work, I would like to do the following if added to the data:

Soil type, in agriculture we are aware that certain crops work best in certain type of soil. The NGO at Karamoja would also have beneficted from this analysis if the data based on soil was available.

Weather and climate intergration, this is also an integral part for agriculture. When weather conditions and climate is favorable to the crops then the farmers would have plenty harvest, am aware it is said that Karamoja is facing drought but it would be best if I had information based on all the seasons experienced at Karamoja for personalized information feeding.

Investment budget: this will help in giving personalized information on areas of farming for higher output per production unit.

For future engineering, I would like to do Matchine Learning models which classify districts and sub-counties based on their levels of procuction and yields.

# LINKS

TABLEAU DASHBOARD: https://public.tableau.com/views/KARAMOJAVISUALIZATIONANALYSIS/KARAMOJADASHBOARDANALYSIS?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

TABLEAU STORY: https://public.tableau.com/views/KARAMOJAVISUALIZATIONANALYSIS/KARAMOJASTORY?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


# **LIBRARIES**

![numpy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)

## **CONTACT**

emmanuelsamuel2523@gmail.com

samuelemmanuel2523@gmail.com
