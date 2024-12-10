# STOR 320: Introduction to Data Science

Submit to gradescope by 11:59 PM, Dec 09, 11:59 PM.

## Final Paper Group 7

## Group members: Ivy Nangalia, Ximing Sun, Kharan Joshi, Alisha Nazir

## Introduction

Homelessness is a pervasive issue affecting communities in the U.S., yet its patterns and causes remain complex and multifaceted. By analyzing trends in the homeless population and identifying factors contributing to homelessness, we can better understand this pressing social challenge and inform strategies to mitigate it. Our project focuses on two critical questions: 

1. *What trends exist in the homeless population, and how does geography affect these trends?*  
2. *Are race, age, and gender good predictors of homelessness?* 

These questions aim to uncover hidden patterns and provide actionable insights for policymakers, social service providers, and others working to reduce homelessness.

The first question delves into the geographical dynamics of homelessness. Understanding how homelessness varies by region, urban density, and local economic conditions is essential for designing targeted interventions. For instance, homelessness in urban areas may be driven by high housing costs, while in rural regions, it may be linked to a lack of access to resources. Exploring these geographical nuances reveals where the problem is most severe and helps identify the unique factors driving homelessness in different areas. This insight is invaluable for organizations allocating resources and developing region-specific solutions.

The second question examines the role of demographic factors—race, age, and gender—in predicting homelessness. These characteristics often intersect with systemic inequalities, shaping individuals' vulnerability to housing instability. We can identify high-risk groups and address underlying disparities by investigating these predictors. For example, if specific demographics are disproportionately affected, understanding the reasons behind this can inform equitable policy reforms and foster more inclusive support systems. This analysis also has implications for advocacy, highlighting populations needing urgent attention and resources.

These questions are both intellectually intriguing and socially significant. For the owner of the data, uncovering these insights could enhance the utility and impact of their data, guiding evidence-based decision-making and fostering partnerships with stakeholders. For the country at large, the answers hold promise for addressing one of the most visible and urgent manifestations of poverty and inequality. By answering these questions, our project aims to contribute to the collective effort to end homelessness and improve the lives of vulnerable populations worldwide.

## Data

The data we used to answer our research question, "What trends are there in the number of homeless people, and how do geographical factors affect these trends?" is from HUD, the U.S. Department of Housing and Urban Development. We used the Point-in-Time (PIT) Count and Housing Inventory Count (HIC) records, which show how many homeless people there are in the U.S. on one night in January every year. Surveys, observations by trained volunteers, and study in public databases are some of the ways the data is gathered. Local Continuums of Care (CoCs) keep an eye on all of it. Local governments, nonprofits, and housing providers are some of the groups that make sure the data is consistent and reliable so that it can be used to make comparisons over time and between areas. The structured and consistent data collection process from HUD allows us to confidently analyze trends across time and regions, making it easier to identify areas and populations most affected by homelessness.

The data set has a lot of variables but we used a few main variables, like race, ethnicity, gender, and age. It also has information about where the people live, such as state-level data and whether the places are urban, suburban, or rural. It also tells the difference between homeless people who are housed and those who are not, which helps show differences in living conditions. This is a detailed picture of homelessness in the U.S. at a certain point in time, meaning each observation is a person or family that was counted during the PIT survey. By separating the data by location and population, we can see patterns. For example, the high number of homeless people on the West Coast is likely due to the high cost of living, and Black and Hispanic people are overrepresented in states like New York, Texas, and California. Our study of differences in homelessness and how geography plays a part is directly linked to this knowledge. Clustering can happen in places with a lot of people or expensive homes, and it's common for people of certain races or ethnicities to be affected more than others. The collection also gives us a way to look into trends over time or more specific patterns in space. This makes it an important tool for learning about homelessness and what causes it.

The bar chart illustrates the distribution of homeless individuals by racial categories across different U.S. states, as reported in the HUD Point-in-Time (PIT) Count. It highlights racial disparities, showing that states like California and New York have significantly higher homelessness counts, particularly among Black, White, and Hispanic populations.

The table provides a detailed breakdown of the homeless population by race across various states, categorizing groups such as White, Black or African American, Asian, and others. This data shows the overrepresentation of certain racial groups, such as Black or African American individuals, in states like California, Texas, and Florida, offering a more granular view of demographic. 

The second research question we explored was if Race, age, and gender are good predictors of homelessness?  The second set of data we used for our study comes from the U.S. Census Bureau and is based on their every-ten-year surveys of New York. This information is gathered by the Census Bureau through a mix of administrative records, home surveys, and door-to-door techniques to make sure that all population groups are fully covered. Answers come directly from households through mailed surveys, online submissions, or interviews with trained census workers that happen in person. The process is carefully planned to reduce mistakes and increase precision, which makes the dataset a trustworthy source for figuring out housing and population trends. This information shows changes in the number of people living in cities versus those living in rural areas, the number of homes available, and the occupancy rates. These findings add to the HUD data by showing how changes in population and housing affect the trends in homelessness in New York. 

Age, gender, race, and housing-related factors like total housing units and occupancy rates are some of the most important variables used from this collection that we analyzed. The dataset also has classifications for urban and rural areas, which lets us look at how geography affects the stability of homes and the number of people living in an area. Each report in the dataset is a statistical summary for a certain New York county or city's population groups or housing units. This information gives us a general picture of the state's people and housing situations, which lets us look for links between these things and trends of homelessness. This information is very helpful for figuring out how differences and geographic factors affect homelessness in New York, which has a lot of people. For example, housing problems are more likely to happen in places with high population densities. Including factors for race and gender also helps find differences in population, and dividing areas into urban and rural areas shows how trends change over time. The HUD data and this dataset together make it possible to look at both the direct effects and root causes of homelessness in New York. 

This map visualizes population density across New York’s counties, categorizing areas by the number of people per square mile. Urban centers like New York City and its surrounding counties are shown to have significantly higher densities compared to rural upstate areas. This data can be linked to homelessness analysis as higher population densities often correlate with a lack of housing affordability. 

## 

## The second map illustrates the percentage change in the White population across New York counties over the past decade. This data includes an option to explore population changes for different racial groups, as highlighted in the screenshot below, which shows racial and ethnic categories like Black or African American, Asian, and Native Hawaiian. Observing these changes reveals patterns of demographic shifts, such as increases in some counties like Bronx County and decreases in others like Queens County. These trends may affect homelessness by altering the dynamics and resource distribution in different areas. By putting these insights together with HUD data, we can look into how changes in population and more people living in cities affect trends in homelessness. For example, counties with fewer people and fewer housing needs may not have as much pressure on housing, while areas with more people may have trouble finding housing and making it affordable, which can hurt some race and ethnic groups more than others.  		

## 

## This table shows changes in race and ethnicity among the homeless people who were living in shelters over two time periods. It is related to our research on racial differences in homelessness. For example, the rise in the number of Hispanic people (+4.5%) and the falls in the numbers of Black (-2.1%) and White (-3.3%) people show changes in how different racial groups experience sheltered homelessness. This is in line with our analysis of the geographic and systemic factors that cause these differences. This lets us look into how structural inequalities and regional trends might affect racial and ethnic groups in different ways over time. This is another piece of the data. We saw the same tables and changes for things like age. 

## 

## 

## Results

IN LESS THAN 6 PARAGRAPHS FOR EACH OF THE TWO QUESTIONS, YOU SHOULD DESCRIBE THE METHODOLOGY YOU USED TO ANSWER EACH QUESTION AND THE RESULTS FROM IMPLEMENTING THAT METHODOLOGY. YOU ARE FREE TO USE ANY MODELING TECHNIQUES OR STATISTICAL TESTS. YOU ARE NOT RESTRICTED TO METHODS DISCUSSED IN THIS CLASS. I HIGHLY ENCOURAGE YOU TO EXPLORE MORE ADVANCED TECHNIQUES THAT ARE APPROPRIATE GIVEN YOUR QUESTIONS. I HIGHLY ENCOURAGE MULTIPLE TECHNIQUES TO BE CONSIDERED TO ANSWER EACH QUESTION. FOR EXAMPLE, MULTIPLE MODELS CAN BE USED TO EXPLORE THE IMPACT OF MULTIPLE PREDICTOR VARIABLES ON 1 EXPLANATORY VARIABLE. ALL DISCOVERIES AND REVELATIONS ABOUT YOUR QUESTIONS SHOULD BE CLEARLY STATED. BY THE END OF READING THIS SECTION, THE READER SHOULD KNOW THE ANSWERS TO YOUR QUESTIONS BASED ON DATA AND NOT OPINION. IF ANY RESULTS SEEM TO BE UNUSUAL, YOU ARE FREE TO GIVE OPINIONS AND IDEAS WHY CERTAIN PHENOMENON EXIST. ALWAYS THINK CREATIVELY AND USE AT LEAST 4 FIGURES AND/OR TABLES IN THIS SECTION TO HELP THE READER VISUALIZE WHAT YOU ARE TRYING TO EXPLAIN. 

Research Question 2: Are race, age, and gender good predictors of homelessness?

To answer the question of whether race, age, and gender are good predictors of homelessness, two datasets were constructed: a “simulated” NYC homelessness dataset and a “realistic” NYC homelessness dataset derived from census and homelessness records. Both datasets were used to evaluate the predictive power of these demographic factors. By employing complementary statistical and machine learning techniques, we aimed to uncover patterns and validate whether these variables hold consistent predictive power across both datasets. The realistic simulation dataset contained 88,025 rows for homeless people and 8,800,000 rows for non-homeless individuals, in line with the estimated NYC population by the Census and the estimated NYC homeless population contained in the PIT-CoC dataset. The dataset contained simulated data drawn from the demographics provided from both the Census and the PIT-CoC datasets in order to depict the inequalities in homelessness accurately. The “realistic” NYC dataset was inherently imbalanced, reflecting the true distribution of homelessness in the population. 

To address this, we applied resampling techniques (undersampling the majority class) to ensure the models received equal representation of homeless and non-homeless groups. Using the same demographics from the other dataset, we created another “simulated” dataset, containing a balanced subset of 88,025 rows for homeless people and 88,025 for non-homeless individuals. This ensured that our analysis would not be biased by differences in the sample sizes. In both datasets, categorical variables like race and gender were one-hot encoded, while the continuous variable age was normalized for consistency across the models.

For the “realistic” dataset, based on the Logistic Regression, we can see that race was the most significant predictor, with minority groups (Hispanic or Latino) having higher odds of homelessness. Gender had a moderate effect, with non-binary and transgender people being more likely to experience homelessness. Age demonstrated little effect, with only older (\>60) individuals being more likely to experience homelessness. The model only achieved an accuracy of 4% and an ROC-AUC of 0.803. For the simulated dataset, the model replicated similar trends, with race and gender emerging as statistically significant predictors. Age effects were slightly weaker but remained consistent. However, the accuracy was 63%, which was much better than the previous one, with an ROC-AUC of 0.803. 

In summary, both datasets revealed consistent trends, underscoring the importance of race and gender in predicting homelessness. Age effects, while present, were less pronounced compared to the other two variables. Based on the employing of logistic regression, the model with real dataset showed worse predictive ability and the model with simulated dataset showed moderate predictive ability. This final result suggested that while race, age, and gender are meaningful predictors of homelessness, additional factors might be necessary to research in order to improve the model’s predicting accuracy.

##  Conclusion

The analysis of homelessness trends and the predictive power of demographic factors has shed light on the complex interplay of geographic, economic, and systemic factors that shape homelessness in the U.S. The results of the first research question reveal clear geographic clustering, with homelessness being more prevalent along the West Coast and border states. These regional trends are deeply intertwined with housing affordability, urban density, and systemic inequities. Moreover, the disproportionate representation of Black/African American populations in states like New York and Texas, and Hispanic populations in states like New Mexico and California, highlights how geography intersects with historical and structural marginalization. Addressing these disparities requires region-specific, equity-driven solutions that account for local economic and demographic conditions.

The second research question demonstrated that race and gender are meaningful predictors of homelessness, while age plays a less pronounced role. Across both the “realistic” and “simulated” NYC datasets we picked, minority racial groups and non-binary or transgender individuals were more likely to experience homelessness, reflecting the broader societal inequities faced by these populations. While the models achieved moderate predictive ability in the simulated dataset, the lower accuracy of the realistic dataset underscores the challenges of modeling such a complex issue with demographic factors alone. This suggests that additional variables, such as economic status, mental health, or access to social services, may be necessary to enhance predictive accuracy.

Together, these findings emphasize the multifaceted nature of homelessness as a societal challenge, shaped by geographic, economic, and demographic factors. Addressing homelessness requires not only national policies but also targeted, region-specific strategies informed by the intersections of race, gender, and systemic inequities. Furthermore, improving predictive models with additional data can help refine interventions and better allocate resources to those most at risk. These insights pave the way for more effective, equitable solutions and contribute to the broader understanding of homelessness in the United States.

Chat gpt? lol  
It is sorry ;(  
I can just write it bro dw