20190915

This is an EA#5 loader designed to run from scratchpad (after the initial load), so that all of the 32k memory space can be safely loaded to.

Several variants are included:

- XBEA5.DSK - contains a LOAD program that boots into Extended BASIC and looks like the Editor/Assembler RUN PROGRAM FILE option.
- XB-EA5 - the CALL LOAD-able program that does the loading from Extended BASIC
- SCRLOAD - an EA#5 program that automatically loads a pre-configured EA#5 program (which you enter with a hex editor - look for the --->  <--- part and put the filename between the arrows.)
- scratchloaderStandaloneROM_C.bin - an 8k ROM cartridge image that does the same as SCRLOAD, but from a cartridge.
