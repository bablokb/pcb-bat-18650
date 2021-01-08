pcb-bat-18650
=============

This is a pcb for 18650 battery with support-circuitry:

  - TP4056 with DW01: breakout for loading and deep-discharge protection
  - TPS61023: a DC-DC converter providing 5.2V (optional)
  - PIC12F1840: an optional microcontroller used for
    - enabling the DC-DC converter ("on")
    - disabling the DC-DC converter ("off")
    - voltage-monitoring
 
 Note this is work in progress!
 
 
 Hardware
 --------
 
 
 
 PCB
 ---
 
 The kicad-source is in the directory `pcb-bat-18650.kicad`. Since the
 size of the battery-holder and the size of the TP4056-breakouts are
 not standardized, you should check that your hardware actually fits.
 
 
 Firmware
 --------
 
 
 Typical setup
 -------------
 
 