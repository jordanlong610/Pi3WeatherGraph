# Pi3WeatherGraph
Raspberry Pi 3 will be configured to automatically acquire and log temperature and humidity 
from a AM2302/DHT22/DHT11 sensor and display the collected data on a graph.


1. Start the Temperature and Humidity to CSV Logger
sudo python temperature-and-humidity-to-csv-logger.py 

2. Start the node.js webserver
node nodejs-webserver-with-soap-services.js 

http://raspberrypi:9998/index.html
