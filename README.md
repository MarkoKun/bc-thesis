# bc-thesis

# description
This bachelor thesis deals with the development of mobile application for the Android operating 
system, in order to monitor the temperature and humidity of the air in the home. The application 
itself also contains additional features, such as GPS locator with map display and current weather 
with outdoor temperature. The measured values using DHT11 sensor, are sent from NodeMcu to 
the firebase realtime database. In tie client-side application, those data are processed and displays 
to the user the current value of measured temperature and humidity. The user also has the 
opportunity, to see the lowest and highest recorded temperature and humidity for last 12 hours. 
For better understanding, those data are also displayed using graphs. This application was created 
for the Android operating system using the Apache Cordova framework. GPS location uses the 
Leafletjs library to obtain the current location. Actual weather is loaded from Openweathermap, 
which provides free external API services.

---

Android application, Leafletjs, JavaScript, HTML, CSS, Firebase, NodeMcu, Apache Cordova, Openweathermap, 
DHT11, Arduino
