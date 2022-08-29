# Kickstarting with Excel

## Overview of Project
This project explores a dataset of the kickstarter campaigns for our client, to help them understand which month would be the best in terms of suceesful rate to start the campaigns on specific subcategory(For example:theater,plays,musical,etc...)

## Purpose
The purpose of this project is to help client understand the successful rate of the campaign based on various parents category and subcategory, to help client optimize their campagin by setting different goal,starting campaign on different time of the year on specific catergory to improve sucessful rate.

## Analysis and Challenges
![image](https://user-images.githubusercontent.com/109333158/187131673-5d8a738b-6d8b-4a95-9c6e-634b294d510c.png)

The dataset contains more than 4000 campaign, some of the information provided for each campagin includes id,name,goal,pledged amount,outcomes,country,deadline,category and etc. See image above. 
Further analysis was to break down the parents category into subcategory and focus on analysis one subcategory's sucessful rate in differnt time of the year.

## Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/109333158/187123875-7e7c0e65-756f-44e9-be74-8a526f81bcf5.png)

Base on the graph above, we concludes that, Launching campaign in May to July would have the greatest count of successful among the year. The counts of sucessful compagin reaches the highest point in May and it would start decline till the end of the year.

Launching campgin in december would have about the same count of failed and sucessful campagin, Launching campaign in december is just waste of money for doing so.

## Analysis of Outcomes Based on Goals
Focusing on analysing the sucessul rate in "Plays" Subcategory. 
![Outcomes Based On Goal](https://user-images.githubusercontent.com/109333158/187123851-4b6aabab-39f4-4494-88c7-01ed37245f19.png)

We could easlier concludes that as the campagin would have a down side trend as we increase the goal from Less than 1000 to 25000-29999, and start to become bull again from 250000-29999 to 40000-44999. The remaining portions are unaccountable.

Yet, the population from 25000-29999 to 50000 or more are less than 20, which mean the accuracy is comparably low. Larger dataset may require to concludes the logic behind it.

## Challenges and Difficulties Encountered
One of the challenges we may encountered are Excel would poping up"please update value" windows once we enter some invalid string into the formula.
I try to resolve the issue by trying out different "solutions" in the online forum, but all of them failed.
At the end, I schedule an 1 on 1 Tutoring time with our TA to solve the issue. TAs are excellent.

## Results
We recommend start doing theater campaign in April to July, since it has higher counts of successful outcomes among the year, stop from july to April. 

In considering the graph's accruatecy, we would ignore and exclude the portion of the graph 25000-29999 to 50000 or more to gain in reliableness.

Afterall, We would recommend setting lower goals in "Plays" subcategory, since it has the highest percentage of successful rate compares to higher goal amount.

## Limitation
The limitation is super high in terms of more speific geographic breakdown,citylization,education and more.Further break down would help analysising and improve the campagin strategies.
Also, the population of the dataset is not enough, ten thousand would be much better number than just a little bit more than 4000 . It helps increase in accuracy in the analytical stage.

## Possible tables/graph that would be useful 
One of the possible table/graph could be comparing the sucessful rate with staff pick and not staff pick, we could easier identify if staff pick would boost the cammpagin to meet the goal, and what's sucessful rate with staff pick campagin.

The other one we could be comparing is the same category sucessful rate in different country. For example, film's sucessful rate in UK is better than US, then we could choose UK to do the film campagin. If US has higher sucessful rate in foods than UK, we could choose US to do the food campagin.
