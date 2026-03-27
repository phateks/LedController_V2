# LED Controller (ESP32-C3-Mini)

<table>
	<tr>
		<td><img src="Images/top_layer.png" alt="PCB Top" width="420" /></td>
		<td><img src="Images/bottom_layer.png" alt="PCB Bottom" width="420" /></td>
	</tr>
</table>


## Power
- Input: 12 or 24 VDC on J1 connector


## Connections for Digital LED
- DO (DATA) 
- LED+ = VCC
- LED- = GND

## Connections for Classic LED
- LED+ = VCC
- Dim- = GND

## External Switch (Momentary)

- S1 - Dim down
- S2 - Dim up
- Com - Second connection on the switch (common for both)


## GPIO Config

- IO4: DATA LED
- IO5: PWM LED
- IO6: Dim Up
- IO7: Dim Down
- TXD0/RXD0: 
- EN: reset/enable
- BOOT: bootloader (IO09)




