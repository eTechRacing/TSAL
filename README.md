# TSAL
The TSAL is an LED light used to indicate the status of the tractive system in an electric vehicle. The purpose of the TSAL is to provide a visual indication of the safety status of the vehicle.

## Functionality
The TSAL must light green when the AIRs and Precharge relay are open and there is no voltage present in the vehicle side of the accumulator. The TSAL must flash red when there is voltage present in any of the DC-Link housings.

#WARNING⚠️
## Please check for changes in ruling. This TSAL is designed following [FSG Rules from 2023](https://www.formulastudent.de/fileadmin/user_upload/all/2023/rules/FS-Rules_2023_v1.1.pdf)

## Installation
- TSAL_Light: must not be installed more than 75mm below the main hoop highest point.
- TSAL_Inverters: must be installed inside any TS enclosure with DC-Link capacitors.
- TSAL_Control: can be installed anywhere. If only one TS enclosure is used, TSAL_Inverters can be replaced with the voltage measurement part of this PCB.
- TSAL_Dummy: if an Accumulator is not available, this PCB can be used to send plausible signals to TSAL_Control and let green light up. Can be implemented without a PCB, only with a connector and wiring.

