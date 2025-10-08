                                                                          overveiw:
so this device is a open development device ment for developing small handheld devices.The pcb schematic was based on a hackpad and used some of the fundemental compnets that you
will find here https://hackpad.hackclub.com/guide#pcb_design due to software diffrences the buttons and led lights are diffrent componets but are still compatiball with the device.
The reason i chose to make this device for blueprint was due to my intrest in proggramable handheld devices were your imagonation is the limit to what you can create.
my experiences and struggles while makeing the pcb are docummented in the journell file if your intrested in my experiences while makeing the pcb and later the case and code 
i highly reccomend takeng a look.



                                                                       development notes:
basic program will be provided as a circuit python file this willl be the first aplication made for this device.
the pcb schematics for this device were made in easyeda pictures and a guid will be provided later to help others replicate the device.

the componets include:
XIAO-RP2040-DIP (micro controller) x1
C273350 (toggle switches) x2
C118141 (buttons) x2
C9900023731 (led lights) x2
note: these componet numbers are used in the easyeda liabrary and are provided so you may copy this pcb using easyeda.

more coming soon!!!


                                                                       replication guid:
note: this guid uses easyeda
1) first make your project file and open it your name can be whatever you want its your device.
2) now got to liabrary and copy and paste the names of the componets given above note: my micro controller will look diffrent its because its a custom version of the one your using yours is fine.
3) now place your componets and wire them like in this image. https://mail.google.com/mail/u/1?ui=2&ik=662d01938f&attid=0.3&permmsgid=msg-a:r7996267192600487695&th=199c4ce9bc84a826&view=att&disp=safe&realattid=199c4cd91993d1229723&zw
4) now convert your file to a pcb schematic.
5) now place your componets exactly like you see them here this is necciceray to insure the wireing works with no errors.
https://mail.google.com/mail/u/1?ui=2&ik=662d01938f&attid=0.2&permmsgid=msg-a:r59257577117358851&th=199c4cf9010f83b8&view=att&disp=safe&realattid=199c4cf58f339c4a7362&zw
6) now yours will look diffrent with only a few blue lines there will be a dotted wire button click it and connect everything like we did on the first desighn.
7) now click autoroute and this will make the bluewires red if some stay blue try to adjust your componet positioning and auto route again untll all wires are red.
8) now that the pcb is rooted you can export and download the files you need to get your device printed.
9) after getting the device and puting it together download circute python onto the microcontroller and add your files or copy my code files that are comeing soon!!!
   
