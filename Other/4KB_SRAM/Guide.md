# 4KB SRAM module for the TE1600 series
Gives the most possible RAM allowance for the TE16100 and TE16150 CPUs (4KBx16)

## Assembly Guide


## Programming Guide
It is recommended to use the Arduino RAM programmer found in the Homebrew/Other/SSM_1.0/ folder. This acts both as a programmer for the SRAM module and as a secondary storage device capable of hosting a USB memory drive as secondary storagge

## BOM

U1: CY7C1020DV33-10ZSXI 32Kx16 SRAM
U2: SN74LS139ADR demux
J1: Right-angled male 2.54 mm pitch THT header. Notches to prevent the RAM being inserted backwards.
J2: 2 pin right angled male 2.54 mm pitch THT header. Allows for power to be delivered to keep RAM programmed when moving it from the programmer to the motherboard.
