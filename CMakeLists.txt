# Adafruit GFX Library Strip
# https://github.com/IcyTrace/Adafruit-GFX-Library-Strip
# BSD License

cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "Adafruit_GFX.cpp" "glcdfont.c"
                       INCLUDE_DIRS "${COMPONENT_DIR}"
                       )

project(Adafruit-GFX-Library-Strip)
