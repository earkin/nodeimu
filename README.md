nodeimu
=========

[![Linux Build][travis-linux-image]][travis-linux-url]


Nodejs bindings for accessing IMU/pressure/humidity/temperature data using [RTIMULib2](https://github.com/richards-tech/RTIMULib2.git). The addon uses [nodejs/nan](https://github.com/nodejs/nan.git). It has been tested on [Sense HAT](https://www.raspberrypi.org/products/sense-hat/) for Raspberry Pi.

## Install

```
git clone https://github.com/rupnikj/nodeimu --recursive && cd nodeimu
npm install node-gyp -g
npm install
```

## Test

```
node test.js
node testSync.js
```


[travis-linux-image]: https://img.shields.io/travis/rupnikj/nodeimu/master.svg?label=linux
[travis-linux-url]: https://travis-ci.org/rupnikj/nodeimu
