# Will the Customer Accept the Coupon?
Repo for AIML Certificate class assignment 5.1.

## Problem
Perform exploratory data analysis of driver characteristics who received a coupon over their cell phone for a restaurant near where they were dirving. Driver either accepts the coupon or does not accept it.

## Data
This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk.  The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. 

## Methodology
Use Pandas functions and Python charting utilities to explore the data characteristics.

## Results

summary of observations:
------------------------
For bar coupons only:
 overall acceptance rate (all drivers): 0.412
 
 These drivers had higher acceptance rates:
 who went more than 3 times in bars per month: 0.762
 who went to bar more than once a month and are over the age of 25: 0.690
 who go to bars more than once a month and had passengers that were not a kid and had occuptions other than farming, fishing or forestry: 0.435
 who go to bars more than once a month, had passengers that were not a kid, and were not widowed: 0.709
 who go to bars more than once a month and are under the age of 30: 0.720
 who go to cheap restaurants more than 4 times a month and income is less than 50K: 0.482

Hypothesis:
-----------
Drivers who accepted bar coupons were likely to to have these characteristics:
 - went to bars more than 3 times per month
 - were under age 30
 - did not have a child (kid) as a passenger
 - did not go to cheap restaurants more than 4 times per month
 - were not in farming, fishing or forestry occupations
 - and had income levels above $50K per year


summary of observations:
------------------------
For coffee coupons only:
 overall acceptance rate (all drivers): 0.496
Acceptance rate for coffee coupons for Male drivers: 0.502
Acceptance rate for coffee coupons for Female drivers: 0.491
Acceptance rate for coffee coupons for drivers with no college degree: 0.520
Acceptance rate for coffee coupons for drivers with Bachelors or higher degree: 0.472
Acceptance rate for coffee coupons before noon: 0.536
Acceptance rate for coffee coupons after noon: 0.463

 Drivers who were male with no college degree had slightly higher acceptance rates for coffee coupons if sent by noon.


Recommendation:
---------------
The advertizing campaign for Bars should target these types of drivers and scenarios to maximize coupon acceptance rates:
 - went to bars more than 3 times per month
 - were under age 30
 - did not have a child (kid) as a passenger
 - did not go to cheap restaurants more than 4 times per month
 - were not in farming, fishing or forestry occupations
 - and had income levels above $50K per year

The advertizing campaign for Coffe House should target these types of drivers and scenarios to maximize coupon acceptance rates:
 - drivers with no college degree (slightly higher than average)
 - driver gender differences is not much (1% dfference) with Male drivers slightly higher.
 - Send coupons before noon for a slightly higher acceptance (53.6%) compared to overall average of 49.6%.


###
