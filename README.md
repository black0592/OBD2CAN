OBD2CAN
=======

Provides a bridge between any OBD2 compliant vehicle and the CAN bus interface. Utilizes a STN1110 bridged with an STM32F0 that acts as a host with a CAN bus front-end, emulating a CAN-OBDII interface. OBDII PID requests are received and transparently passed to the STN1110 chip for processing on the appropriate legacy OBDII bus. Replies are forwarded back to the emulated OBD-II CAN interface.

