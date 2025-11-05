Cerberus: Field Radio Monitoring & Microcontroller System

Objective: Portable field microcontroller and radio monitoring system for short-range device control and long-range satellite telemetry reception.

Cerberus is a rugged, field-deployable system designed for real-time two-way radio control of remote devices and reception of NOAA and other weather satellite imagery. The system integrates a Raspberry Pi microcontroller hub, Arduino-controlled short-range radios, and a touchscreen interface for monitoring and control.

Features

Short-Range Radio Communication:
Two-way wireless control of field devices up to ~0.5 miles using NRF24l01 modules and Arduino Nano controllers.

Long-Range Satellite Reception:
Capture, decode, and store NOAA and other weather satellite telemetry and images for field analysis, using a RTL-SRD dongle and a L-N-A.

Field Microcontroller Hub:
Raspberry Pi 3B central controller integrates radios, sensors, and touchscreen interface.

Portable & Rugged:
All components are housed in a Pelican 1300 case with a Noctua NF-A4x10 5V fan for reliable cooling and outdoor operation.

Software Updates:
The Cerberus software stack is actively maintained, and the repository will receive periodic updates to improve telemetry decoding, device control, and user interface functionality.

Repository Structure
Cerberus_STL_Log/
│
├─ Prototyping/
│  ├─ STL_Prototypes/      # Early 3D printable prototypes
│  └─ S-W_Prototypes/      # SolidWorks prototype files
│
├─ Project_STL/             # Primary STL files for project assembly
│
└─ Final_Parts/             # Finalized STL and SolidWorks parts ready for assembly
