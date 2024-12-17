# RaspberryPi_DHT_OLED
Raspberry Pi + DHT Sensor and OLED in python code
#### Web Blog http://raspberrypi4u.blogspot.com/2017/02/raspberry-pi-dht-sensor-oled.html
#### Developer http://softpowergroup.net/ amphancm@gmail.com
![GitHub Logo](/RPI3_DHT11-OLED_bb.png)

# Note Setting up multiple I2C buses using dtoverlay
file: `/boot/config.txt` add:
```bash
dtoverlay=i2c-gpio,bus=3,i2c_gpio_delay_us=1,i2c_gpio_sda=17,i2c_gpio_scl=27
```
https://medium.com/@mileperuma/enable-multiple-i2c-ports-on-raspberry-pi-5a8807471737