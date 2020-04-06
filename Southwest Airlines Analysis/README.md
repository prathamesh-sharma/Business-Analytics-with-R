A consulting firm working for Southwest Airlines would like to predict airfares using
Airfares.csv, which contains real data that were collected between Q3-1996 and Q2-
1997. The variables in these data are listed below. Some airport-to-airport data (e.g.,
JFK-BWI) are available, but most data are at the city-to-city level (e.g., Atlanta-Boston).
A key question is whether the presence or absence of Southwest Airlines (a low-cost
entrant) would have any effect on fare.

Variable Description:
S_CODE: Starting airport’s code
S_CITY: Starting city
E_CODE: Ending airport’s code
E_CITY: Ending city
COUPON: Average number of coupons for that route (a one-coupon flight is a nonstop
flight, a two-coupon flight is a one-stop flight, etc.)
NEW: Number of new carriers entering that route between Q3-96 and Q2-97
VACATION: Whether (Yes) or not (No) a vacation route
SW: Whether (Yes) or not (No) Southwest Airlines serves that route
HI: Herfindahl index, a measure of market concentration (higher number means
smaller number of available carriers on that route)
S_INCOME: Starting city’s average personal income
E_INCOME: Ending city’s average personal income
S_POP: Starting city’s population
E_POP: Ending city’s population
SLOT: Whether or not either endpoint airport is slot-controlled (this is a measure of
airport congestion)
GATE: Whether or not either endpoint airport has gate constraints (this is another
measure of airport congestion)
DISTANCE: Distance between two endpoint airports in miles
PAX: Number of passengers on that route during period of data collection
FARE: Average fare on that route
