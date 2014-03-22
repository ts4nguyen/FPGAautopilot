This is part of my works before which is a FPGA based-quadrocopter.
.I haven't finish it. I would like to put it in open source for developing
Sumary of works I have done so far. 
- 1 PCB for motor control + 1 PCB for FPGA and sensors : all devices tested and work well
- All drivers for sensors (I2C , SPI, UART , paralel bus ) wrote and tested
- Simple version of PID on FPGA implemented but can not make the rocopter fly 
- A simple version of ground station UI on Microsoft Visual Studio 
Software required :
- Altium (or any pcb design software) 
- Xilinx IDE 
- Matlab + SYstem generator : PID designed in matlab and then integrated in Xilinx IDE through System Generator 

Details on system design and hardware design will be updated soon

