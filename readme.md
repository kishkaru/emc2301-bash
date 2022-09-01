# Setup

1. Enable IC2 control: sudo raspi-config -> Interface options -> I2C enable
2. Install required packages: `sudo apt install i2c-tools bc -y`
3. `./daemon.sh`

Measure CPU temp via:
```
vcgencmd measure_temp
```
