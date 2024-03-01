# AirBNB New York Dec 2021

Our two big question are:
1. What factors (facilities/prices/customer service) affect revenue the most?
2. How to set appropriate prices to make profits?

Our target audience will be property owners New York (one of the most expensive cities in the world) who want to become hosts on AirBnB.
As our data contains details of listings, as well as their reviews and pricing, one can take a closer look to see how to set a listing strategy to improve rating score as well as boosting revenue from AirBnB properties.

The datasets required to answer the big questions
We decided to get information about all AirBnB listings in: New York (Using Dec 2021 data)
We chose New York because it is in the list of most expensive cities in the world( ). Property owners in these cities have to pay higher expenses for owning a property (higher maintainence fees, land tax, utilities etc.) (**), therefore their AirBnB listings have to generate enough revenue to not only break even but also make profits.

(*) Source: https://globetrender.com/2022/01/06/tel-aviv-ranked-most-expensive-city-world-2021/

(**)Sources: https://streeteasy.com/blog/buying-a-home-in-nyc-everything-you-need-to-know/

https://www.home-hunts.com/blog/hidden-costs-of-buying-property-in-france/

Each of the cities contain the following datasets:

listings.csv.gz: detailed information about listings
listings.csv: a compact version of listings.csv.gz
reviews.csv.gz: detailed information about reviews of listings in the area
reviews.csv: a compact version of reviews.csv.gz
calendar.csv.gz: information about availability of a listings in the next 365 days
neighbourhoods.csv: a list of wards and their corrensponding districts
neighbourhoods.geojson: useful for geo plot
