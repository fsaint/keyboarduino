# keyboarduino
Using an Arduino as a Keyboard. 

Install DFU Programmer
	sudo port install dfu-programmer


Changing the Arduino to Keyboard Mode
	sudo dfu-programmer atmega16u2 erase
	sudo dfu-programmer atmega16u2 flash --debug 1 Arduino-keyboard-0.3.hex

Switching back to programmng Mode
	sudo dfu-programmer atmega16u2 erase
	sudo dfu-programmer atmega16u2 flash --debug 1 Arduino-usbserial-uno.hex

