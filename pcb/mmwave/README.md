### Bill of material ###

```
Date    : 2022-07-23
Doc. ID : MMIR-SCH-01
Project : Esphome Mmwave Sensor / Ir Sensor
Title   : Main Board

Part #  : MMIR-V1
REV.    : A

Components : 23
```

------------------------------------------------------------------------------------------------------------------------


| Qty | Ref.      | Description                                 | Value         | Part #            | Footprint             |
|-----|-----------|---------------------------------------------|---------------|-------------------|-----------------------|
| 1   | H5        |                                             | SF2           | -                 | SF2-SensorCap         |
| 1   | J3        | Header - Single Row - 4 Pos                 | I2C           | -                 | HDR-M-1x04            |
| 1   | J4        | Header - Single Row - 6 Pos                 | MMW_SENSOR    | -                 | HDR-M-1x06            |
| 1   | J2        | Header - Dual Row - 6 Pos                   | PROG          | -                 | HDR-M-2x03            |
| 1   | J1        | USB Connector - Type C - 16 Contacts        | -             | USB4105-GF-A      | GCT_USB4105-GF-A      |
| 1   | U1        | 600mA CMOS LDO Regulator with enable        | -             | AP7365-33ERG-13   | SOT-223               |
| 1   | U3        | PIR Motion sensor                           | -             | EKMB1305111K      | PIR-EKMB1310111K-EDGE |
| 1   | U2        | ESP32-C3 Module, 4MB SPI flash, PCB antenna | -             | ESP32-C3-WROOM-02 | ESP32-C3-WROOM        |
| 1   | U4        | Temperature and humidity sensor             | -             | SHT4X             | smt-dfn:DFN4          |
| 2   | C3, C6    | Capacitor                                   | 100nF         | -                 | SMT-0603              |
| 5   | R3-R6, R8 | Resistor                                    | 10k           | -                 | SMT-0603              |
| 1   | C2        | Capacitor                                   | 10uF          | -                 | SMT-0805              |
| 3   | C1, C4-C5 | Capacitor                                   | 1uF           | -                 | SMT-0805              |
| 2   | R1-R2     | Resistor                                    | 5.1k          | -                 | SMT-0603              |
| 1   | Z1        | ESD Supressor                               | CDSOD323-T05C | -                 | smt:SOD-323-NP        |
