# ROBOTS101_2023


Goal:
To create a easy funtional Pi hat for the ROBOTS101 program.

This pi hat will:
- Label all pins & connections clearly.
- Have breakout headers to reduce confusion and reduce dangerous connections
- Regulate battery voltage & power the Pi safely 
- Provide a direct and clear power switch
- (Optional) Expand GPIO for future projects 
- Clean and streamline robot construction.
- Have an easy design for future PCB workshop to work on


ROBOTS101 WIKI LINK: https://goofy-slicer-49c.notion.site/ROBOTS101-Wiki-223888f84ce34d78a62f8b15874e6fb9


## Key Features
1. Battery Connector
    - XT30 PCB Mount
2. Power Regulation 
    - 5.1V Regulation
        - Limit to 2.5A
        - Needs filtering capacitors
        - Regulators can be bought from store
    - 3.3V Regulation? (unsure if necessary)
3. Reverse Polarity 
    - P-MOSFET
4. User Feedback
    - Buttons
    - LEDS
5. Expansion 
    - I2C address lanes - breakout into multiple connectors
6. Breakouts
    - Motor control board
    - Single Gripper Servo or two??
    - Ultrasonic Sensor
    - Adafruit Mini PiTFT support
