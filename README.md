# voron24r2
My configuration files for the Voron2.4r2 printer




PrusaSlicer Filament Settings:
ABS - Esun Black
Extruder: 245
Bed: 110
Chamber: 45
Disable fan for the first: 5 layers
SET_PRESSURE_ADVANCE ADVANCE=0.035

ABS - Matterhacker
Extruder: 245
Bed: 110
Chamber: 45
Disable fan for the first: 5 layers
SET_PRESSURE_ADVANCE ADVANCE=0.045

ABS - KVP
Extruder: 245
Bed: 110
Chamber: 45
Disable fan for the first: 5 layers
SET_PRESSURE_ADVANCE ADVANCE=0.05


Printer Settings:
Start G-code
PRINT_START BED=[first_layer_bed_temperature] HOTEND={first_layer_temperature[initial_extruder]+extruder_temperature_offset[initial_extruder]} CHAMBER=[chamber_temperature]
