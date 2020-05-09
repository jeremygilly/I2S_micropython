# I2S_micropython

This binary is from https://github.com/miketeachman/micropython/blob/esp32-i2s/ports/esp32/README.md

This was just to speed up the process of how to write to the ESP32. Can be written to the ESP32 with 
```esptool.py --baud 115200 --chip esp32 --port '<USB location>' write_flash 0x1000 <binary location.bin>```
