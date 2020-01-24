# esp8266TempProject
code for the ESP8266 device for the temperature httpclient.
The device sends a GET Request every 5 min containing JSON to an API, and for the other time it sleeps.

#### Replace the given values with your own 
- SSID (home wireless name) 
- Password (wireless password).
- URL with your own API link. (without the website name)
- Host contains the website name. ex. website.nl (without http(s)

```
const char* ssid     = "";
const char* password = "";
String url = "/api/tempInsert/";
const char* host = "myapi.nl/api"; 
```


![](ESP8266-DHT11.jpg)
