# PL9823 LED Knight Rider

### PL9823 F5

9823 LED
### Wiring
![Alt text](http://cdn.instructables.com/F9C/BBRM/IHDUL60R/F9CBBRMIHDUL60R.LARGE.jpg "9823")

### Fritzing
![Alt text](http://cdn.instructables.com/FVM/XNSN/IHJES80S/FVMXNSNIHJES80S.LARGE.jpg "Wiring")
### Code
As you can see by the code the most important thing is the line:
```c++
Adafruit_NeoPixel strip = Adafruit_NeoPixel(NUM_PIXELS, PIN, NEO_RGB + NEO_KHZ400);
```
The "NEO_GBR" is for the WS2812b leds model, the NEO_RGB is for this model. The velocity of communication is NEO_KHZ400 for the WS2812 is 800.
