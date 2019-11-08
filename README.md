# XMLScripts-Project-BatteryCharging
Sample scripts that use a Siglent SPD3303X to charge NiMH batteries via SCPI

The scripts are not intended for critical usage - always asume it can be buggy.

To get this repository with all its submodules the following command might be of use 

git clone --recurse-submodules https://github.com/HendriXML/XMLScripts-Project-BatteryCharging.git C:\BatteryCharging

What's needed to use this script?
* Siglent SPD3303X 
* Siglent SDS1104X-E or SDS1204X-E (only required for the measurement script)
* NI VISA setup (only the bare minimum)
* Interpreter executable (64 bit Windows, developed by me)
* Script + Script libraries

## NiMH Battery charging using a SPD3303X.xml
Charges a battery until the voltage drops a certain amount.

## Battery voltage measurement.xml
Charges a battery until the voltage drops a certain amount. The voltage measurements are done using a scope
