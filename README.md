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
    Source: https://learn.adafruit.com/adding-basic-audio-ouput-to-raspberry-pi-zero/pi-zero-pwm-audio
      
## Power/Battery
    Tested current draw of Pi Zero

        5.00V 170-180mA (67mA idle)
        4.00V 200-210mA (79mA idle)
        3.00V 260-270mA (94mA idle)
        2.80V 270-280mA
        2.70V 280-290mA occasional reboots
        2.60V will not run

    No failed tests at any voltage
    Source: https://www.raspberrypi.org/forums/viewtopic.php?t=144267


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
    
## Resources
[GPIO Functions](https://elinux.org/RPi_BCM2835_GPIOs)
[Game Boy Zero Wiki Guide](https://www.sudomod.com/wiki/index.php/Game_Boy_Zero)

