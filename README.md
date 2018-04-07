# edc-power-distro-board
Power distribution board for my EDC harness project

Has individual switches, probably using MOSFETS and low voltage switching. Both
direct electrical low voltage control via switch and microprocessor control as
well.

Use high amperage switchcraft connectors for all dc connectors and include extra fuses

size wires and fuses for 10A which is under rated current of high amperage connectors.

Separate fuses in each individual component.


## Power Requirements

| Component     | Power Requirements | Current at 12V   | Notes |
|:--------------|:-------------------:|:-----------------:|:------|
| EDC Mux board |     6.22W ->7.2W   | 518.4mA -> 600mA | includes rounded estimates for voltage rail conversions |
| Line Mixer    | 500mW              | 41.67mA -> 50mA  | includes rounded estimates for voltage rail conversions |
| Flashlight Connector Box | 96W     | 8A maximum | 4 flashlights at 2A each |
