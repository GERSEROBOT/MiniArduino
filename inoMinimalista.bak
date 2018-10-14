EESchema Schematic File Version 4
LIBS:inoMinimalista-cache
EELAYER 26 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title "Arduino basico"
Date "2018-10-14"
Rev "0.0"
Comp "Mini curso Kicad"
Comment1 "Arduino basico mais hardware minimo"
Comment2 "Pedro Igor B. S."
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L MCU_Microchip_ATmega:ATmega328P-PU U1
U 1 1 5BBBDF8C
P 2700 2650
F 0 "U1" V 2150 2250 50  0000 R CNN
F 1 "ATmega328P-PU" V 2150 1900 50  0000 R CNN
F 2 "Package_DIP:DIP-28_W7.62mm" H 2700 2650 50  0001 C CIN
F 3 "http://ww1.microchip.com/downloads/en/DeviceDoc/ATmega328_P%20AVR%20MCU%20with%20picoPower%20Technology%20Data%20Sheet%2040001984A.pdf" H 2700 2650 50  0001 C CNN
	1    2700 2650
	1    0    0    -1  
$EndComp
$Comp
L power:Earth #PWR05
U 1 1 5BBBE117
P 2700 4250
F 0 "#PWR05" H 2700 4000 50  0001 C CNN
F 1 "Earth" H 2700 4100 50  0001 C CNN
F 2 "" H 2700 4250 50  0001 C CNN
F 3 "~" H 2700 4250 50  0001 C CNN
	1    2700 4250
	1    0    0    -1  
$EndComp
Wire Wire Line
	2700 4250 2700 4200
Wire Wire Line
	2100 1450 2050 1450
Wire Wire Line
	2050 1450 2050 4200
Wire Wire Line
	2050 4200 2700 4200
Connection ~ 2700 4200
Wire Wire Line
	2700 4200 2700 4150
$Comp
L Device:CP_Small C2
U 1 1 5BBBE2AC
P 5150 3400
F 0 "C2" H 5238 3446 50  0000 L CNN
F 1 "0u1F" H 5238 3355 50  0000 L CNN
F 2 "Capacitor_THT:CP_Radial_D5.0mm_P2.50mm" H 5150 3400 50  0001 C CNN
F 3 "~" H 5150 3400 50  0001 C CNN
	1    5150 3400
	1    0    0    -1  
$EndComp
Text GLabel 3400 2950 2    39   Input ~ 0
RST
Wire Wire Line
	3400 2950 3300 2950
$Comp
L Device:R R1
U 1 1 5BBBE420
P 5150 3050
F 0 "R1" H 5200 3100 50  0000 L CNN
F 1 "10k" V 5150 3000 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P10.16mm_Horizontal" V 5080 3050 50  0001 C CNN
F 3 "~" H 5150 3050 50  0001 C CNN
	1    5150 3050
	1    0    0    -1  
$EndComp
Wire Wire Line
	5150 3200 5150 3250
$Comp
L power:Earth #PWR03
U 1 1 5BBBE54C
P 5150 3600
F 0 "#PWR03" H 5150 3350 50  0001 C CNN
F 1 "Earth" H 5150 3450 50  0001 C CNN
F 2 "" H 5150 3600 50  0001 C CNN
F 3 "~" H 5150 3600 50  0001 C CNN
	1    5150 3600
	1    0    0    -1  
$EndComp
Wire Wire Line
	5150 3600 5150 3500
$Comp
L power:+5V #PWR02
U 1 1 5BBBE6EA
P 5150 2800
F 0 "#PWR02" H 5150 2650 50  0001 C CNN
F 1 "+5V" H 5165 2973 50  0000 C CNN
F 2 "" H 5150 2800 50  0001 C CNN
F 3 "" H 5150 2800 50  0001 C CNN
	1    5150 2800
	1    0    0    -1  
$EndComp
Wire Wire Line
	5150 2800 5150 2900
Text GLabel 5000 3250 0    39   Input ~ 0
RST
Wire Wire Line
	5000 3250 5150 3250
Connection ~ 5150 3250
Wire Wire Line
	5150 3250 5150 3300
$Comp
L Device:C_Small C1
U 1 1 5BBBEBB2
P 5950 3250
F 0 "C1" H 6042 3296 50  0000 L CNN
F 1 "22pF" H 6042 3205 50  0000 L CNN
F 2 "Capacitor_THT:C_Disc_D3.0mm_W1.6mm_P2.50mm" H 5950 3250 50  0001 C CNN
F 3 "~" H 5950 3250 50  0001 C CNN
	1    5950 3250
	1    0    0    -1  
$EndComp
$Comp
L Device:C_Small C3
U 1 1 5BBBEC5F
P 6500 3250
F 0 "C3" H 6592 3296 50  0000 L CNN
F 1 "22pF" H 6592 3205 50  0000 L CNN
F 2 "Capacitor_THT:C_Disc_D3.0mm_W1.6mm_P2.50mm" H 6500 3250 50  0001 C CNN
F 3 "~" H 6500 3250 50  0001 C CNN
	1    6500 3250
	1    0    0    -1  
$EndComp
$Comp
L Device:Crystal Y1
U 1 1 5BBBEDBD
P 6250 2950
F 0 "Y1" H 6250 3218 50  0000 C CNN
F 1 "Crystal" H 6250 3127 50  0000 C CNN
F 2 "Crystal:Crystal_HC18-U_Vertical" H 6250 2950 50  0001 C CNN
F 3 "~" H 6250 2950 50  0001 C CNN
	1    6250 2950
	1    0    0    -1  
$EndComp
Wire Wire Line
	6100 2950 5950 2950
Wire Wire Line
	5950 2950 5950 3150
Wire Wire Line
	6400 2950 6500 2950
Wire Wire Line
	6500 2950 6500 3150
$Comp
L power:Earth #PWR04
U 1 1 5BBBF286
P 6500 3450
F 0 "#PWR04" H 6500 3200 50  0001 C CNN
F 1 "Earth" H 6500 3300 50  0001 C CNN
F 2 "" H 6500 3450 50  0001 C CNN
F 3 "~" H 6500 3450 50  0001 C CNN
	1    6500 3450
	1    0    0    -1  
$EndComp
$Comp
L power:Earth #PWR01
U 1 1 5BBBF29D
P 5950 3450
F 0 "#PWR01" H 5950 3200 50  0001 C CNN
F 1 "Earth" H 5950 3300 50  0001 C CNN
F 2 "" H 5950 3450 50  0001 C CNN
F 3 "~" H 5950 3450 50  0001 C CNN
	1    5950 3450
	1    0    0    -1  
$EndComp
Wire Wire Line
	5950 3450 5950 3350
Wire Wire Line
	6500 3450 6500 3350
Text GLabel 5850 2950 0    39   Input ~ 0
XTL1
Wire Wire Line
	5850 2950 5950 2950
Connection ~ 5950 2950
Text GLabel 6600 2950 2    39   Input ~ 0
XTL2
Wire Wire Line
	6600 2950 6500 2950
Connection ~ 6500 2950
Text GLabel 3400 2150 2    39   UnSpc ~ 0
XTL2
Wire Wire Line
	3400 2150 3300 2150
Text GLabel 3400 2050 2    39   UnSpc ~ 0
XTL1
Wire Wire Line
	3400 2050 3300 2050
$Comp
L Connector:Conn_01x14_Male J1
U 1 1 5BBC10FE
P 4700 1450
F 0 "J1" V 4550 1450 50  0000 C CNN
F 1 "16-28" V 4650 1450 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x14_P2.54mm_Vertical" H 4700 1450 50  0001 C CNN
F 3 "~" H 4700 1450 50  0001 C CNN
	1    4700 1450
	0    -1   1    0   
$EndComp
Text GLabel 3400 1450 2    39   BiDi ~ 0
PB0
Wire Wire Line
	3400 1450 3300 1450
Text GLabel 3400 1550 2    39   BiDi ~ 0
PB1
Text GLabel 3400 1650 2    39   BiDi ~ 0
PB2
Text GLabel 3400 1750 2    39   BiDi ~ 0
PB3
Text GLabel 3400 1850 2    39   BiDi ~ 0
PB4
Text GLabel 3400 1950 2    39   BiDi ~ 0
PB5
Wire Wire Line
	3400 1950 3300 1950
Wire Wire Line
	3400 1850 3300 1850
Wire Wire Line
	3400 1750 3300 1750
Wire Wire Line
	3400 1650 3300 1650
Wire Wire Line
	3400 1550 3300 1550
Text GLabel 3400 3150 2    39   BiDi ~ 0
PD0
Text GLabel 3400 3250 2    39   BiDi ~ 0
PD1
Text GLabel 3400 3350 2    39   BiDi ~ 0
PD2
Text GLabel 3400 3450 2    39   BiDi ~ 0
PD3
Text GLabel 3400 3550 2    39   BiDi ~ 0
PD4
Text GLabel 7000 1750 3    39   BiDi ~ 0
PD5
Text GLabel 6900 1750 3    39   BiDi ~ 0
PD6
Text GLabel 6800 1750 3    39   BiDi ~ 0
PB7
Wire Wire Line
	3400 3150 3300 3150
Wire Wire Line
	3300 3250 3400 3250
Wire Wire Line
	3400 3350 3300 3350
Wire Wire Line
	3300 3450 3400 3450
Wire Wire Line
	3400 3550 3300 3550
Text GLabel 3400 2350 2    39   BiDi ~ 0
PC0
Text GLabel 3400 2450 2    39   BiDi ~ 0
PC1
Text GLabel 3400 2550 2    39   BiDi ~ 0
PC2
Text GLabel 3400 2650 2    39   BiDi ~ 0
PC3
Text GLabel 3400 2750 2    39   BiDi ~ 0
PC4
Text GLabel 3400 2850 2    39   BiDi ~ 0
PC5
Wire Wire Line
	3400 2350 3300 2350
Wire Wire Line
	3400 2450 3300 2450
Wire Wire Line
	3300 2550 3400 2550
Wire Wire Line
	3400 2650 3300 2650
Wire Wire Line
	3300 2750 3400 2750
Wire Wire Line
	3400 2850 3300 2850
$Comp
L Device:LED_ALT D1
U 1 1 5BBDA20C
P 4450 2900
F 0 "D1" V 4395 2979 50  0000 L CNN
F 1 "LED_ALT" V 4486 2979 50  0000 L CNN
F 2 "LED_THT:LED_D3.0mm" H 4450 2900 50  0001 C CNN
F 3 "~" H 4450 2900 50  0001 C CNN
	1    4450 2900
	0    1    1    0   
$EndComp
$Comp
L Device:R R2
U 1 1 5BBDA3A0
P 4450 3300
F 0 "R2" H 4500 3350 50  0000 L CNN
F 1 "330" V 4450 3250 50  0000 L CNN
F 2 "MyFootprint:Resistor_Vertical_RM3mm" V 4380 3300 50  0001 C CNN
F 3 "~" H 4450 3300 50  0001 C CNN
	1    4450 3300
	1    0    0    -1  
$EndComp
Wire Wire Line
	4450 3150 4450 3050
Text GLabel 4450 2650 1    39   Input ~ 0
PB5
Wire Wire Line
	4450 2650 4450 2750
$Comp
L power:Earth #PWR06
U 1 1 5BBDB4B0
P 4450 3600
F 0 "#PWR06" H 4450 3350 50  0001 C CNN
F 1 "Earth" H 4450 3450 50  0001 C CNN
F 2 "" H 4450 3600 50  0001 C CNN
F 3 "~" H 4450 3600 50  0001 C CNN
	1    4450 3600
	1    0    0    -1  
$EndComp
Wire Wire Line
	4450 3600 4450 3450
Text GLabel 5750 1750 3    39   Output ~ 0
RST
$Comp
L power:+5V #PWR07
U 1 1 5BBDC44C
P 2750 900
F 0 "#PWR07" H 2750 750 50  0001 C CNN
F 1 "+5V" H 2765 1073 50  0000 C CNN
F 2 "" H 2750 900 50  0001 C CNN
F 3 "" H 2750 900 50  0001 C CNN
	1    2750 900 
	1    0    0    -1  
$EndComp
Wire Wire Line
	2700 1150 2700 1050
Wire Wire Line
	2700 1050 2750 1050
Wire Wire Line
	2800 1150 2800 1050
Wire Wire Line
	2800 1050 2750 1050
Connection ~ 2750 1050
Wire Wire Line
	2750 900  2750 1050
Text GLabel 5850 1750 3    39   BiDi ~ 0
PD0
Text GLabel 5950 1750 3    39   BiDi ~ 0
PD1
Text GLabel 6050 1750 3    39   BiDi ~ 0
PD2
Text GLabel 6150 1750 3    39   BiDi ~ 0
PD3
Text GLabel 6250 1750 3    39   BiDi ~ 0
PD4
Wire Wire Line
	5850 1750 5850 1650
Wire Wire Line
	5950 1650 5950 1750
Wire Wire Line
	6050 1750 6050 1650
Wire Wire Line
	6150 1650 6150 1750
Wire Wire Line
	6250 1750 6250 1650
Wire Wire Line
	5750 1750 5750 1650
$Comp
L power:+5V #PWR010
U 1 1 5BBE3E5D
P 6350 1950
F 0 "#PWR010" H 6350 1800 50  0001 C CNN
F 1 "+5V" V 6350 2150 50  0000 C CNN
F 2 "" H 6350 1950 50  0001 C CNN
F 3 "" H 6350 1950 50  0001 C CNN
	1    6350 1950
	1    0    0    1   
$EndComp
Wire Wire Line
	6350 1950 6350 1650
$Comp
L power:Earth #PWR011
U 1 1 5BBE4B2B
P 6450 1950
F 0 "#PWR011" H 6450 1700 50  0001 C CNN
F 1 "Earth" H 6450 1800 50  0001 C CNN
F 2 "" H 6450 1950 50  0001 C CNN
F 3 "~" H 6450 1950 50  0001 C CNN
	1    6450 1950
	1    0    0    -1  
$EndComp
Wire Wire Line
	6450 1950 6450 1650
Wire Wire Line
	6700 1750 6700 1650
Wire Wire Line
	6800 1750 6800 1650
Wire Wire Line
	6900 1750 6900 1650
$Comp
L Connector:Conn_01x08_Male J2
U 1 1 5BBEC38B
P 6050 1450
F 0 "J2" V 5885 1377 50  0000 C CNN
F 1 "PD" V 5976 1377 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x08_P2.54mm_Vertical" H 6050 1450 50  0001 C CNN
F 3 "~" H 6050 1450 50  0001 C CNN
	1    6050 1450
	0    -1   1    0   
$EndComp
Text GLabel 3400 3650 2    39   BiDi ~ 0
PD5
Text GLabel 3400 3750 2    39   BiDi ~ 0
PD6
Text GLabel 3400 3850 2    39   BiDi ~ 0
PB7
Wire Wire Line
	3300 3650 3400 3650
Wire Wire Line
	3300 3750 3400 3750
Wire Wire Line
	3300 3850 3400 3850
$Comp
L Connector:Conn_01x04_Male J3
U 1 1 5BBEFE9F
P 6800 1450
F 0 "J3" V 6650 1400 50  0000 L CNN
F 1 "PD" V 6750 1400 50  0000 L CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x04_P2.54mm_Vertical" H 6800 1450 50  0001 C CNN
F 3 "~" H 6800 1450 50  0001 C CNN
	1    6800 1450
	0    -1   1    0   
$EndComp
Text GLabel 6700 1750 3    39   BiDi ~ 0
PB0
Wire Wire Line
	7000 1650 7000 1750
Text GLabel 4100 1750 3    39   BiDi ~ 0
PB1
Text GLabel 4200 1750 3    39   BiDi ~ 0
PB2
Text GLabel 4300 1750 3    39   BiDi ~ 0
PB3
Text GLabel 4400 1750 3    39   BiDi ~ 0
PB4
Text GLabel 4500 1750 3    39   BiDi ~ 0
PB5
Wire Wire Line
	4500 1750 4500 1650
Wire Wire Line
	4400 1750 4400 1650
Wire Wire Line
	4300 1750 4300 1650
Wire Wire Line
	4200 1750 4200 1650
Wire Wire Line
	4100 1750 4100 1650
$Comp
L power:+5V #PWR08
U 1 1 5BC02EC2
P 4600 1900
F 0 "#PWR08" H 4600 1750 50  0001 C CNN
F 1 "+5V" V 4600 2100 50  0000 C CNN
F 2 "" H 4600 1900 50  0001 C CNN
F 3 "" H 4600 1900 50  0001 C CNN
	1    4600 1900
	-1   0    0    1   
$EndComp
Wire Wire Line
	4600 1900 4600 1650
$Comp
L power:Earth #PWR09
U 1 1 5BC0403A
P 4750 1900
F 0 "#PWR09" H 4750 1650 50  0001 C CNN
F 1 "Earth" H 4750 1750 50  0001 C CNN
F 2 "" H 4750 1900 50  0001 C CNN
F 3 "~" H 4750 1900 50  0001 C CNN
	1    4750 1900
	1    0    0    -1  
$EndComp
Text GLabel 4900 1750 3    39   BiDi ~ 0
PC0
Text GLabel 5000 1750 3    39   BiDi ~ 0
PC1
Text GLabel 5100 1750 3    39   BiDi ~ 0
PC2
Text GLabel 5200 1750 3    39   BiDi ~ 0
PC3
Text GLabel 5300 1750 3    39   BiDi ~ 0
PC4
Text GLabel 5400 1750 3    39   BiDi ~ 0
PC5
Wire Wire Line
	4900 1750 4900 1650
Wire Wire Line
	5000 1750 5000 1650
Wire Wire Line
	5100 1650 5100 1750
Wire Wire Line
	5200 1750 5200 1650
Wire Wire Line
	5300 1650 5300 1750
Wire Wire Line
	5400 1750 5400 1650
Wire Wire Line
	4800 1650 4800 1700
Wire Wire Line
	4800 1700 4750 1700
Wire Wire Line
	4700 1700 4700 1650
Wire Wire Line
	4750 1900 4750 1700
Connection ~ 4750 1700
Wire Wire Line
	4750 1700 4700 1700
Wire Notes Line
	7300 650  1850 650 
Wire Notes Line
	1850 4400 7300 4400
Wire Notes Line
	7300 650  7300 4400
Wire Notes Line
	1850 650  1850 4400
$EndSCHEMATC
