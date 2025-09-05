A generic Satellite Telemetry Decoding GNURadio Flowgraph for Small satellites using ADF7030-1 Radio Transceivers.
This flowgraph will demodulate the GFSK modulated RF signal, verifes the CRC bytes encapsulated by the ADF7030-1 Transceiver. 
It can also check for the length byte within a variable length user packet and then use it to verify the CRC byte included within the same packet. 
