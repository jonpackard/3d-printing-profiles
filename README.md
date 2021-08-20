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
