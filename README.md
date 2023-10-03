# AIML---Practical-Application-1
This repository contains the Practical Application of a real-world Machine Learning problem “Will a customer accept the coupon?” The goal of this project is to distinguish between customers who accepted a driving coupon versus those that did not by utilizing data analysis, plotting, statistical summarizations, and data visualization skills.

## Data:
This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, passenger, etc., and then asks people whether they will accept the coupon if they are the driver. Answers given that the users will drive there “right away” or “later before the coupon expires” are labeled as “Y = 1”, and answers “no, I do not want the coupon” are labeled as “Y = 0”. There are five different types of coupons—less expensive restaurants (under $20), coffee houses, carry out and take away, bars, and more expensive restaurants ($20–$50).

## High-Level Sumamry of Findings

#### High-level observations from the cleaned data-set across all coupon categories -
- The likehood of the driver to use the coupon is higher in comparison to them rejecting a coupon.
- Passangers who ae traveling Alone seem to have a higher acceptance rate on coupon across the board over all other passanger types
- Sunny Weather and warmer temperatures seem to have higher acceptance rate for coupons

#### Bar coupon acceptance rate -
- Higher for Drivers who are less frequent in visiting Bar's. (80%)
- Higher acceptance rate at 6PM time
- More users between ages 21-31 have higher acceptance rates and also for users over 50.
- Most drivers prefer to go to the Bar when the weather is sunny
- Bar coupons have a higher acceptance rate at 6PM and 10PM and users are less likely to visit the bar during 7AM, 10AM, and 2PM
- Drivers with Kids tend to vist Bar 4-8 times in a month.
- Drivers with low income or very high income tend to accept more coupons
- Drivers prefer coupons that expire in a day vs. the ones that expire in 2hrs and these are mosyly passangers that are Alone.
  
#### CoffeeHouse coupon acceptance rate -
- Higher acceptance rate for less frequent in visiting Coffee Houses.
- Higher acceptance rate at 7AM,10Am, 2PM, and 6PM.
- Passengers with No urgent travel destination and with Friends tend to get more coffee.
- Most drivers prefer to go to go have coffee when its Sunny.
- Coupon acceptance is higher for students whose Marital status is single
- Low income groups ( <50K) tend to have higher coupon acceptance rate even if it is in the opposite direction.
- Drivers with low income or very high income tend to accept more coupons
- Drivers prefer coupons that expire in a day vs. the ones that expire in 2hrs
- Higher acceptance rate for ages under 25 and who does atleast 1-3 Carry Away coupons

##### Link to the Junyper Notebook can be found [here] (https://github.com/Sri-Kasturi/AIML---Practical-Application-1/blob/main/Practical_Application_Sri_Kasturi_GitHub.ipynb)

