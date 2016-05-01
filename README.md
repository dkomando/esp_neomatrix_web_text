# ESP8266 ESP-01 - NeoPixel NeoMatrix - Text Scroller
This has been tested and works with the Arduino IDE v1.6.7 & v1.6.8  

### Original work by Samir Sogay:
https://www.youtube.com/watch?v=TfzFJkDgg7s  
Original working files are linked from his YouTube video as well.  


## Project Hardware
- [ESP8266 - ESP-01 WiFi Module](https://www.google.com/webhp?sourceid=chrome-instant&ion=1&espv=2&ie=UTF-8#tbs=vw:l,mr:1,price:1,ppr_max:10&tbm=shop&q=esp-01+wi-fi)
- [NeoMatrix x2](https://www.adafruit.com/products/1487)
- Homemade board to hold the ESP8266 & connect the NeoMatrix  


## Project Software / Arduino Libraries Used
### JavaScript Libraries  
- [Spectrum Colorpicker](https://github.com/bgrins/spectrum)  
- [Twitter Bootstrap](http://getbootstrap.com/)  

### Arduino Libraries  
**Make sure to only download these from within the Arduino IDE**  
- [Adafruit-GFX-Library](https://github.com/adafruit/Adafruit-GFX-Library)  
- [Adafruit_NeoPixel](https://github.com/adafruit/Adafruit_NeoPixel)  
- [Adafruit_NeoMatrix](https://github.com/adafruit/Adafruit_NeoMatrix)  
- [ESP8266httpUpdate](https://github.com/esp8266/Arduino)  


## Getting Started
- Download the [Spectrum Colorpicker](https://github.com/bgrins/spectrum) from github and on a server you can access the files. Alternatively you can try to link directly to GitHub which the files are currently setup for.  
- Download this repo & open in the Arduino IDE  
- Download the required Adafruit libraries from inside the Arduino IDE (You may need to visit Adafruit.com for a how-to guide)  
- Define Your WiFi Connection Information:  

```c++
const char* WiFi_SSID = "<SSID-HERE>";
const char* WiFi_PASS = "<PASSWORD-HERE>";
```

- Program / upload this repo to your ESP-01 from within the Arduino IDE
- Connect your NeoMatrix
- Find your ESP-01's IP Address and connect with a browser
- You may need to adjust the direction of the scrolling code "NEO_MATRIX_RIGHT" w/ "NEO_MATRIX_LEFT"
- Have fun!

![Demo Shot](/screenshots/ESP-01-NeoMatrix.png)

![Demo Shot Color Picker Open](/screenshots/ESP-01-NeoMatrix-Colorpicker.png)


### Troubleshooting: some of the original steps to make Samir's code work for me:  
https://forums.adafruit.com/viewtopic.php?f=24&t=87346   
