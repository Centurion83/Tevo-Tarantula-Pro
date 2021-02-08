# Tevo_Tarantula-Pro-Marlin-2.x 



CENTURION 3D Configurations

- Increased the BLTOUCH Homing Speed/ While maintaining accuracy

- Correct PID settings Applied

- Runs Great as is, or make changes to your area of use.


- Instructions for setting your Z-OFFSET

1. Home 3D printer
2. M851 Z0 - Reset Z0Offset
3. M500 - Store setting to eeprom
4. M501 - Set active parameters
5. M503 - Display Active Parameters
6. G28 Z - Home Z Axis
7. G1 F60 Z0 - Move nozzle to true 0 offset
8. M211 S0 - Switch off soft endstops
9. Move nozzle towards bed slowly until the paper can barely move
10. Take note of the Z on the printer display (take that number and add the measurment of the calibration sheet or device used)
11. M851 Z X.XX (X.XX being your z offset achieved)
12. M211 S1 - Enable Soft Endstops
13. M500 - Save settings to Eeprom
14. M501 - Set Active Parameters
15. M503 - display current settings
16. G28 - Home Printer
17. G1 F60 Z0 - test settings, they should be what you set them for but showing Z@0

Marlin 2.0.X for the GREEN Tevo Tarantula Pro. Dual Z Axis/ BLtouch / 2208 Drivers / MKS_GEN_L Board V1. This Build Compiles easy with Arduino. The Z Axis down Movement is set slow so you may have to adjust that. Other then that there is ZERO issues with this build. 

<img class="rg_i Q4LuWd" data-src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSugpycDw0s2usJlKQczXpqftzE5A-u0zfnFA&amp;usqp=CAU" data-lt="" jsname="Q4LuWd" alt="Image result for gladiator helmet art" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSugpycDw0s2usJlKQczXpqftzE5A-u0zfnFA&amp;usqp=CAU" width="120" height="340"><center>


