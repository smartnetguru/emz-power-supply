# My First Programmable Power Supply

## Ideas
- SMD or Through Hole?
- PFC?

## Specifications
- 0 24 Volts (1mv Resolution)
- 0 2 Amps (1ma Resolution)
- 0 50 Watts (1mw Resolution)
- 16 bit DAC and ADC
- 16 bit Microcontroller
- 24V Toroidal Transformer (33.941vpp, 50+VAC)

## Features
- Enable/Disable Output
- Lock\Unlock Output
- Constant Voltage, Current and Power Modes
- 3x 4 Digit LED Displays One for each measurement

## Possible Op Amps
- LM318		15Mhz, 10-40V, 70v/us, DIP-8
- OPA171
- LM6211
- OPA188

## Possible Voltage References
- LM4132, SOT-23, 3V, 30ppm/°C

## Possible Voltage Regulators
- LT1776		Buck for Microcontroller

## Bill of Materials
| Part Number   | Part Description              | Quantity | Package            |
| ------------- | ----------------------------- | --------:| ------------------ |
| LT4320-1      | Ideal Diode Bridge Controller | 1        | 12-Lead MSOP       |
| IPD220N06L3   | N-Channel Power Transistor    | 4        | 3-Lead DPAK/TO-252 |