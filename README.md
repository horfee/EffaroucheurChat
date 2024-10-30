
# Effaroucheur à Chat

This project is a design of a board, based on ESP32, to control ultra sound speaker according to infrared motion sensors.

It is powered by 2 solar panels, with a LDO MP2161GJ-Z to power efficiently the device.

Used components are :
- MP2161GJ-Z
- ESP32 WROOM
- TP4056 as battery charger
- HC-SR501 for motion sensors
- << insert speaker ref here >>
- FT232RL to discuss with ESP32 for flash phase
- UMH3N to enabled RTS/DTR mechanism

Flash firmware will come later.

Current design is this :
![The actual board](https://github.com/horfee/EffaroucheurChat/blob/main/EffaroucheurChat.png?raw=true)
