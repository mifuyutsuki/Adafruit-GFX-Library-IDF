# Adafruit GFX Library
# https://github.com/adafruit/Adafruit-GFX-Library
# BSD License

cmake_minimum_required(VERSION 3.5)

# FORK NOTE: The following libraries are excluded due to requiring components
# of Arduino (SPI and I2C/TwoWire): "Adafruit_GrayOLED.cpp" "Adafruit_SPITFT.cpp"
idf_component_register(SRCS "Adafruit_GFX.cpp" "glcdfont.c"
                       INCLUDE_DIRS ".")

project(Adafruit-GFX-Library)
