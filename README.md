# A_cheap_thermal_camera
build a simple thermal camera based on rasperry and AMG8833 sensor

Requirements:
 - Hardware: Raspberry pi 3, Grideye AMG88xx sparkun(I2C communication)
 - Run on Raspbian, python3
 - library: pygame, colour, Adafruit_AMG88xx, scipy
 
Results:
 - Display thermal object
 - Point out average temp, max temp points, thermistor temperature
 
Evaluation:
 - not high accuracy
 - object is blur
 - start point for thermal image processing
 
References:
- https://github.com/adafruit/Adafruit_AMG88xx_python
- https://makersportal.com/blog/2018/1/25/heat-mapping-with-a-64-pixel-infrared-sensor-and-raspberry-pi
