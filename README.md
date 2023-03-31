# kimχ micro

kimχ micro is a small and spicy open hardware embedded SBC that offers tons of
versitility for many different applications.

![kimchi micro](https://labs.groupgets.com/kimchi-micro/images/kimchi-front.jpg)

# Drone Control Daughterboard Expansion

This is a hardware add-on 'lid' for the kimχ micro that adds drone control hardware
replacing a separate PX4 external embedded subsystem. The kimχ micro with the drone-
control add-on board is an all-in-one embedded drone and rover control system.

![drone control](https://teledatics.com/drone-control/images/drone-control-front.jpg)

![drone control](https://teledatics.com/drone-control/images/drone-control-back.jpg)

## Features

* m.2 connector for NXP IW612 Wi-Fi 6E/Bluetooth & BLE/Zigbee 802.15.4 board
* Gigabit Ethernet port
* ST Micro ISM330 IMU (gyroscope/accelerometer)
* ST Micro IIS2MD magnetometer/compass
* Bosch BMP581 pressure sensor
* Connector for Raspberry Pi HD camera
* GPS & Telemetry connectors for NXP drone & rover kits
* PWM control for up to 8 external motors


## Work In Progress

Stay tuned for updates to both the hardware and software as we add features and port
PX4 Autopilot to the i.MX8M Mini on-board embedded ARM m4 core

Please see out Yocto github to build a Linux OS for the kimχ micro with drone-control 
daughterboard

[Drone Control Yocto](https://github.com/teledatics/drone-control-yocto)

