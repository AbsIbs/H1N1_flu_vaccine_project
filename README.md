# H1N1 and Seasonal Flu Vaccine Predictions
![fluvirus](https://github.com/AbsIbs/H1N1_flu_vaccine_project/blob/main/images/flu%20banner.jpeg)

## Project Overview

The North Georgia Hospital System has asked us, The Radiant Gradients, if we can predict whether people received the H1N1 and seasonal flu vaccines. They have provided us with all the necessary data, which we will use to complete this analysis.

## Business Problem

** NEED TO WRITE BUSINESS PROBLEM
How can we predict whether a person received a seasonal or H1N1 flu vaccine?
** NEED TO WRIE DOWN RECOMMENDATIONS

Based on our analysis of the data, we would recommend:
<ul>
  <li>X</li>
  <li>Y</li>
  <li>Z?</li>
</ul>

### Guiding Questions for Predictive Modeling
<ul>
  <li>Which features are the most important in predicting whether a person received a seasonal flu shot?</li>
  <li>Which features are the most important in predicting whether a person received a H1N1 flu shot?</li>
  <li>Which model is the most effective in predicting whether a person received a seasonal flu shot?</li>
  <li>Which model is the most effective in predicting whether a person received a H1N1 flu shot?</li>
</ul>



## The Data
![databanner](https://github.com/AbsIbs/H1N1_flu_vaccine_project/blob/main/images/data-science-banner.jpeg)

The data for our study is obtained from the National 2009 H1N1 Flu Survey (NHFS) which was held by the Centres for Disease Control and Prevention (CDC). This survey asked respondents whether they had received the H1N1 and seasonal flu vaccines, in conjunction with questions about themselves. These additional questions covered their social, economic, and demographic background, opinions on risks of illness and vaccine effectiveness, and behaviors towards mitigating transmission. This data was obtained to get a fair idea about the knowledge of people on the effectiveness and safety of flu vaccines and to learn why some people refrained from getting vaccinated against the H1N1 flu and seasonal flu.

The dataset contains the following columns/ information:
<ul>
<li>h1n1_vaccine - Have they received H1N1 flu vaccine</li>
<li>seasonal_vaccine - Have they received seasonal flu vaccine</li>
<li>h1n1_concern - Level of concern about the H1N1 flu. 0 = Not at all concerned; 1 = Not very concerned; 2 = Somewhat concerned; 3 = Very concerned</li>
<li>h1n1_knowledge - Level of knowledge about H1N1 flu. 0 = No knowledge; 1 = A little knowledge; 2 = A lot of knowledge</li>
<li>behavioral_antiviral_meds - Have they taken antiviral medications (binary)</li>
<li>behavioral_avoidance - Do they avoid close contact with others with flu-like symptoms (binary)</li>
<li>behavioral_face_mask - Do they have a face mask (binary)</li>
<li>behavioral_wash_hands - Do they frequently wash their hands (binary)</li>
<li>behavioral_large_gatherings - Have they avoided large gatherings (binary)</li>
<li>behavioral_outside_home - Have they reduced contact with people outside of their own home (binary)</li>
<li>behavioral_touch_face - Do they avoid touching their face (binary)</li>
<li>doctor_recc_h1n1 - Was the H1N1 flu vaccine was recommended by doctor (binary)</li>
<li>doctor_recc_seasonal - Was the Seasonal flu vaccine was recommended by doctor (binary)</li>
<li>chronic_med_condition - Do they have any of the following chronic medical conditions: asthma or an other lung condition, diabetes, a heart condition, a kidney condition, sickle cell anemia or other anemia, a neurological or neuromuscular condition, a liver condition, or a weakened immune system caused by a chronic illness or by medicines taken for a chronic illness (binary)</li>
<li>child_under_6_months - Are they in close contact with a child under the age of six months (binary)</li>
<li>health_worker - Are they a healthcare worker (binary)</li>
<li>health_insurance - Do they have health insurance (binary)</li>
<li>opinion_h1n1_vacc_effective -  What is their opinion about H1N1 vaccine effectiveness. 1 = Not at all effective; 2 = Not very effective; 3 = Don't know; 4 = Somewhat effective; 5 = Very effective</li>
<li>opinion_h1n1_risk** - What is their opinion about risk of getting sick with H1N1 flu without vaccine. 1 = Very Low; 2 = Somewhat low; 3 = Don't know; 4 = Somewhat high; 5 = Very high</li>
<li>opinion_h1n1_sick_from_vacc** - Are they worried about getting sick from taking H1N1 vaccine. 1 = Not at all worried; 2 = Not very worried; 3 = Don't know; 4 = Somewhat worried; 5 = Very worried</li>
<li>opinion_seas_vacc_effective** - What is their opinion about seasonal flu vaccine effectiveness. 1 = Not at all effective; 2 = Not very effective; 3 = Don't know; 4 = Somewhat effective; 5 = Very effective</li>
<li>opinion_seas_risk - What is their opinion about risk of getting sick with seasonal flu without vaccine. 1 = Very Low; 2 = Somewhat low; 3 = Don't know; 4 = Somewhat high; 5 = Very high</li>
<li>opinion_seas_sick_from_vacc - Are they worried about getting sick from taking seasonal flu vaccine. 1 = Not at all worried; 2 = Not very worried; 3 = Don't know; 4 = Somewhat worried; 5 = Very worried</li>
<li>age_group - What age group do they fall into</li>
<li>education - What is their education level</li>
<li>race - Race </li>
<li>sex - Sex </li>
<li>income_poverty - Household annual income with respect to 2008 Census poverty thresholds</li>
<li>marital_status - Married or Not Married</li>
<li>rent_or_own - Housing situation (Rent or Own)</li>
<li>employment_status - Employment status (Employed or Unemployed)</li>
<li>hhs_geo_region - Residence using a 10-region geographic classification defined by the U.S. Dept. of Health and Human Services - values are random character strings</li>
<li>census_msa** - Where is the residence within metropolitan statistical areas (MSA) as defined by the U.S. Census</li>
<li>household_adults - Number of other adults in household, top-coded to 3</li>
<li>household_children - Number of children in household, top-coded to 3</li>
<li>employment_industry - Type of industry they are employed in - values are random character strings</li>
<li>employment_occupation - Type of occupation - values are random character strings.</li>
</ul>

## Methodology 
<ul>
  <li>Logistic Regression</li>
  <li>Decision Tree</li>
  <li>Support Vector Machines</li>
  <li>Naive Bayes</li>
  <li>Voting Classifier</li>
  <li>Emsemble Methods
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
               </ul>
    </ul>
</ul>

      

## Business Results
![linebanner](https://github.com/AbsIbs/H1N1_flu_vaccine_project/blob/main/images/linebanner1.jpg)

blah! blah! blah! blah! blah!

## Conclusion

![bottlebanner](https://github.com/AbsIbs/H1N1_flu_vaccine_project/blob/main/images/bottle%20banner.jpeg)

blah! blah! blah! blah! blah! blah!

