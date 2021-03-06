# GBAZero
Gamebody advanced zero projet

## Display
#### Components:
    1. Screen
      - BW 3.5 Inch TFT LCD Monitor 
#### Circuit:
    PP1 5V, PP6 GND, PP4 and PPg Composite Output

## Audio
#### Components:
    1. Filter Circuit
      - Low-Pass Filter
        - 270 Ohm Resistor, 33nF Capacitor
        
      - High-Pass Filter
        - 150 Ohm Resistor, 10uF Capacitor
        
    2. Amplifier
      - PAM8403 Class D Amplifier, 2 100 Ohm Resistor
      
    3. Speaker (Original)
    
    4. Headphone Jack (Original)
    
#### Circuit:
    Filter > Amplifier > Headphone Jack > Speaker
      
## Power/Battery
    Tested current draw of Pi Zero

        5.00V 170-180mA (67mA idle)
        4.00V 200-210mA (79mA idle)
        3.00V 260-270mA (94mA idle)
        2.80V 270-280mA
        2.70V 280-290mA occasional reboots
        2.60V will not run

    No failed tests at any voltage

#### Components: 
    1. Battery
      - 2000 mAH LiPo
      
    2. Charging Board
      - TP4056
      
    3. Boost Converter
      - MT3608
      
    4. Switch
#### Circuit:
    Battery (3.7V) > Charging Board > Booster Converter (3.7 - 5V) > Power Strip > Screen, Pi, Amplifier       

## Controls
#### Circuit:
    Button traces > GPIO Pins
    
## Parts
[BW 3.5 Inch TFT LCD Monitor](https://www.amazon.com/BW-3-5-Inch-Monitor-Automobile/dp/B0045IIZKU/ref=sr_1_1?ie=UTF8&qid=1546575336&sr=8-1&keywords=BW+3.5+Inch+TFT)

## Resources
[GPIO Functions](https://elinux.org/RPi_BCM2835_GPIOs)

[Game Boy Zero Wiki Guide](https://www.sudomod.com/wiki/index.php/Game_Boy_Zero)

[Pi Zero PWM Audio Schematic](https://learn.adafruit.com/adding-basic-audio-ouput-to-raspberry-pi-zero)

[Pi Zero PWM Audio](https://learn.adafruit.com/adding-basic-audio-ouput-to-raspberry-pi-zero/pi-zero-pwm-audio)

[Pi Zero at Low Voltages](https://www.raspberrypi.org/forums/viewtopic.php?t=144267)

