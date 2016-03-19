# Adafruit LIS3DH Python driver
Using initial build by Matt Dyson
This build:
1. Adds Click detection - initiatilation routine for either single click or double click detection as per data sheet
2. Click detection either bu polling register or using a GPIO interrupt with user defined handler.
3. partitions the driver class and the test calls
4. Fixes bug in 16G Range (incorrect divisor)
