# Investigating APIs

in this page i will be talking about the APIs i used in my app:
location , weather and movies API

location API
A fused location provider is Location API. The fused location provider is a Google Play Services location API that intelligently integrates various signals to offer the location data that your app requires. It controls the underlying location technologies, such as GPS and Wi-Fi, and provides a simple API for specifying the desired service quality.

When you enable location and Wi-Fi scanning, you can utilize this function to improve the device's location awareness. It calculates the distance between the phone and the RTT-capable Wi-Fi access point (AP).

authentication key : pk.0671c2e501d32c898422e2b0f03b63eb

endpoints :

+ <https://us1.locationiq.com/v1/search.php?key=YOUR_ACCESS_TOKEN&q=SEARCH_STRING&format=json>

+ <https://eu1.locationiq.com/v1/search.php?key=YOUR_ACCESS_TOKEN&q=SEARCH_STRING&format=json>

these are the links used to access the locationIQ API

the terms : SEARCH_STRING & YOUR_ACCESS_TOKEN are place holders for the values we enter:
YOUR_ACCESS_TOKEN is the authentication key, and when used in netlify (while its hidden in the .env) we cant use it , so we add it in the enviroment variables and setting the value to pk.0671c2e501d32c898422e2b0f03b63eb (access key)

as for SEARCH_STRING, in my web app this variable value is taken from the user , they enter the city they want to explore and it shows right infront fo them

-----------------------------------------------------------------

frontends :


Frontend : git hub repo <https://github.com/LawrenceAbuDubai/city-assignment>

Frontend : netlify <https://cityexplore-lsa.netlify.app/>


backends :


backend : github repo <https://github.com/LawrenceAbuDubai/city-assignment-backend>

backend : heroku app <https://city-explore-lsa.herokuapp.com/>

-----------------------------------------------------------------

references
<https://www.visualcrossing.com/resources/documentation/weather-api/what-is-a-weather-api/>
<https://www.tcl.com/global/en/service-support-mobile/tclplex/What-is-location-API.html>
<https://developers.themoviedb.org/3>
<https://blog.api.rakuten.net/top-10-best-movie-apis-imdb-movie-database-unogs/>
