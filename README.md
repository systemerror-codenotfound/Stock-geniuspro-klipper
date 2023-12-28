Klipper-Config for my Genius Pro based on this video

https://www.youtube.com/watch?v=7iQK6uSapJ0

You have to use a specific Start Gcode for Prusa:

PRINT_START EXTRUDER_TEMP=[first_layer_temperature] BED_TEMP=[first_layer_bed_temperature]
SET_PRESSURE_ADVANCE ADVANCE=0.068
