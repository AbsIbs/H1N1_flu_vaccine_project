# H1N1 and Seasonal Flu Vaccine Predictions
![fluvirus](https://github.com/AbsIbs/H1N1_flu_vaccine_project/blob/main/images/flu%20banner.jpeg)

## Project Overview

We have been hired by the CDC as a part of a campaign to increase awareness and encourage more individuals to get vaccinated. We will assist them in making recommendations of how to increase awareness and identify which factors most influence people to get vaccinated.

### Business Problem

Which factors most influence whether a person receives a seasonal or H1N1 flu vaccine?

### Recommendations

Based on our analysis of the data, we would recommend honing in on these 4 factors:
<ul>
  <li>Doctor recommendation of vaccines</li>
  <li>Opinion of vaccine effectiveness</li>
  <li>Opinion of flu risk</li>
  <li>Health insurance</li>
</ul>

We will dive into this further below!

### Guiding Questions for Predictive Modeling
<br>
We used these 4 quesitons below as a guide to completing this analysis:
<ul>
  <li>Which model is the most effective in predicting whether a person received a seasonal flu shot?</li>
  <li>Which model is the most effective in predicting whether a person received a H1N1 flu shot?</li>
  <li>Which features are the most important in predicting whether a person received a seasonal flu shot?</li>
  <li>Which features are the most important in predicting whether a person received a H1N1 flu shot?</li>
</ul>



# The Data
![databanner](https://github.com/AbsIbs/H1N1_flu_vaccine_project/blob/main/images/data-science-banner.jpeg)

The data for our study is obtained from the National 2009 H1N1 Flu Survey (NHFS) which was held by the Centres for Disease Control and Prevention (CDC). The survey sample consiste of over 26,000 people. This survey asked respondents whether they had received the H1N1 and seasonal flu vaccines, in conjunction with questions about themselves. These additional questions covered their social, economic, and demographic background, opinions on risks of illness and vaccine effectiveness, and behaviors towards mitigating transmission. This data was obtained to get a fair idea about the knowledge of people on the effectiveness and safety of flu vaccines and to learn why some people refrained from getting vaccinated against the H1N1 flu and seasonal flu.

The dataset contains the following columns/ information:
<ul>
<li><strong>h1n1_vaccine</strong> - Have they received H1N1 flu vaccine</li>
<li><strong>seasonal_vaccine</strong> - Have they received seasonal flu vaccine</li>
<li><strong>h1n1_concern</strong> - Level of concern about the H1N1 flu on a scale from 0-3</li>
<li><strong>h1n1_knowledge</strong> - Level of knowledge about H1N1 flu on a scale from 0-3</li>
<li><strong>behavioral_antiviral_meds</strong> - Have they taken antiviral medications (binary)</li>
<li><strong>behavioral_avoidance</strong> - Do they avoid close contact with others with flu-like symptoms (binary)</li>
<li><strong>behavioral_face_mask</strong> - Do they have a face mask (binary)</li>
<li><strong>behavioral_wash_hands</strong> - Do they frequently wash their hands (binary)</li>
<li><strong>behavioral_large_gathering</strong>s - Have they avoided large gatherings (binary)</li>
<li><strong>behavioral_outside_home</strong> - Have they reduced contact with people outside of their own home (binary)</li>
<li><strong>behavioral_touch_face</strong> - Do they avoid touching their face (binary)</li>
<li><strong>doctor_recc_h1n1</strong> - Was the H1N1 flu vaccine was recommended by doctor (binary)</li>
<li><strong>doctor_recc_seasonal</strong> - Was the Seasonal flu vaccine was recommended by doctor (binary)</li>
<li><strong>chronic_med_condition</strong> - Do they have chronic medical conditions (binary)</li>
<li><strong>child_under_6_months</strong> - Are they in close contact with a child under the age of six months (binary)</li>
<li><strong>health_worker</strong> - Are they a healthcare worker (binary)</li>
<li><strong>health_insurance</strong> - Do they have health insurance (binary)</li>
<li><strong>opinion_h1n1_vacc_effective</strong> -  What is their opinion about H1N1 vaccine effectiveness on a scale from 1-5</li>
<li><strong>opinion_h1n1_risk</strong> - What is their opinion about risk of getting sick with H1N1 flu without vaccine on a scale from 1-5</li>
<li><strong>opinion_h1n1_sick_from_vacc</strong> - Are they worried about getting sick from taking H1N1 vaccine on a scale from 1-5</li>
<li><strong>opinion_seas_vacc_effective</strong> - What is their opinion about seasonal flu vaccine effectiveness on a scale from 1-5</li>
<li><strong>opinion_seas_risk</strong> - What is their opinion about risk of getting sick with seasonal flu without vaccine on a scale from 1-5</li>
<li><strong>opinion_seas_sick_from_vacc</strong> - Are they worried about getting sick from taking seasonal flu vaccine on a scale from 1-5</li>
<li><strong>age_group</strong> - What age group do they fall into</li>
<li><strong>education</strong> - What is their education level</li>
<li><strong>race</strong> - Race </li>
<li><strong>sex</strong> - Sex </li>
<li><strong>income_poverty</strong> - Household annual income with respect to 2008 Census poverty thresholds</li>
<li><strong>marital_status</strong> - Married or Not Married</li>
<li><strong>rent_or_own</strong> - Housing situation (Rent or Own)</li>
<li><strong>employment_status</strong> - Employment status (Employed or Unemployed)</li>
<li><strong>hhs_geo_region</strong> - Residence using a 10-region geographic classification - values are random character strings</li>
<li><strong>census_msa</strong> - Where is the residence within metropolitan statistical areas (MSA) as defined by the U.S. Census</li>
<li><strong>household_adults</strong> - Number of other adults in household, top-coded to 3</li>
<li><strong>household_children</strong> - Number of children in household, top-coded to 3</li>
<li><strong>employment_industry</strong> - Type of industry they are employed in - values are random character strings</li>
<li><strong>employment_occupation</strong> - Type of occupation - values are random character strings.</li>
</ul>

## Exploratory Data Analysis

### Heatmap
<br>
We created a heatmap to get a better understanding of the correlations between each feature, and their correlations to the H1N1 and seasonal vaccine. 
![heatmap](https://github.com/AbsIbs/H1N1_flu_vaccine_project/blob/main/images/Screen%20Shot%202022-01-28%20at%2012.19.07%20AM.png)

## Methodology
<br>
Listed below are the classifiers that we used to create our models:
<ul>
  <li>Logistic Regression</li>
  <li>Decision Tree</li>
  <li>Support Vector Machines</li>
  <li>Naive Bayes</li>
  <li>Voting Classifier</li>
  <li>Ensemble Methods
    <ul>
          <li>Bagging: 
            <ul>
              <li>Random Forest</li>
            </ul>
          <li>Boosting: 
             <ul>
                <li>Ada Boost</li>
                   <li>Gradient Boost</li>
                      <li>Histogram Gradient Boost</li>
               <li>Cat Boost</li>
               </ul>
    </ul>
</ul>

# Business Results
After making a myriad of different models to predict our targets (H1N1/seasonal vaccinations) we found that our best model was the CatBoost classifier using cross validation and a Bayesian optimization tool called Optuna. It gave us a ROCAUC score of .87 and accuracy of 85% for H1N1 vaccinations while giving us a ROCAUC score of .86 and accuracy of 82% for seasonal vaccinations.  

## H1N1 Analysis
Here is a graph showing how our models performed based on the ROCAUC score for H1N1 vaccinations.
![h1n1modelsummary](https://github.com/AbsIbs/H1N1_flu_vaccine_project/blob/main/images/h1n1%20models%20graph.png)
<br>
ROCAUC Score
![h1n1roc](https://github.com/AbsIbs/H1N1_flu_vaccine_project/blob/main/images/h1n1%20roc.png)
<br>
Confusion Matrix
![h1n1confusionmatrix](https://github.com/AbsIbs/H1N1_flu_vaccine_project/blob/main/images/h1n1%20cm.png)
<br>
Permutation Feature Importance
![h1n1permutations](https://github.com/AbsIbs/H1N1_flu_vaccine_project/blob/main/images/h1n1%20permutation.png)

## Seasonal Analysis
Here is a graph showing how our models performed based on the ROCAUC score for seasonal vaccinations.
![seasonalmodelsummary](https://github.com/AbsIbs/H1N1_flu_vaccine_project/blob/main/images/seasonal%20models%20graph.png)
<br>
ROCAUC Score
![seasonalroccurve](https://github.com/AbsIbs/H1N1_flu_vaccine_project/blob/main/images/seasonalroc.png)
<br>
Confusion Matrix
![seasonalconfusionmatrix](https://github.com/AbsIbs/H1N1_flu_vaccine_project/blob/main/images/seasonal%20permutation.png)
<br>
Permutation Feature Importance
![seasonalpermutations](https://github.com/AbsIbs/H1N1_flu_vaccine_project/blob/main/images/seasonalpermutation.png)


## A Closer Look at the Health Insurance Feature

As you can see in the chart below, people with health insurance have a higher likelihood of receiving a vaccine. On the other hand, people without insurance are more unlikely to get the vaccine. Individuals without insurance are less likely to see a doctor, so their chances of getting the vaccine recommended to them, falls significantly. As mentioned previous, a doctor's recommendation is one of the top 3 most influential predictors.

![healthinsurancegraph]( INSERT HEALTH INSURANCE GRAPH

## Another Feature of Importance - Household Income

In addition to not having health insurance, people that have a household income below the poverty line are also less likely to get vaccinated. 

![Householdincomegraph]( INSERT HOUSEHOLD INCOME GRAPH


# Conclusion

![bottlebanner](https://github.com/AbsIbs/H1N1_flu_vaccine_project/blob/main/images/bottle%20banner.jpeg)

Overall, the 3 most influential factors in determining whether a person got vaccinated against H1N1 or the seasonal flu were:

<ul> 
<li> How effective they believed the vaccine to be at protecting against the flu.</li>
<li> Whether a doctor recommended that they get the vaccine.</li>
<li> Their perceived level of risk of getting sick with the flu without the vaccine.</li>
</ul>

## Recommendations
Based on our analysis, we would make the following 3 recommendations to the CDC to help reach their goal of increasing awareness and increasing the number of vaccinated people:

<ul> 
<li> Doctors should regularly recommend that their patients get vaccinated.</li>
<li> Targeted efforts should be made to inform and provide access to vaccinations for people without health insurance and below the poverty line.</li>
<li> Inform people of the potential risks of H1N1/seasonal flu and provide more education on vaccine effectiveness.</li>
</ul>


