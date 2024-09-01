# Universal ECU Recommended wiring 

pin                    - wire colour       - Function
1A1 - GND              - brown             - GND
1A2 - GND              - brown             - GND
1A3 - VR+D             -                   - CAM VR+
1A4 - VR-D             -                   - CAM VR-
1B1 - GND              - brown             - GND
1B2 - GND              - brown             - GND
1B3 - 5V2              - orange            - 5V sensor supply MAP OR MAF
1B4 - 5V2              - red               - 5V sensor supply TPS
1C1 - GND              - brown             - GND for knock shields,
1C2 - GND              - brown             - GND 
1C3 - 5V2
1C4 - 5V2
1D1 - KNK1             - green             - Knock 2
1D2 - KNK2             - yellow            - Knock 1
1D3 - 5V1              - red/green         - 5V for sensors
1D4 - 5V1              - red/green         - 5V for sensors
1E1 - DIGI1            -                   - Vehicle Speed
1E2 - DIGI2            - yellow            - Cam Hall  Sensor
1E3 - 5V1
1E4 - 5V1
1F1 - DIGI3            - black             - Crank Hall sensor
1F2 - DIGI4            -                   - Flex Fuel Pulse                  - Flex Ethanol % + fueltemp
1F3 - DIGI5            -                   - Water Flow Pulse
1F4 - DIGI6            -                   - Turbo speed
1G1 - HS2
1G2 - HS1              - white             - Aux High Side
1G3 - HS3
1G4 - HS4
1H1 - EXTRALSD
1H2 - EXTRALSC
1H3 - EXTRALSB
1H4 - EXTRALSA

2A1 - IGBT8
2A2 - IGBT7
2A3 - IGBT6
2A4 - IGBT5
2B1 - LS2              - brown/green       - Fuel Pump
2B2 - IGN7
2B3 - IGN6             - black/red dab     - Ignition 6
2B4 - STEPA2
2C1 - LS1              - brown             - Main Relay
2C2 - IGN8
2C3 - IGN5             - black/yellow dab  - Ignition 5
2C4 - STEPA1
2D1 - 12VKEY           - red/white         - 12v from engine switch
2D2 - CAN-                                 - CAN
2D3 - CAN+                                 - CAN
2D4 - STEPB1
2E1 - AT3              - black             - IAT
2E2 - AT4              - grey              - Ambient Air Temp
2E3 - GND              - brown             - GND for Map, IAT, CLT, TMAP
2E4 - STEPB2
2F1 - AT1              - brown/red         - CLT
2F2 - AT2              - light grey        - Compressor discharge Temp 
2F3 - CRANK-           -                   - CRANK VR-
2F4 - GND              - brown             - GND for APP, TPS Crank hall, CAM hall 
2G1 - AV10             -  pink             - APP2 
2G2 - AV11             -  		           - WBO analog input
2G3 - CRANK+           -                   - CRANK VR+
2G4 - LSU_IP2
2H1 - AV7              - white/green       - Aux Analog 
2H2 - AV8              - purple            - APP1 
2H3 - AV9              - white/yellow dot  - Aux Analog 
2H4 - LSU_VM2
2J1 - AV4              - yellow            - Fuel Pressure
2J2 - AV5              - Purple/Yellow     - Aux Analog  
2J3 - AV6              - purple            - TPS2
2J4 - LSU_RTRIM2
2K1 - AV1              - yellow            - MAP
2K2 - AV2              - black             - TPS1 
2K3 - AV3              -                   - Oil pressure
2K4 - LSU_UN2
2L1 - 12V_MR_FUSE
2L2 - 12V_MR_FUSE      - Wideband
2L3 - GND              - Main Ground to Battery or Chassis
2L4 - HEATERNEG2
2M1 - ETB1+            - orange            - ETB Motor Pos
2M2 - ETB1-            - grey              - ETB Motor Neg
2M3 - ETB2+
2M4 - ETB2-
  
3A1 - IGBT1             - black/purple dab  - Dumb Coil 1
3A2 - IGBT2             - black/green dab   - Dumb Coil 2
3A3 - IGBT3             - black/white dab   - Dumb Coil 3
3A4 - IGBT4             - black/blue dab    - Dumb Coil 4
3B1 - LS3               - brown/white       - Inj 1
3B2 - IGN2              - black/green dab   - Ignition 2
3B3 - IGN3              - black/white dab   - Ignition 3
3B4 - LSU_UN1           -                   - Wideband
3C1 - LS8               - brown/purple      - Inj 6
3C2 - IGN1              - black/purple dab  - Ignition 1
3C3 - IGN4              - black/blue dab    - Ignition 4
3C4 - LSU_RTRIM1        -                   - Wideband
3D1 - LS6               - brown/blue        - Inj 4
3D2 - LS7               - brown/green       - Inj 5
3D3 - LS4               - brown/red         - Inj 2
3D4 - LSU_VM1           -                   - Wideband
3E1 - LS15              -                   - Check Engine Light
3E2 - LS16              - purple            - Tacho
3E3 - LS5               - brown/yellow      - Inj 3
3E4 - LSU_IP            -                   - Wideband
3F1 - LS13              -                   - ICV Open
3F2 - LS14              -                   - ICV Close
3F3 - GND              - brown             - GND
3F4 - PERMLIVE         -                   - 12v direct from battery
3G1 - 12VMR            - red/white         - 12v in from main relay
3G2 - 12VMR            - red/white         - 12v in from main relay
3G3 - GND              - Main Ground to Battery or Chassis
3G4 - HEATERNEG1       -                   - Wideband
3H1 - LS9ADD           -                   - Aux Output
3H2 - LS10ADD          -                   - Aux Output
3H3 - LS11ADD          -                   - Aux Output
3H4 - LS12ADD          -                   - Aux Output
