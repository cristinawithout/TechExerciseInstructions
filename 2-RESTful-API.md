# SUMMARY

In this exercise, you're working on the same project as the previous exercise (Database). This time, you'll be designing the RESTful API. The same requirements are provided again below for quick reference.

Again, work with your team and use any resources available to you.

# REQUIREMENTS

* The application SHALL have the following sections: 
  * Flights – A list of flights. 
    * Details for each flight contains: 
      * Flight Number – The flight designator 
      * Departure airport – The airport from which the flight will depart. 
      * Arrival airport – The airport to which the flight will arrive.
      * Departure time 
      * Arrival time
      * Passengers – Passenger data consists of First Name, Last Name, and Flight 
  * Airports – A list of airports. 
    * Detail for each airport contains: 
      * Airport Name 
      * ICAO – A 4-character code assigned by the International Civil Aviation Org. 
      * IATA – A 3-character code assigned by the International Air Transport Assoc. 
* Each section SHALL have a screen with a list of items.  
* Clicking on an item from the list SHALL navigate to a page with detail about the item. 
* Users SHALL be able to read, create, update and delete each Flight & Airport. 
* Each passenger belongs to only 1 flight. Passenger data SHALL be populated from another application and must also be stored locally. Passenger data SHALL be read-only.


# TASK

Complete a spec for the API endpoints, including:

* URI
* HTTP methods
* Response body
* HTTP status code(s)
* Query parameters each endpoint will need 

When done, present your proposal to your team lead and describe how the UI will be implemented against this API. 
