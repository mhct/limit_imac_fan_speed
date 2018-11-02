# Limit iMac Fan Speed

This project is useful for people how changed their iMac HDD for an SSD, and did 
not add a new temperature sensor to the computer. The iMac will not have a temperature for the HDD and simply set the fans to maximum speed.

This project sets the maximum speed of the HDD Fan of an iMac to 1200 rpm. The goal is to limit the Fan speed and avoid too much noise coming from the computer.



----
## Installation

Clone this repository at */opt/*

    git clone https://github.com/mhct/limit_imac_fan_speed.git /opt

Copy the file **set_max_hdd_fan_speed.xml** to the folder */Library/LaunchDaemons*.

    sudo cp set_max_hdd_fan_speed.xml /Library/LaunchDaemons

## Disclaimer

This project relies on the code provided by https://github.com/hholtmann/smcFanControl

