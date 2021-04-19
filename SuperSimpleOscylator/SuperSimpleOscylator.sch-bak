EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title "SuperSimpleOscylator"
Date "2021-04-19"
Rev "0"
Comp "Paweł Dobrowolski"
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L Transistor_BJT:BC337 Q1
U 1 1 607DE5D3
P 6300 3750
F 0 "Q1" H 6491 3796 50  0000 L CNN
F 1 "BC337" H 6491 3705 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-92_Inline" H 6500 3675 50  0001 L CIN
F 3 "https://diotec.com/tl_files/diotec/files/pdf/datasheets/bc337.pdf" H 6300 3750 50  0001 L CNN
	1    6300 3750
	1    0    0    -1  
$EndComp
$Comp
L Device:R R1
U 1 1 607DEB60
P 6400 3000
F 0 "R1" H 6470 3046 50  0000 L CNN
F 1 "1k" H 6470 2955 50  0000 L CNN
F 2 "" V 6330 3000 50  0001 C CNN
F 3 "~" H 6400 3000 50  0001 C CNN
	1    6400 3000
	1    0    0    -1  
$EndComp
$Comp
L Device:R_POT RV1
U 1 1 607DF31D
P 6400 3300
F 0 "RV1" H 6330 3346 50  0000 R CNN
F 1 "50k" H 6330 3255 50  0000 R CNN
F 2 "" H 6400 3300 50  0001 C CNN
F 3 "~" H 6400 3300 50  0001 C CNN
	1    6400 3300
	1    0    0    -1  
$EndComp
$Comp
L Device:R R2
U 1 1 607DF9A8
P 6400 4250
F 0 "R2" H 6470 4296 50  0000 L CNN
F 1 "1R" H 6470 4205 50  0000 L CNN
F 2 "" V 6330 4250 50  0001 C CNN
F 3 "~" H 6400 4250 50  0001 C CNN
	1    6400 4250
	1    0    0    -1  
$EndComp
$Comp
L Device:CP C1
U 1 1 607DFEC9
P 7000 4000
F 0 "C1" H 7118 4046 50  0000 L CNN
F 1 "47uF" H 7118 3955 50  0000 L CNN
F 2 "" H 7038 3850 50  0001 C CNN
F 3 "~" H 7000 4000 50  0001 C CNN
	1    7000 4000
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR0101
U 1 1 607E09C0
P 6400 4600
F 0 "#PWR0101" H 6400 4350 50  0001 C CNN
F 1 "GND" H 6405 4427 50  0000 C CNN
F 2 "" H 6400 4600 50  0001 C CNN
F 3 "" H 6400 4600 50  0001 C CNN
	1    6400 4600
	1    0    0    -1  
$EndComp
Wire Wire Line
	6400 3450 6550 3450
Wire Wire Line
	6550 3450 6550 3300
Wire Wire Line
	6400 3450 6400 3550
Connection ~ 6400 3450
Wire Wire Line
	6400 3950 6400 4050
Wire Wire Line
	6400 4400 6400 4550
Wire Wire Line
	6400 4550 7000 4550
Wire Wire Line
	7000 4550 7000 4150
Connection ~ 6400 4550
Wire Wire Line
	6400 4550 6400 4600
Wire Wire Line
	7000 3850 7000 3550
Wire Wire Line
	7000 3550 6400 3550
Connection ~ 6400 3550
Text GLabel 6400 2800 1    50   Input ~ 0
9V
Wire Wire Line
	6400 2800 6400 2850
NoConn ~ 6100 3750
Text Notes 5150 3950 0    50   ~ 0
Bend 2 leg until it breaks.\nDo not connect to anything.
Text GLabel 5650 4150 0    50   Input ~ 0
+Audio_Out
Text GLabel 5650 4300 0    50   Input ~ 0
-Audio_Out
Connection ~ 6400 4050
Wire Wire Line
	6400 4050 6400 4100
Wire Wire Line
	6400 4550 5800 4550
Wire Wire Line
	5800 4550 5800 4300
Wire Wire Line
	5800 4300 5650 4300
Text Notes 3800 4550 0    50   ~ 0
Audio out can be connected to mono jack\nOr 1R resistor can be replaced with small speaker.
Wire Notes Line
	6800 4000 5700 4000
Wire Notes Line
	5700 4000 5700 3950
Wire Notes Line
	5700 3950 5100 3950
Wire Notes Line
	5100 3950 5100 3750
Wire Notes Line
	5100 3750 5950 3750
Wire Notes Line
	5950 3750 5950 3600
Wire Notes Line
	5950 3600 6800 3600
Wire Notes Line
	6800 3600 6800 4000
Wire Notes Line
	3750 4350 3750 4600
Wire Notes Line
	3750 4600 5900 4600
Wire Notes Line
	5900 4600 5900 4050
Wire Notes Line
	5900 4050 5150 4050
Wire Notes Line
	5150 4050 5150 4350
Wire Notes Line
	5150 4350 3750 4350
Wire Wire Line
	5650 4150 6000 4150
Wire Wire Line
	6000 4150 6000 4050
Wire Wire Line
	6000 4050 6400 4050
$EndSCHEMATC
