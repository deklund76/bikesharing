# Bikesharing

## Overview

This repository contains a jupyter notebook file that was used to adjust the raw Citibike data obtained directly CitiBikenyc.com as well as a tableau workbook used to create the presentation used in the analysis below.

The purpose of this analysis is to demonstrate to investors the viability and potential profitability of a bike sharing service similar to CitiBike based in Des Moines, Iowa.

## Results

![Trips by Weekday per Hour](https://github.com/deklund76/bikesharing/blob/main/resources/Trips%20by%20Weekday%20per%20Hour.png)

Our analysis begins with a heatmap of bike trips taken throughout the week. It's clear that many New Yorkers find CitiBike useful for their daily commutes during the weekdays and throughout the day for recreation and getting around on weekends. Note that at peak rush hour on Thursday evening, CitiBike has nearly 45,000 users between 6 and 7 PM.

![Trips by Gender (Weekday per Hour)](https://github.com/deklund76/bikesharing/blob/main/resources/Trips%20by%20Gender%20(Weekday%20per%20Hour).png)

Breaking this data down by Gender, we find that Women use the bikes less than men, but at the same times of day. Whether this is due to personal preference or lack of outreach is yet to be determined.

![Customers by Type](https://github.com/deklund76/bikesharing/blob/main/resources/Customers%20by%20Type.png)

CitiBike offers two different options for its users, a subscription service where users pay a flat rate for unlimited usage and a pay per use system for customers who are not subscribed. The Subscribers naturally use the service more often. This should be encouraging for investors as the subscription model provides better stability and means revenues should be generally unaffected by factors such as weather.

![User Trips by Gender by Weekday](https://github.com/deklund76/bikesharing/blob/main/resources/User%20Trips%20by%20Gender%20by%20Weekday.png)

Here we see again that male subscribers ride the bikes most often. What's notable here is that non-subscribers tend to use the bikes most on the weekends. This should inform pricing strategies and marketing. Clearly subscribers are more likely to use the bikes on their daily commutes.

![Checkout Time for Users](https://github.com/deklund76/bikesharing/blob/main/resources/User%20Trips%20by%20Gender%20by%20Weekday.png)

This information is also valuable for determining pricing. The above chart shows that the most common CitiBike trip lasts only 5 minutes. Although many thousands will last longer it's clearly important to have a large number of stations as people tend to not travel particularily far on a given trip.

![Checkout Times by Gender](https://github.com/deklund76/bikesharing/blob/main/resources/Checkout%20times%20by%20Gender.png)

Digging into the trip duration data further and recalling the heatmaps we have alraedy seen, we see that all people regardless of gender have mostly similar usage patterns.

![Bike Utilization](https://github.com/deklund76/bikesharing/blob/main/resources/Bike%20Utilization.png)

We've talked a lot accessibility and revenue potential so far, but the key to profit as we all know is revenue minus expenditures. Besides start-up costs, one of the major expenditures will be recurring maintenance on the bikes themselves. This Visualization should put to rest any fears of out-of-control costs. The larger redder, circles represent the bikes with the most use (time checked out). It's clear from this data that a relatively small number of bikes bear the brunt of the burden meaning repairs shouldn't have a major impact on bike supply and those needing repairs can go for quite some time without them (Note trip duration here is represented in seconds).

## Summary

Overall we've seen that many users find CitiBikes useful for their commutes and are willing to subscribe to the service offerring a stable and steady business. On weekends, many non-subscribers also use the bikes for recreation and transportation. Their is a clear gender-gap in usage and further market research is needed to determine if this represents a baked-in difference in preference or a significant potential for growth. Besides offering consistent business, the bikes are also quite easy and affordable to maintain suggesting good potential for long term profit. For further analysis, a visualization depicting trip durations by customer type would be helpful in informing whether flat fees or usage rates would be more appropriate for non-subscribing customers. To determine how many bike stations should be installed and where, it would also be helpful to have a visulaization charting the distance between start and end locations. Ideally this visualization would be filterable by weekday hour so that station capacity is sufficiently robust for peak hours.
