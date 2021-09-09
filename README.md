# 3d-printing-profiles
## Info on printers used for testing these profiles:
### Printer: TenLog D3 Pro (TL-D3 Pro)
- Vendor: L.N.L. Solutions
- Main Firmware: D3P PLR Ver 1.0.20
- Screen Firmware: 1.2.5

```
Send: M115
Recv: FIRMWARE_NAME:Marlin V1; Sprinter/grbl mashup for gen6 FIRMWARE_URL:https://www.github.com/tenlog PROTOCOL_VERSION:1.0.0 MACHINE_TYPE:TL 3D Printer EXTRUDER_COUNT:2
```

```
Send: M503
Recv: echo:Steps per unit:
Recv: echo:  M92 X80.00 Y80.00 Z800.00 E92.60
Recv: echo:Maximum feedrates (mm/s):
Recv: echo:  M203 X80.00 Y80.00 Z3.00 E25.00
Recv: echo:Maximum Acceleration (mm/s2):
Recv: echo:  M201 X500 Y500 Z100 E1000
Recv: echo:Acceleration: S=acceleration, T=retract acceleration
Recv: echo:  M204 S500.00 T500.00
Recv: echo:Advanced variables: S=Min feedrate (mm/s), T=Min travel feedrate (mm/s), B=minimum segment time (ms), X=maximum XY jerk (mm/s),  Z=maximum Z jerk (mm/s),  E=maximum E jerk (mm/s)
Recv: echo:  M205 S0.00 T0.00 B20000 X20.00 Z0.40 E5.00
Recv: echo:Home offset (mm):
Recv: echo:  M206 X0.00 Y0.00 Z0.00
Recv: echo:PID settings:
Recv: echo:   M301 P22.23 I1.61 D76.95
Recv: echo:Secondery Max Pos:
Recv: X2:355.40
Recv: echo:Extender Offset:
Recv: Y2:4.30
Recv: echo:Extender Offset:
Recv: Z2:2.00
Recv: Auto Power Off:0
```

### Printer: Kingroon KP3S (Titan Extruder)
- Vendor: Kingroon
- Main Firmware: Stock

```
Send: M115
Recv: FIRMWARE_NAME:Marlin 1.0.0 (Github) SOURCE_CODE_URL:https://github.com/MarlinFirmware/Marlin PROTOCOL_VERSION:1.0 MACHINE_TYPE:3D Printer EXTRUDER_COUNT:2 UUID:cede2a2f-41a2-4748-9b12-c55c62f367ff
Recv: Cap:SERIAL_XON_XOFF:0
Recv: Cap:EEPROM:1
Recv: Cap:VOLUMETRIC:1
Recv: Cap:AUTOREPORT_TEMP:1
Recv: Cap:PROGRESS:0
Recv: Cap:PRINT_JOB:1
Recv: Cap:AUTOLEVEL:1
Recv: Cap:Z_PROBE:1
Recv: Cap:LEVELING_DATA:1
Recv: Cap:BUILD_PERCENT:0
Recv: Cap:SOFTWARE_POWER:0
Recv: Cap:TOGGLE_LIGHTS:0
Recv: Cap:CASE_LIGHT_BRIGHTNESS:0
Recv: Cap:EMERGENCY_PARSER:0
Recv: ok
Send: M155 S2
Recv: ok
```

```
Send: M503
Recv: echo:  G21    ; Units in mm
Recv: 
Recv: echo:Filament settings: Disabled
Recv: echo:  M200 D3.00
Recv: echo:  M200 T1 D3.00
Recv: echo:  M200 D0
Recv: echo:Steps per unit:
Recv: echo:  M92 X160.00 Y160.00 Z800.00
Recv: echo:  M92 T0 E768.00
Recv:   M92 T1 E90.00
Recv: echo:Maximum feedrates (units/s):
Recv: echo:  M203 X200.00 Y200.00 Z4.00
Recv: echo:  M203 T0 E100.00
Recv:   M203 T1 E100.00
Recv: echo:Maximum Acceleration (units/s2):
Recv: echo:  M201 X1000 Y1000 Z100
Recv: echo:  M201 T0 E1000
Recv:   M201 T1 E1000
Recv: echo:Acceleration (units/s2): P<print_accel> R<retract_accel> T<travel_accel>
Recv: echo:  M204 P1000.00 R1000.00 T1000.00
Recv: echo:Advanced: S<min_feedrate> T<min_travel_feedrate> B<min_segment_time_us> X<max_xy_jerk> Z<max_z_jerk> E<max_e_jerk>
Recv: echo:  M205 S0.00 T0.00 B20000 X15.00 Y15.00 Z0.40 E5.00
Recv: echo:Home offset:
Recv: echo:  M206 X0.00 Y0.00 Z0.00
Recv: echo:Hotend offsets:
Recv: echo:  M218 T1 X20.00 Y5.00
Recv: echo:  M420 S0
Recv: echo:Endstop adjustment:
Recv: echo:  M666
Recv: echo:PID settings:
Recv: echo:  M301 P24.00 I0.88 D80.00
Recv: echo:Z-Probe Offset (mm):
Recv: echo:  M851 Z0.00
Recv: ok
```
