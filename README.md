

DeWinCNC brings the benefits of the RAMPS eco-system to machines which originated with WinCNC.



Compared with WinCNC:
WinCNC software uses a proprietory daughter card on a full-size PCI I/O card which needs a Windows desktop PC.

This shield + an Arduino MEGA 2560 + Marlin firmware enables you to use a laptop of any OS you like, 
with a choice of controller/loader apps.  Or no computer at all - just load files from an SD-card!

You can use entirely open source software with no license or on-going maintenance costs.
Or you can chose somehting like LightBurn which has a great camera feature at a great price.

In common with WinCNC:
Includes the same DB37 plug for direct connection to your existing machne's breakout board.



Compared with RAMPS:
Uses common industrial off-board stepper driver modules so you can scale to any power your mechine needs.

Has a 1-Wire interface so you can use as many digital temperature sensors as you like.

Has 4 on-board isolated SolidState Relays for switching machine power, GasAssist, VacuumPump etc.

Can take power entirely from the USB host, or from a common industrial 24Vdc supply.

Limit switch inputs have convenient screw-terminal connectors.

In common with RAMPS:
Limit switch headers, I2C & reset botton.
Keeps the Aux-1,2,3,4 ports for Servos, SD-card, LCD contoler etc. within the same footprint.



Additionaal functionality:
Could be plugged into the WinCNC controller to replace the CNC machine's breakout board.
Could be used with the WinCNC controller to monitor/simulate most signals.
Can be usaed as a general purpose breakout shield with 4 SSRs & 23 I/O lines (inc 10 analog).

ToDo:
Most PCB manufacturers will want a bigger gap between main & break-off boards.  And perforation holes.
