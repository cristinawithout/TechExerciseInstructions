# SUMMARY

In this exercise, you're developing the single page application described in the requirements for the previous exercises.

The product owner has provided the minimum viable product (MVP) requirements below for the user interface. 
Your team lead has provided a functional specification and notes for you.

This is an Ember.js application that, for intervie purposes, you'll be developing the application in an online IDE. 
(Don't worry if you've never used Ember before. The purpose is to test your problem solving 
and how you work with the team, not your Ember expertise.)

# MVP REQUIREMENTS

 * The application SHALL have a title in h1 tag with text “Flight Tracker”. 
 *  The application SHALL have navigation links below the title to: 
   * “Home” 
   * “Airports”  
   * “Flights” 
   * “About” 
 * The Home screen SHALL have welcome text and images. 
 * All pages linked from the navigation SHALL have an h2 tag with text that matches the text in the navigation.  
 * The airports screen SHALL have a list of airports.
   Clicking on an airport from the list SHALL navigate to the airport item screen. 
 * Airport item screen SHALL include: 
   * H2 tag with airport name 
   * Airport details 
   * A list of departing flights 
   * A list of arriving flights 
 * The flight screen SHALL show a list of flights. 
   Clicking on a flight from the list SHALL navigate to the flight item screen.  
 * Flight item screen SHALL include: 
   * H2 tag with flight number 
   * Flight details 
   * A list of the passengers on the flight 
 * The About screen has have a description and image about the application. 
 * In any lists throughout the application: 
   * Airports SHALL display as “<Image> <Airport Name> (<IATA>)”. 
   * Flights SHALL display as “<Number>: <Origin IATA> to <Destination IATA>”. 
   * Passengers SHALL display as “<First Name> <Last Name>”. 

# NOTES FROM YOUR TEAM LEAD
 * The application is located at: https://ember-twiddle.com/b38580216c196ef8668d1dbdb5c651f2
 * The PO has seen and approved the "Home” and “About” screen content. (Nothing else was ready to review with the PO.) 
 * All tests must pass when done. You may add as many tests as needed. Tests can also be removed or updated if appropriate.
 * The "Run Tests" button in Twiddle doesn't work.
 * To run tests in Twiddle: Update twiddle.json.  
   * Set “options.enable-testing” to true. 
   * Set “ENV.environment” to “test”. 
 * The application mocks HTTP requests with Mirage.  
   * The mocks are fully complete. You should not need to modify the mock data in the “mirage” directory.  
   * Mirage has been configured to output API requests and responses to the console. 
 * In Twiddle, if you use File > Add, the component JS files are created using syntax for “Native Components”. 
   The examples in this application and the Ember guides use “Classic Component” syntax. You may create components to use “Classic Component” syntax. 
 * If you are familiar with Ember development, it’s useful to you to know: 
   * In Twiddle, the environment.js file is not used. All ENV values, including “environment” have to be set in twiddle.json. 
   * This application uses the conventional structure, not the pods structure. 
