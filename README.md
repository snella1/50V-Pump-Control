
# Proserv Pump Control – ABB AC500 PLC

## Overview

This repository contains a PLC program written in **Structured Text (ST)** for the **ABB AC500** platform. The program is designed to control the **Proserv 50V service pump**.

##  Table of Contents In README

1. [Repository Contents](#repository-contents)  
2. [Functionality](#functionality)  
   - [Output Signals](#output-signals)  
   - [Input Signals](#input-signals)  
   - [HMI Logic](#hmi-logic)  
3. [System Overview](#system-overview)  
   - [HMI Interface](#hmi-interface)  
   - [Hydrostatic System](#hydrostatic-system)  
   - [Terminal Mapping](#terminal-mapping)  
4. [Requirements](#requirements)  
5. [User Manual](#user-manual)  
  


## Repository Contents

- **Structured Text code in `.txt` format**  
  The program files are provided in plain text format to ensure readability for users who do not have a license for Automation Builder.

- **AC500 upload files**  
  Includes all necessary files required to upload the program to an AC500 PLC.

- **System illustrations**  
  Diagrams and images are included to describe the system architecture and provide context for the code design.

- **User manual**  
  A comprehensive guide aimed at end users, covering:
  - Safe operation and HSE considerations  
  - Troubleshooting procedures  
  - General usage instructions  

### Functionality
- Output Signals
  - `AR2`: On/off — pressurizing  
  - `AR3`: 0–100 % — pressurizing speed  
  - `AR4`: On/off — bleed-off  
  - `AB1`: 0–100 % — bleed-off speed  
  - `AirTrip`: On/off — pressurizing  
- Input Signals (Reading and Scaling)
  - `AI_AR2`: 0–20 bar — input pressure  
  - `AI_PT`: 0–1000 bar — output pressure 

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

