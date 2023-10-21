In the USA, a significant part of the wages of many service workers come from tips, nominally voluntary payments by the customer in additional to the listed price.  For taxis in New York, tourist advice suggests a tip of 15-20%. You have data (Modules| Datasets |Taxis ) from two months of taxi trips in New York City, including information on time of day, day of the week, trip distance, price, number of passengers, locations of pickup and dropoff.  

Using the data from week 4 of January 2016, construct a model that predicts the amount of a tip.  Evaluate the mean squared error of this model on the data from week 2 of January 2016.  Write a report that describes how you constructed the model and how accurate it is. 

Notes: 

1. The data sets are fairly large. Each one has a couple of million records. You should still be able to handle them in R, but it is perfectly acceptable to run initial analyses on a subsample of the data, and allowable to run final analyses on a subsample if necessary.

2. As the data dictionary indicates, tip information is not available for all trips

3. These data have not been cleaned; they are as they came from the data provider.

4. You will want to recode variables such as pickup and dropoff time and location into categories: they will not have linear relationships with tip amount. Some graphical exploration is likely to be helpful in addition to thinking about the problem.  If you have problems drawing graphs because of the size of the data, taking  a random subsample of, say, 10% of it can be useful. 

5. The `total_amount` variable is the total amount paid. It includes the tip, and so can't be used to predict the tip.
