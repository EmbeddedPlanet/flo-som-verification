Variscite i.MX8M-NANO SoM Verification program

----

Current Capability

- Wifi Connection
- GPIO:
  - USR2
  - LED902-G
  - LED902-B
  - LED901-B

Upcoming Capability

- SPI read/write
- ADC input
- GPIO and C API
  - LED901_R
  - LED901_G
  - FLOW_PULSE
  - MOTOR_CLOSE
  - MOTOR_OPEN
  - CTRL_MOTOR
  - RELAY_STATE#
  - PUSHBUTTON
  - USR1

----

Use of the program:

Copy "verify" to the Variscite SoM running the Yocto Dunfell recovery SD card. (ref 1)

Execute "chmod +x verify".

Execute "./verify"


Ref 1: https://variwiki.com/index.php?title=Yocto_Recovery_SD_card&release=RELEASE_DUNFELL_V1.8_VAR-SOM-MX8M-NANO
