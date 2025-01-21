# ICY40 - Lattice ICE40UP5K FPGA learning board

<p float="left">
  <img src="/Doc/ICY40_board_fully_assembled.jpg" width="1000" />
</p>

The ICY40 board is equally suited for the absolute beginner and the ambitious digital logic enthusiast. It covers complexities in the range from
simple combinational pushbutton-to-LED circuits to a full blown SoC (system on chip) with for example the EC16 soft processor core.

The board is deliberately designed as a self-contained teaching tool, with its ample buttons, switches, LEDs, a tricolor LED,
a 7-segment and an OLED graphic display. And its sensitive components are additionally protected by a case since the target audience 
is not (only) the soldering iron wielding hardware wizzard in his ESD-proof workplace but everyone with a computer and a desktop.

There are only two external electrical interfaces: 
- a USB port that provides power, the programming interface and a communication channel (COM-Port)
- an 8-bit PMOD connector if hardware extensions are desired
<p float="right">
  <img src="/Doc/ICY40_in_housing.jpg" width="800" />
</p>

The EC16 soft processor core is free and open source just as the assembler EC16ASM.PY and the simple monitor program EC16MON.
Assembler programs can be written with a text editor like Notepad++ and uploaded with a terminal program like Tera Term.

The processor currently runs at 20MHz, uses only about 20% of the logic ressources and comes with 512 words boot ram and 16K program/data memory.
Included are a Fixed Asynchronous Receiver Transmitter (115.200 Baud 8N1), an I2C master (100/400/1000 KHz) for the OLED and access to all
display and control elements. Of course everything is changeable in the VHDL source files.
 
<p float="left">
  <img src="/Doc/ICY40_EC16_writes_text_on_display.jpg" width="800" /> 
</p>
