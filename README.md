# 32, 64, 128 and 256-bit SYMPL IEEE 754-2019 Instruction Set Architecture Compute Engine.

(June 28, 2021) Update:  the debugger now has source-level disassembly.  The animated .gif below shows an actual debug session starting from power-up message, then proceeding to Help menu, uploading a binary executable, uploading object listing file, setting harware breakpoint, running, hitting breakpoint, single-stepping, displaying data dump, editing a data memory location, single-stepping, then free-run with auto snap-shot occuring every 2 seconds.  While running in real-time, you can examine and edit any memory location on-the-fly, without having to force a breakpoint first, all without the need for any s/w routines on the target side, as it's all done in hardware.

[![RTMDXgif](https://github.com/jerry-D/SYMPL_IEEE754-2019_ISA/blob/main/SYMPL_RTMDX.gif)](https://github.com/jerry-D/SYMPL_IEEE754-2019_ISA/blob/main/SYMPL_RTMDX.gif)

(June 18, 2021) Update:  the debugger is up and running in the ULX3S FPGA.  Still need a couple weeks to do documentation and add the disassembler. Sorry for the delay.

(April 22, 2021)  A RADIONA ULX3S FPGA project board has been purchased and efforts are underway to create 32, 64, 128 and 256-bit versions of the SYMPL IEEE 754-2019 ISA Compute Engine that implements in hardware all computational and non-computational binary32 floating-point operations mandated by the IEEE 754-2019 standard.  

For a preview of what's to come, click on the thumb of a 17" x 24" poster-size preliminary information sheet below and then the "download" button once it appears.  This repository will be continually updated with FPGA flash file that you can use to flash your ULX3S FPGA with for evaluation purposes.  To obtain your RADIONA ULX3S board, visit CrowdSupply or MOUSER Electronics.  Be sure to order the model with the -85F FPGA.  

Be advised that it will probably be another 3-4 weeks before alpha is made available here.

[![poster](https://github.com/jerry-D/SYMPL_IEEE754-2019_ISA/blob/main/SYMPL_IEEE_754_poster_v1_3_thumb.png)](https://github.com/jerry-D/SYMPL_IEEE754-2019_ISA/blob/main/SYMPL_IEEE_754_poster_v1_3.png)


