# An analysis of theater crowdfunding

## Overview 
   This analysis will cover the percentage of successful kickstarter plays campaigns based on their goal amount. The second part of the analysis will focus on how many campaigns were successful in relation to their launch date. The purpose of this document is to have a better understanding on whether launch dates or goals have an       impact on the success of a kickstarte campaign. With this knoweledge, proceed decide when the most optimal time to launch a campaign is and what amount/budget should you consider as your goal to make it more likely that your campaign will be successful.

## Analysis and Challenges
    
### Analysis of Outcomes Based on Launch Date
 ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/101848882/161445342-800058da-1aa5-44ff-a9d8-c0998503374b.png)

The table considered the "Theater" category in kickstarter and their outcomes. The information displayed allows us to conclude that the best time to launch a theater campaign is during May. The summer months (June, July and August) are a good option as well as the amount of successful vs failed campaigns is close to double. We would need more information to draw a conclusion on what the true reasons are.

### Analysis of Outcomes Based on Goals
 ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/101848882/161445630-d3dd6a6a-c26f-47b9-9d0e-96b6f5a8857c.png)

The table considers diferent goal ranges and the count of the subcategory "Plays". This graph is a little trickier to conclude on. The largest percentage of successful plays campaigns is from small goals, lower than $5,000 and implied lower production costs. Next comes campaigns in the range of $35,000 to $45,000 which would lead to believe that a bigger project and production is considered. At that point, the recomendation we can give is to either go for a small production or a big one. In both instances though, more information regarding the funds management could lead us to better conclusions.

### Challenges and Difficulties Encountered
Regarding the project itslef, the challenge I encountered was finding the correct way to input the ranges of the COUNTIFS functions as I kept getting an error message after the cell gave me the correct result. After trying several different range, criterias, and validating that the result was correct by manual filtering in the dataset, I realized that the formula wa correct and Excel was just thinking there was an issue because the first cell did not contain the same number of ranger and criterias for the COUNTIFS functions. Otherwise, the challenge was mostly and Excel reinforcement course, which is still useful.

This was the Microsoft support page I used as support for the function: https://support.microsoft.com/es-es/office/funci%c3%b3n-contar-si-conjunto-dda3dc6e-f74e-4aee-88bc-aa8c2a866842?ns=excel&version=90&syslcid=3082&uilcid=3082&appver=zxl900&helpid=xlmain11.chm60529&ui=es-es&rs=es-es&ad=es


## Results

- Regarding the Theater Outcomes vs Launch graph, if you want to run a Theater campaign in kickstarter, the best month to do it is May. Another useful insight is about behavior, not a lot of campaigns get canceled, that gives the idea that for a campaign to be started, an actual project is already crafted, so participating in crowdfunding is actually very safe.

- Regarding the Outcomes vs Goals graph, the biggest conclusion to gather is the disparity of successful campaign vs failed campaigns in the middle ranges compared with the extreme ranges of pledge Goals. I f you want to fund your campaign, you either want a small play or a big, there is no middle point.

- The dataset has a couple of limitations. Regarding the success of the campaigns, not enough information of the reasons for campaign completion. Maybe dig up the ages of the pledgers as maybe more internet usage during the summer from high school users can lead to more campaign fulfilled. On the Outcomes based on Goals more information regarding the funds gathered could be useful to give more clarity on the size of the production that was presented in the end.

- A useful graph, with the available data, could be successful plays for the last 2 years to compare if the same trends are still present. As well as the average pledge from users for successful play campaigns to estimate how many users you would need to fung your project. You want to consider the size of the campaign as well to estimate more accurately the amount of people you will need.
