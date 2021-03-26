# YMDK75 config & how to flash
![Current keyboard](https://github.com/PetterRein/Custom-Keyboard-Config/blob/main/YMDK75/photos/5.jpg?raw=true)

## Change the firmware/keymap
 - Follow [QMK Tutorial](https://beta.docs.qmk.fm/tutorial/newbs_getting_started)
 - Clone this repo with possible some keymaps already setup
 - For default firmware use command: `qmk compile -kb ymd75/rev3 -km default`
 - Change to the keymap you want, and flash it

 ## Create new firmware/keymap
- Follow [QMK Tutorial](https://beta.docs.qmk.fm/tutorial/newbs_getting_started)
 - For default firmware use command: `qmk compile -kb ymd75/rev3 -km default`
 - Setup new keymap that is clone of default: `qmk new-keymap`
 - Open the keymap.c in text editor and make your own keymap
 - Compile and flash

## Flashing new firmware & access to reset button
 - Press reset button on the back of the PCB
 - Flash firmware if Atmel DFU connected

 ## Flashing new firmware & not access to reset button
 - Long press Space+B while connecting the PCB to computer
 - Flash firmware if Atmel DFU connected

 ## Good to knows
 ### Swich between 6KRO and NKRO
  - Remove USB from computer, press Space+N while connecting USB to computer again
### Control RGB Underglow
 - Long press Fn+QERTYUIOP
### Reset if some keycodes don't work
 - Remove USB from computer, press Space+Backspace while connecting USB to computer again

## How to assemble the kit
 - Install Stabilizers onto the PCB
 - Inserts some switches into Plate. Corners and the middle
 - Place Plate with switches onto the PCB. Be careful that the switches legs is straight and goes into the sockets
 - Screw the PCB+Plate into the Case