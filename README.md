# Home Assistant Operating-System
Home Assistant OS based on [buildroot](https://buildroot.org/). It's a hypervisor for Docker and supports various kind of IoT hardware. It is also available as virtual appliance. The whole system is optimized for embedded system and  security. You can update the system simple with OTA updates or offline updates.

## Focus

- U-Boot as bootloader
- Linux/Buildroot LTS
- RAUC for OTA updates
- SquashFS LZ4 as filesystem
- Docker-CE
- AppArmor protected
- ZRAM LZ4 for /tmp, /var, swap
