# airbnb-and-tax-effects

Project in a data science course on economic models.

The goal was to analyze the effects of a new occupancy tax on Airbnb rentals in Boston, MA.



__1__ The Data

First began by familiarizing with the data and data dictionary. This involved trimming down the data to focus on a specific subset which would allow us to get a more equitable view of relationship between the data points.  We narrowed our analysis to weekend nights of only rentals which were entire homes/apartments and got rid of outliers from very high cost rentals and those which took place before the new occupancy tax came into effect.

__2__ Building the Demand Curve

To build a demand curve we filtered down to only the apartments which had been rented and manipulated the numbers such that we could build a proper demand curve which would be monotonically decreasing. Next we evaluated the slope and intercept in order to get a function in terms of price to serve as the equation for our demand curve, followed by computing elasticity.

__3__ Building the Supply Curve

We followed similar steps as in part _2_, manipulating how price was accounted so we our curve would be monotonically increasing as a supply curve should be represented. Again we found the slope and interecept to find a function which expressed our supply curve, followed by calculating the elasticity.

__4__ Solving for Equilibria

Utilizing the supply and demand curves we have calculated, we solved the system of equations to find equilibrium within the market. 

__5__ Introducing a Tax

Lastly, we calculated the demand curve after the occupancy tax had taken effect so we could compare whether this had an impact on rentals within our data. We also concisdered the types economic incidences which would result from this. (*note: we had recieved an updated graph as the one within the project for question 5.3 itself was not correct*). We saw that there did appear that the effect of the tax grew as price of rentals went down, indicating that it did hamper bookings, but we were not able to rule out confounding factors which could have been the cause for a decrease in demand.  
