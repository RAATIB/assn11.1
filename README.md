# assn11.1
Professional Certificate in ML/AI Practical Application 2

# Will the Customer Accept the Coupon?

Raatib Tanvir | Sep 17 2025 | Professional Certificate in Machine Learning and Artificial Intelligence

**Assignment notebook:** https://github.com/RAATIB/assn11.1/blob/5ebea2a1da91ce05c1b512e1ca34f9ae046e2ca7/assn11.1.ipynb

## Single Non-Numeric Values

Features like fuel type, condition, and title status all reliably contribute to the value of our car. Thanks to our analysis, we can pinpoint to what degree features affect price and advise sales personnel on how valuable certain features are.

### Condition
* Our analysis demonstrates that "fair" and "excellent" condition for cars are massive drivers of value. These features heavily increase the selling price of a car. Cars with a "like new" condition are actually statistically not as strongly preferred in the used car market, and "new" cars even less so, demonstrating buyer's preferences towards previously used cars and a likelihood for less costly brands to be present in inventory space. ***Used car sales personnel should prioritize "fair" and "excellent" cars** most to align with consumer interest, followed by "like new" and "good", then by "new" and "salvage"*


### Drive
* Amongst cars designated with front-wheel drive (FWD), rear-wheel drive (RWD), and four-wheel drive (4WD), 4WD is by far the biggest contributer to value. A vehicle's 4WD designation tends to contribute nearly three times as much towards a car's price than a FWD designation, and far far more than a RWD designation. ***Used car sales personnel should prioritize 4WD in ther inventory** and then provide FWD, followed by RWD vehicles in order to maximize the price of their stock*


### Fuel
* In terms of fuel type, sales personnel can **expect diesel and gas cars to be the highest price vehicles on their lot**. Vehicles with an "other" designation are less valuable, while **electric and hybrid vehicles are even further less valuable** according to analysis. This likely reflects the used car market, where users are hoping for reliable cars for every day use, and may not have the capability to use electric means of fuel.

### Title Status
* In terms of title status, sales personnel can rest assured that intuitively, the better condition a title status of a car, the higher the price the car will be. In essence, **clean title status indicates highest pricing, then lien**, followed by rebuilt, parts only, missing, and salvage respectively.








## Problem Statement:
In this project, we utilized data processing tools and visualizations to discern whether surveyed customers accepted certain coupons or not.

Our analysis provided ***promising trends that could cue shareholders into the mind of a potential coupon user***, demonstrating how factors like age, habits, and income affect the decision of customers on the receiving end of a coupon.


Our conclusions can lead us to **actionable steps to secure further business engagements with the right customers!**


<br />

## Guided Analysis on Bar Coupon Results:
- Individuals who already **go to the bar at least once** are ***much more likely*** to accept bar coupons
- **Individuals above 25, individuals above 30, and individuals with companions who aren't kids** are all subsets of respondents who are ***significantly more likely*** to accept bar coupons.
    - These all fit demographics that are intuitively more likely to visit a bar, given they are of age to drink alcohol.
- Individuals who **do not visit the bar frequently** (<1 a month) are ***much less likely*** to accept bar coupons, reflecting a consistent lack of desire to attend the bar.
- Individuals who **have kids** with them in their car are ***much less likely*** to accept bar coupons. Customers with kids accompanying are likely unable to attend the bar.

<br />

# Individual Analysis
## Problem Statement:
Can we find patterns in *subsets of data related to the coffee house coupons*?
In particular, can we find trends related to income, age, and frequency of coffee house visits?

## Individual Analysis - Results:
- **Income**    affected rate of acceptance:
    - A majority of lower income bracket respondents accepted coffee house coupons
    - A minority of upper income bracket respondents accepted coffee house coupons
    - Overall, there was a small increase (about 11%) in likelihood for acceptance if participants were in lower income brackets, reflecting the relative utility of a coupon to lower income customers.
 
      
- **Age**    was another factor in rate of acceptance:
    - A **majority** of *younger* participants (younger than 30 years old) accepted coffee house coupons
    - A **minority** of *older* participants (30 or older) accepted coffee house coupons
    - Overall, younger participants were slightly more likely (about 14%) to accept coupons than older participants.
    - Factors like interest in coffee, utility of coffee based on age, or free time based on age could have led to these results.
 
      
- **Frequency of attending coffee houses**    in a month had a *massive affect* on rate of acceptance!:
    - Individuals who attended coffee houses frequent (4 or more times a month) were vastly more likely (a 50% difference!) than infrequent (less than 4 a month) attenders to accept the coupon.
    - We can conclude that individuals who already attend coffee houses frequently are very likely to accept coffee house coupons. This invaluable information allows owners and managers to curate coupons towards frequent visitors to ensure further business interactions.

## Recommendations:
Further recommendations are included in the notebook. They include:
- Finding statistical data on the "disposable income" of given income bracket participants in order to hone in on possible trends in coupon acceptance based on income.
- Survey of factors like "free time" or relative interest or utility of coffee of participants, perhaps in relation to age, as it may allow for further analysis of coupon acceptance rates to make decisions around.
