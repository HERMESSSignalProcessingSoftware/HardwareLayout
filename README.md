# HardwareLayout

## TODO
- power supply
- stamp connectors
- rxsm connector
- user leds

## Guidelines
* Add a 10k resistor to ground on all critical signal outputs like clocks and resets (except for SF2 reset). This mitigates I/O glitches during power-up and power-down and does not force us to implement power sequencing.