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
    Button tracers > GPIO Pins

