# coustomer_shopping_behaviour
Goal :-
 My project's goal is was to look at coustomer data to figure out who spends most money and give the store a clear plan to increase sale 

## Big surprise for me in this data##
 I discovered that almost every coustmer only bought something once , no repeat coustomer in this data . this was major surprise 
then 
I stop looking for loyality since there was none and then gave Focus on wich factor give major effect on increment sales

# important things that I noticed 
1. females do more shopping and check also which category both gender spend most of their money by visualization 
so answer is both gender spend their most of the money on cloths and men more like to shoes technology,books ,toy or female like to spend money on cosmetic ,souvenir

2.the coustomer age also depend on ,how much they spend money 

3. in category technology item cost is most 

 4. i also subploted the all years sale trend 

5. many coustomer visit two mall largly than the other 
1. mall of istanbul
2. kanyin 
i check that is it result for all year, answer was yes and also in every mall people choise was same for category 

6. most people prefer spend money in cash 
then majorly credit card 
and that's good point, people prefer credit card rather than debit card 
bcz then they spend more money 

# feature engineering 
 in this data I add more column year and month so I can analyse sales trend of all moths of each year

I  subploted the all years sale trend and their I noticed in 2023 demand is low than 2021 or 2022
so seen direct effect on sales I also give effort to find which factor imporant and check ,is it producet are expensive than other year but no products range was same here any other drametic reason should be

# built best prediction model 
in this data I built two type of model and for that I make final_customer_df variable and stored in all important column which help in modelling 
purpose of 1 st model :- 
i built a model to guess how much money a new coustomer would spend 
using the complex model called Random Forest Regression worked best

this model is very strong ,it can correctly explains about 70% of the reason why coustmer spends a certain amount this is good enough to trust for making buisness decission 

2nd model :- for predict new coustomer how much possibilities to buy clothes by simply we can build for other category also 
and it can correctly predict about 65% and here monetary column had to be dropped othervise random forest classification model gave 0.98% accuracy after drop column 
both ogistic regression  and Random Forest classifier both have same accuracy 0.65%


