Two very similar FPGA boards exist, boards A and B. The schematic is mostly the same, with the difference that on board A MPS DCDC type MPM3834C are used. Board B uses pin compatible DCDC FS3303 from TDK.

The problem appears with simple Hello World demo with RISC-V based system. Board A works well, on board B once out of five attempts one character goes missing on the UART output.

What is the problem with board B?
