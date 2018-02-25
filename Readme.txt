Site name : VoyageBuddy
The website/app aims at helping you plan your travel smartly .It acts as a saviour when you know:
*** you want to travel 
*** you have only XX $ in your pocket to spare
*** your vacation is of n days 
*** You know that places with beaches interest you though history sounds boring
but you are clueless about where all you can go and get an optimal trip.

Amadeus APIs used/plan to be used:--
*** Flight Inspiration search: To recursivley get the favourable destinations from the origin within the budget.
*** Flight Low Fare Search: To make the flight bookings
*** YapQ City Name Search: To get the latitudes and longitudes  of the destinations cities
*** YapQ Geosearch: To get the points of interest in the destination cities and categorize the cities.(e.g. beaches, historical,hilly,luxury,etc.)
*** Hotel Airport Search: To get the list of hotels near the destination airports
*** Car Rental Airport Search: To get the best possible car rentals near the airport

Sample Test Data:-
Input:
        ** Origin:Chicago
        ** Duration:7
        ** Departure Dates: 02/23/18-02/25/18
        ** Budget: 1000$
        
Output:
        ** You can pick either of the itineraries : 
                -->Chicago - Boston - New York - Chicago                Approximate fare: 890$
                         02/23/18 - 02/26/18 - 02/30/18
                -->Chicago - Paris - Chicago                            Approximate fare: 980$
                        02/23/18 - 02/30/18 
                -->Chicago - LosAngeles - Connecticut - Chicago         Approximate fare: 750$
                        02/24/18 - 02/26/18 - 02/30/18
                -->Chicago - London - Chicago                           Approximate fare: 820$
                        02/23/18 - 02/29/18
          ** Once the user selects the interesting itinerary, it gives you all the points of interest of the destination cities.
          ** Then the user is promted to book the flights for the slected itinerary.
          ** Based on the destinations, hotel booking is called.
          ** On the basis of multiple stops , the car rentals are suggested and booked.
Unique Features: 
** Unlike most of the apps and serach engines present today , it does not fixes the destination , ather suggests them .
** It gives an opimal path from origin to your destination enabling you to visit as many and as interesting places as possible.

Technologies used: 
Java script, HTML, CSS, Ajax, Jquery

Team members: 
Saba Kathawala, Deepika Tripathi, Mohit Kumar Paritosh Ghia
