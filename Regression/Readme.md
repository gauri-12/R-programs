The data in the accompanying file “Airline data 2.csv” (posted on Canvas) was assembled by Professor Robert Windle of the Smith School with assistance from Oliver Yao. The file contains information on 627 air routes in the United States. A route refers to a pair of airports. Note that some cities are served by more than one airport. In such cases, the airports are distinguished by their 3-letter code. The data was collected for the third quarter of 1996 (3Q96). The variables in the data set are:
1.	S_CODE: starting airport’s code
2.	S_CITY: starting city
3.	E_CODE: ending airport’s code
4.	E_CITY: ending city
5.	COUPON: average number of coupons (a one-coupon flight is a non-stop flight, a two-coupon flight is a one stop flight, etc.) for that route
6.	NEW: number of new carriers entering that route between Q3-96 and Q2-97
7.	VACATION: whether a vacation route (Yes) or not (No); Florida and Las Vegas routes are generally considered vacation routes
8.	SW: whether Southwest Airlines serves that route (Yes) or not (No)
9.	HI: Herfindahl Index – airlines use this as a measure of market concentration (a larger value indicates greater concentration)
10.	S_INCOME: starting city’s average personal income
11.	E_INCOME: ending city’s average personal income
12.	S_POP: starting city’s population
13.	E_POP: ending city’s population
14.	SLOT: whether either endpoint airport is slot controlled or not; this is a measure of airport congestion
15.	GATE: whether either endpoint airport has gate constraints or not; this is another measure of airport congestion
16.	DISTANCE: distance between two endpoint airports in miles
17.	PAX: number of passengers on that route during period of data collection
18.	FARE: average fare on that route

There are two goals of the study. The first is to predict the FARE as a function of the other variables. The second is to determine how the presence of Southwest Airlines affects fares. 
We will not use the first four attributes (S_CODE, S_CITY, E_CODE, and E_CITY) in our analysis. 

