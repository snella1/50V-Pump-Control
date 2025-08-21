# Proserv Pump Control – ABB AC500 PLC

## Overview
This repository contains a PLC program written in **Structured Text (ST)** for the ABB AC500, designed to control the Proserv "50V" service pump.


The program includes:
- control of control of output (AR2, AR3, AR4, AB1, Air Trip)
- Read and translation of input:  AI_AR2 (0–20 bar) and AI_PT (0–1000 bar)
- Basic HMI logic for manual operation and feedback

## Requirements
- ABB Automation Builder (tested with version 2.7 or newer)
- ABB AC500 PLC
- Control cabinet with HMI (e.g. CP604)
- Alternatively: ABB AC500-eCo V3 Starter Kit
- ABB Automation Builder LICENSE

## System Overview: HMI Interface and system Mapping
-HMI
![HMIm](images/HMI%20Interface.png)
– Hydrostatic System
![Hydrostatic System](images/Hydraulic-Mechanical%20Overview.png)
– Terminal Mapping
![Terminal Mapping](images/Input%20channels%20and%20terminal%20numbers.png)


# Proserv Pump Control – ABB AC500 PLC

## Overview
This repository contains a PLC program written in **Structured Text (ST)** for the ABB AC500 platform. The program is designed to control the Proserv "50V" service pump.

### Functionality
- `AR2`: On/off, Pressurizing  
- `AR3`: On/off,Pressurizing speed  
- `AR4`: On/off, Bleed-off  
- `AB1`: 0–100 %, Bleed-off speed  
- `AirTrip`: On/off, pressurizing  
- Input reading and scaling:
  - `AI_AR2`: 0–20 bar, input pressure
  - `AI_PT`: 0–1000 bar, output pressure

- Basic HMI logic for manual operation and operator feedback

## Requirements
- ABB Automation Builder (v2.7 or newer)
- ABB AC500 PLC or AC500-eCo V3 Starter Kit
- HMI panel (e.g. CP604)
- Valid Automation Builder license

## System Overview
### HMI Interface
![HMIm](images/HMI%20Interface.png)

### Hydrostatic System
![Hydrostatic System](images/Hydraulic-Mechanical%20Overview.png)

### Terminal Mapping
![Terminal Mapping](images/Input%20channels%20and%20terminal%20numbers.png)

