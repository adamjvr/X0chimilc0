# Design Notes

### FPGA Power Supply Voltages
- 1.1V
- 2.5V

### MCU Power Supply Voltages
- 3.3V
- 1.8V
- Voltage ref (check chip) REF6225IDGKT
### Audio Codec Supply Voltages
- 3.3V
- 1.8V

### DDR3L Memory Supply Voltages
- 1.35V
- VTT (what voltage) 0.5-0.9V Ti chip thing


### Proposed Power Supply
- Either High ouput DCDC feeding multiple LDOs or Dual DCDC feeding multiple
LDOs
- 5V LDO 1A
- 3.3V LDO 1A
- DCDC converter feeding LDOs either dual or high current single
- USB C powered
- Lipo Battery Charger over USB C
