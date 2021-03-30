# YMDK75 config & how to flash
![Current keyboard](https://github.com/PetterRein/Custom-Keyboard-Config/blob/main/YMDK75/photos/5.jpg?raw=true)

## Change the keymap
 - Follow [QMK Tutorial](https://beta.docs.qmk.fm/tutorial/newbs_getting_started)
 - Clone this repo
 - Change keymap.c
 - Compile it
 - Flash it

## Create new keymap
 - Follow [QMK Tutorial](https://beta.docs.qmk.fm/tutorial/newbs_getting_started)
 - For default keymap use command: `qmk compile -kb ymd75/rev3 -km default`
 - Setup new keymap that is clone of default: `qmk new-keymap`
 - Open the keymap.c in text editor and make your own keymap
 - Compile and flash

## Flashing new keymap & access to reset button
 - Press reset button on the back of the PCB
 - Use QMK Toolbox
 - Check if it says Atmel DFU connected in output/terminal
 - Flash keymap

## Flashing new keymap & not access to reset button?
 - Long press Space+B while connecting the PCB to computer
 - Flash keymap if Atmel DFU connected

## Good to knows
### Swich between 6KRO and NKRO
 - Enable NKRO first in rules file for keyboard in qmk files
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