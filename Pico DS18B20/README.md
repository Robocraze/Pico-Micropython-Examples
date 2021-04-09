# DS18B20 One wire temperature sensor on the RPi Pico

After installing the micropython UF2 on the Pico and setting it up in the Thonny IDE, visit the two links given below and copy the code from both. Save them on your pico under the "lib" folder. If this folder does not already exist, you can create it and save the files using the exact names given below.

Ensure you connect the VCC pin to 3v3 and not 5v, GND to GND and the output pin directly to GP15 on the pico (or change the pin in code accordingly).

`onewire.py:` https://raw.githubusercontent.com/micropython/micropython/master/drivers/onewire/onewire.py

`ds18x20.py:` https://raw.githubusercontent.com/micropython/micropython/master/drivers/onewire/ds18x20.py

Then copy the code from the `ds18b20_example.py` file and run it. 