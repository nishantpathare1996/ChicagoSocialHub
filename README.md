# ChicagoSocialHub

## Overview:
- The app-user shall be able to specify the search conditions using two fields to represent the pair (business-category, street-name).
- The search results for top rated Yelp-reviewed places based on the specified filter by the app-user shall be displayed on a webpage.
-	The app-user shall be provided with the capability to view the real-time status for the near-by Divvy docking stations of the selected place 	along with Google map for the current location, the selected place location, and the nearest 3 Divvy docking stations of the selected place.

## Technology Stack:
-Angular 11
-Node.js/Express
-PostgreSQL- to store Divvy stations realtime status
-ElasticSearch - to store Yelp reviews for Chicago Businesses

## Folder Contents:
1. backend
  - The backend folder consists of the server.js file (file name in the server).
2. backend-build-divvy-status
	- The backend-build-divvy-status folder consists of the python script(divvy_stations_status.ipynb) that is used to connect and store Divvy station status onto the PostgreSQL database.
	
3. backend-build-yelp-reviews
	- The backend-build-yelp-reviews folder consists of the python script(ChicagpSocialHub-Yelp.ipynb) that is used to store Yelp reviews for Chicago Businesses on ElasticSearch database.

4. frontend
	- The frontend folder consists of all code files (.ts, .html, .css) for building the application frontend. 
