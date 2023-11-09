# Weather-App
I started this project when I was learning Java Servlets and JSP and decided to create this dynamic web application to pull data from different weather APIs to display data and maps.
Starting with index.html, the user enters a zipcode and submits. Current weather data is pulled from openweathermap.org and weatherapi.com and is displayed in a simple table in indx.jsp.
The 7-day forecast data is pulled from NOAA at weather.gov and displayed with it's supplied icons and detailed descriptions of upcoming weather.
I used Google Maps API to display a map of the area and used either ClimaCell or openWeatherMap weather layers to overlay the map and show precipitation, cloud cover, and temperature. The radio buttons will update the map with the new layer when clicked.
**This was built in Eclipse running on Apache Tomcat so you will need a web server running. I also needed to install json-simple-1.1.jar to handle the JSON files in Java: http://www.java2s.com/Code/Jar/j/Downloadjsonsimple11jar.htm
