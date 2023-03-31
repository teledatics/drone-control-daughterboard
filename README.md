# Drone Control

This is a hardware add-on 'lid' for the kimχ micro that adds drone control hardware
replacing a separate PX4 external embedded subsystem. The kimχ micro with the drone-
control add-on board is an all-in-one embedded drone and rover control system.

The kimχ micro with the drone-control add-on is an [i.MX8M Mini](https://www.nxp.com/products/processors-and-microcontrollers/arm-processors/i-mx-applications-processors/i-mx-8-applications-processors/i-mx-8m-mini-arm-cortex-a53-cortex-m4-audio-voice-video:i.MX8MMINI) Linux system with a 
32mm x 65mm x 10mm form factor.

![drone control](https://teledatics.com/drone-control/images/drone-control-front.jpg)

![drone control](https://teledatics.com/drone-control/images/drone-control-back.jpg)

## kimχ micro

kimχ micro is a small and spicy open hardware embedded SBC that offers tons of
versitility for many different applications.

[kimχ micro](https://github.com/groupgets/kimchi-micro)

![kimchi micro](https://labs.groupgets.com/kimchi-micro/images/kimchi-front.jpg)

## Features

* m.2 connector for [NXP IW612](https://www.nxp.com/products/wireless/wi-fi-plus-bluetooth-plus-802-15-4/2-4-5-ghz-dual-band-1x1-wi-fi-6-802-11ax-plus-bluetooth-5-2-plus-802-15-4-tri-radio-solution:IW612) Wi-Fi 6E/Bluetooth & BLE/Zigbee 802.15.4 board
* Gigabit Ethernet port
* ST Micro [ISM330DHCX](https://www.st.com/en/mems-and-sensors/ism330dhcx.html) IMU gyroscope/accelerometer
* ST Micro [IIS2MDC](https://www.st.com/en/mems-and-sensors/iis2mdc.html) magnetometer/compass
* Bosch [BMP581](https://www.bosch-sensortec.com/products/environmental-sensors/pressure-sensors/bmp581/) pressure sensor for altitude
* 15-pin Connector for Raspberry Pi v1.3 HD camera
* GPS & Telemetry connectors for NXP drone & rover kits
* PWM control for up to 8 external motors w/ NXP rover & drone kit compatible connector


## Work In Progress

Stay tuned for updates to both the hardware and software as we add features and port
PX4 Autopilot to the i.MX8M Mini on-board embedded ARM m4 core

Please see our Drone Control Yocto github repository to build a Linux OS for the kimχ 
micro with drone-control daughterboard

[Drone Control Yocto](https://github.com/teledatics/drone-control-yocto)
