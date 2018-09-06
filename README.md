# VoyageBuddy
Hackillinois 2018

The website/app aims at helping you plan your travel smartly. It acts as a saviour when you know:
* you want to travel 
* you have only XX $ in your pocket to spare
* your vacation is of n days 
* You know that places with beaches interest you while history sounds boring
* But you are clueless about where all you can go and get an optimal trip.

# Amadeus APIs used/plan to be used:
* Flight Inspiration search: To recursivley get the favourable destinations from the origin within the budget.
* Flight Low Fare Search: To make the flight bookings
* YapQ City Name Search: To get the latitudes and longitudes  of the destinations cities
* YapQ Geosearch: To get the points of interest in the destination cities and categorize the cities.(e.g. beaches, historical,hilly,luxury,etc.)
* Hotel Airport Search: To get the list of hotels near the destination airports
* Car Rental Airport Search: To get the best possible car rentals near the airport

# Assumptions:
* Data provided by the APIs is correct and absolute
* For the prototype , we only show maximum upto 3 stopovers per itinerary


# Sample Test Data:-
Input:
* Origin:Chicago
* Duration:7
* Departure Dates: 02/23/18-02/25/18
* Budget: 1000$
        
# Output:
* You can pick either of the itineraries : 

| No. |                Places .                  |                 Dates          | Approximate Fare |
| --- | ---------------------------------------- | ------------------------------ | :---: |
|  1. | Chicago - Boston - New York - Chicago    | 02/23/18 - 02/26/18 - 02/30/18 |$890       |
|  2. | Chicago - Paris - Chicago                | 02/23/18 - 02/30/18  | $980 |
|  3. | Chicago - LosAngeles - Connecticut - Chicago     | 02/24/18 - 02/26/18 - 02/30/18 | $750 |
|  4. | Chicago - London - Chicago   | 02/23/18 - 02/29/18 | $820 |
   
# Planned enhancements: 
* Once the user selects the interesting itinerary, it gives you all the points of interest of the destination                    cities.
* Then the user is promted to book the flights for the slected itinerary.
* Based on the destinations, hotel booking is called.
* On the basis of multiple stops , the car rentals are suggested and booked.

# Unique Features: 
* Unlike most of the apps and search engines present today , it does not fix the destination , rather suggests them.
* It gives an optimal path from origin to your destination enabling you to visit as many and as interesting places as possible.

# Technologies used: 
JavaScript, HTML, CSS, AJAX, Jquery, Express, Node.js

# Team members: 
Saba Kathawala, Deepika Tripathi, Mohit Kumar Paritosh Ghia
