# sigrok_mpu6050_decoder

![](https://raw.githubusercontent.com/adrianalin/sigrok_mpu6050_decoder/master/MPU6050.jpg)


This is work in progress, it decodes I2C messages with datasheet register information for MPU6050 accelerometer, so it's stacked on I2C protocol. Still need to figure out how to use annotations and annotation rows, and correctly decode accel, gyro, and temp values.
For a quick test install `puseview`, `libsigrok`, and `sudo cp -r mpu6050/ /usr/share/libsigrokdecode/decoders/`.

![screenshot](https://raw.githubusercontent.com/adrianalin/sigrok_mpu6050_decoder/master/screenshot.png)
