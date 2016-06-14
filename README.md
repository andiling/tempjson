wat!
Example of some ESP8266 Arduino code to read a ds18b20 temperature sensor 
and present the results as a JSON-ish API.

how!
open it in arduino and upload to your ESP8266. 

status screen in serial monitor will show its ip address.

then hit `http://[ip]/api` and get
```{
	temp: [
  	25,
	  77
	]
}
```

hookup!
[gnd, 3.3v, d4](http://www.modernmethod.com/send/files/tempjsonhookup.jpg)

license!
whatever

