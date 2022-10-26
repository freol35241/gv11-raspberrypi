# gv11-raspberrypi
Configuration for the raspberry pi running at GV11. 

## Hardware

* Raspberry Pi 3B (built-in bluetooth support)
* RTL-SDR v3 433 dongle with external antenna (https://www.electrokit.com/produkt/rtl-sdr-receiver-dongle-v3/)

## Setup

* Raspberry Pi OS Lite (Bullseye)
* docker (follow relevant parts of https://dev.to/elalemanyo/how-to-install-docker-and-docker-compose-on-raspberry-pi-1mo)
* docker-compose
  ```
  curl -SL https://github.com/docker/compose/releases/download/{latest_version}/docker-compose-linux-armv7 -o /usr/local/bin/docker-compose
  chmod +x /usr/local/bin/docker-compose
  ```

## Configuration

* docker-compose.yml (requires an accompanying `.env`-file)


