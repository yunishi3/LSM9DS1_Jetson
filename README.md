# SparkFun LSM9DS1 Library for Jetson
===

Porting [SparkFun_LSM9DS1_Arduino_Library](https://github.com/sparkfun/SparkFun_LSM9DS1_Arduino_Library) to Jetson Nano.  

This repository is modified from [Raspberry Pi Version](https://github.com/akimach/LSM9DS1_RaspberryPi_Library) to Jetson Nano.  

<p align="center"><img src="https://user-images.githubusercontent.com/17570265/29253393-a11ac3a6-80b6-11e7-846f-0d387fa2fbe4.jpeg" alt="LSM9DS1" width="200"/></p>

[LSM9DS1 Breakout Board (SEN-13284)](https://www.sparkfun.com/products/13284)

This library supports only I2C.  

## Requirement
[Set up GPIO for Jetson](https://github.com/NVIDIA/jetson-gpio)  
You can check i2c detection using following command via Terminal.  

```
$ i2cdetect -y -r 1
```


## Install
  
```
$ git clone https://github.com/yunishi3/LSM9DS1_Jetson.git
$ cd LSM9DS1_Jetson
$ make
$ sudo make install
```

## Example
### C++
```
$ cd LSM9DS1_Jetson/example
$ make
$ ./LSM9DS1_Basic_I2C
```


### Python version

```
$ cd LSM9DS1_Jetson/example
$ sudo python LSM9DS1_Basic_I2C.py
```
