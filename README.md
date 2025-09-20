# assn11.1
Professional Certificate in ML/AI Practical Application 2

# Will the Customer Accept the Coupon?

Raatib Tanvir | Sep 17 2025 | Professional Certificate in Machine Learning and Artificial Intelligence

**Assignment notebook:** https://github.com/RAATIB/assn11.1/blob/5ebea2a1da91ce05c1b512e1ca34f9ae046e2ca7/assn11.1.ipynb


## Introduction and Problem Statement:
In this project, we utilized data processing tools and machine learning techniques to discern what factors contribute to a used car's price.

Our analysis provided ***promising trends that could cue sales personnel into the mind of a used car buyer***, demonstrating how factors like condition, year of manufacture, and title status contribute to a car's price.


Our conclusions can lead us to **actionable steps to allow sales personnel to assess their inventory for the most successful used car sales!**


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


## Numeric Values

### Cylinders, Odometer, Year

* Our analysis provides promising information about the numeric features of car's in the inventory of our sales personnel. Firstly, ** increasing cylinder count has a very strong effect on price**, where each increase in cylinder count increases the price of a car greatly. **Sales personnel should prioritize higher cylinder count cars** to ensure greater pricing. **Cars newer by the year are more valuable**, where each increase in year leads to a moderate increase in price. **Sales personnel should stock up on newer car models** to maximize their pricing. Finally, odometer count gradually decreases price as it increases. Unsurprisingly **sales personnel should be aware that greater mileage lowers the price of a car**, considering lower mileage cars to maximize value.


## Conclusion and Summary:
**Here, we'll summarize the best features to guarantee high pricing for used cars in our inventory.

* Condition: **"Fair" and "excellent" cars are priced highest**, followed by "like new", "good", "new" and "salvage."
* Drive: **4WD are by far the highest priced** cars, followed by moderately priced FWD, and much cheaper RWD.
* Fuel: **Highest priced cars are "diesel" and "gas" based**, followed by "other", than "electric" and "hybrid."
* Title status: Intuitively, price is highest as follows: **"clean", "lien"**, "rebuilt", "parts only, "missing," and "salvage."
* Cylinders: Price increases very greatly per each cylinder a car has. **The more cylinders, the higher the price!**
* Odometer: Price decreases gradually as odometer value increases. **The lower the odometer value, the more valuable the car!**
* Year: Newer models sell for a higher value. **The newer the car model, the more valuable the car!**
