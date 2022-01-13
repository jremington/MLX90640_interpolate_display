# MLX90640_interpolate_display
Code to acquire 32x24 images from MLX90640 IR camera, bicubic interpolate and display as 320x240 image

This project uses a Teensy 3.2 to acquire images from the MLX90640 thermal imaging camera, and displays them on a 480x320 pixel TFT display. 

Adafruit's bicubic interpolation code, obtained from this tutorial https://learn.adafruit.com/adafruit-amg8833-8x8-thermal-camera-sensor?view=all
was modified to allow displays with resolution higher that 256 pixels on the fly. The internal display buffer was eliminated from Adafruit's code.

