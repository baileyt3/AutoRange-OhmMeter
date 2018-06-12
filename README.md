# AutoRange-OhmMeter
Autorange resistance measurement using Arduino
Will measure resistances from short circuit to ~5M Ohms
The code performs Autorange until either it finds and displays the correst resistance
or 'Out of Limits' if the resistance is too high or open circuit.
Output is via Serial Monitor (can turn this on/off by setting 1/0 in the code) and
to an attached LCD.
