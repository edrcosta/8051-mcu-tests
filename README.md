# 8051 Learning

This repository contains study code for 8051 Microcontroller im currently using AT89S51 

http://ww1.microchip.com/downloads/en/devicedoc/doc2487.pdf

# Uploading code to 8051

Im using an arduino uno as SPI programmer 

https://www.instructables.com/How-to-Program-8051-Using-Arduino/


## Uploading with AVR dude 

"avrdude.exe" -C chip.conf -c stk500v1 -P COM5 -p 89s51 -b 19200 -U flash:w:"blinky.hex":a

