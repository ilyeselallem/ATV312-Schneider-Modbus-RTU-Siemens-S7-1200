# ATV312-Schneider-Modbus-RTU-Siemens-S7-1200
Control and monitor a Schneider Electric ATV312 variable frequency drive from a Siemens S7-1200 over a single RS-485 pair, using a CB 1241 (RS485) board and the MB_COMM_LOAD / MB_MASTER instructions in TIA Portal.
The goal is a reusable method, not a one-off. Read the drive's communication manual, map the registers, match the serial settings, and reuse the same PLC pattern. Adapting to another Modbus drive mainly means changing the register map and scaling.
