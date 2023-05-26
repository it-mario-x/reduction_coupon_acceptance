
# Reduction Coupon Acceptance

## Data overview
This notebook is about an analysis of how probable reduction coupons can be accepted by drivers.
For this purpose, the data available has some details about :
  - the drivers:
    - gender
    - income
    - age
    - maritalStatus
  - external factors:
    - weather
    - temperature
    - time
 
 just to name a few.
 
This analysis focuses in some general insights and then focuses to those drivers who were going to a bar and also where they went in a sunny day. 

Results arte given in the jupyter notebook.

## Analysis workflow

Firstly, data analysis is done in order to know what kind of data we are dealing with. The reader will find out that for some features the data was very scarce. 

Then, cleaning is done (like filling some missing values) and also replacing some dirty values (e.g., for somerows, the same column contains a string and numerical values). We will deal with this when necessary.

Finally, a brief summary of the different acceptance rates is shown. This comparison will help us to know that a given population can be more prone to accept the coupon. This, in turn, can help us to adapt to business strategy for such coupons. We also show what are the preferences of drivers in a sunny day.
