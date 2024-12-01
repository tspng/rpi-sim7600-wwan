# SIM7600G-H / SIM7600X NDIS Driver

Linux kernel driver for Waveshare SIM7600G-H / SIM7600X 4G HAT modules on Raspberry Pi.

## Overview

This driver enables NDIS networking support for SIM7600 series cellular modems 
on Raspberry Pi running Raspbian Debian GNU/Linux 12 (bookworm). 
It is adapted from the original Waveshare driver to work with current Linux kernels.

Original kernel module code: https://files.waveshare.com/upload/0/00/SIM7600_NDIS.7z
Based on the Waveshare documentation from:
https://www.waveshare.com/wiki/Raspberry_Pi_networked_via_NDIS

## Hardware Support

- SIM7600G-H 4G HAT
- SIM7600X 4G HAT

## Requirements

- Raspberry Pi (any model)
- Raspbian Debian GNU/Linux 12 (bookworm)
- SIM7600X/G-H

## Installation

1. Clone this repository
2. Build and install the driver:

```sh
make
sudo make install
```
