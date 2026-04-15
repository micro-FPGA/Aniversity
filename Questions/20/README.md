Look at the picture in this folder. It is a LOW CAPACITANCE diode between PROG_BD and INIT nets going to FPGA.

PROG_BD pulsing low initiates FPGA configuration process.

INIT_B is kept low by FPGA when it is not configured and not ready.

PULLING INIT_B low keeps FPGA idle delaying configuration process.

Now to the question and problem, with the DIODE between INIT and PROG_BD the FPGA multiboot is not working.

How to fix the problem without removing the DIODE?

Identor #9 suggested one solution that would also work, what we actually did test was another solution.

So the question is WHAT did we add the schematic to make multiboot working again?
