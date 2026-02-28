# SolaxvT58 battery in NodeRED
NodeRED flow to read Solax T58 Battery details directly from battery module via RS485 serial converter and wirelessly over ESPHome serial stream proxy

Connect RJ45 pin 3 and 6 to last slave T58 battery. Pin 3 -> modbus B-, Pin 6 -> modbus A+. Recommended use of modules with disabled sending data. 

For wireless connection use ESP module with some kind of serial proxy, i.e. ESPHome and ESP32

You can read temperatures, SoC, voltage, current, cycle count of each module
