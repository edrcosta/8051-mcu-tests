# Hello world 

for a MCU blink its a hello world

## Uploading with AVR dude 

"avrdude.exe" -C chip.conf -c stk500v1 -P COM5 -p 89s51 -b 19200 -U flash:w:"blinky.hex":a

