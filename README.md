Plane API

![plane_api](https://github.com/user-attachments/assets/41b46fcd-8e7b-46a8-bbef-f9941ee02c0f)

Overview
The Plane API is a Python-based project that provides a set of endpoints for managing and retrieving data about flights, airports, and airline schedules. The API offers real-time flight information, allowing users to track flight statuses, obtain airport details, and search for available flights. Built with Python, the API uses external services like Amadeus for fetching live flight and airport data.

Key Features
Flight Status Tracking: Get real-time updates on the status of flights, including departures, arrivals, delays, and cancellations.
Airport Information: Retrieve data on cities and airports worldwide, including their names and locations.
Flight Search: Search for available flights based on criteria such as origin, destination, and date.
Real-Time Data: Provides live updates on flight and airport statuses, ensuring accurate and timely information.
Endpoints
The API integrates with the following external endpoints to fetch the required data:

City and Airport Information:
Endpoint: https://test.api.amadeus.com/v1/reference-data/locations/cities
This endpoint retrieves data on cities and airports worldwide, including their names and locations.
Flight Offers Search:
Endpoint: https://test.api.amadeus.com/v2/shopping/flight-offers
This endpoint allows users to search for available flights by specifying criteria such as origin, destination, and travel dates.
Authentication Token:
Endpoint: https://test.api.amadeus.com/v1/security/oauth2/token
This endpoint is used for obtaining an authentication token, allowing secure access to the Amadeus API.
Technologies Used
Python: The core programming language used to develop the API.
Amadeus API: External APIs from Amadeus are used for accessing flight and airport data.
Use Cases
Travel Applications: Integrate the Plane API into travel apps that need to provide flight and airport information to users.
Flight Tracking Services: Use the API to track flights and provide updates on flight statuses.
Airport Information Systems: Utilize the API to manage and display real-time data about airports.

