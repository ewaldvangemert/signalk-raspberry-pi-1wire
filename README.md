# signalk-raspberry-pi-1wire

1-Wire temperature sensors on Raspberry-Pi for Signal-K. This plugin is downloaded from the Signal-K application.

## Getting Started

You will need a Signal-K application and a 1-wire temperature sensor to make use of this plugin.

### Prerequisites

You need basic understanding of installing Node applications with NPM

### Installing SignalK

You can install the application with the command `npm install signak-server`
Get documentation for the application here:
- https://www.npmjs.com/package/signalk-server

### 1-Wire sensor

You can find documentation of connecting and enabeling 1-wire sensors on your Raspberry Pi here:
- [Domoticx Dutch manual](http://domoticx.com/raspberry-pi-temperatuur-sensor-ds18b20-uitlezen/)
- [Connecting 1-wire](https://www.modmypi.com/blog/ds18b20-one-wire-digital-temperature-sensor-and-the-raspberry-pi)

### Enable 1-wire on Raspberry

You will have to enable the 1-wire protocol on the Raspberry-Pi
- [Enable 1-wire](https://www.raspberrypi-spy.co.uk/2018/02/enable-1-wire-interface-raspberry-pi/)

### Building examples

- ![alt BreadBoard Example](https://raw.githubusercontent.com/ewaldvangemert/signalk-raspberry-pi-1wire/master/examples/raspberry-breadboard-1wire.jpg)

You can use a ISDN splitter to house a sensor, and plugin two more sensors. You will need to alter and solder the PCB.

- ![alt ISDN splitter internals](https://raw.githubusercontent.com/ewaldvangemert/signalk-raspberry-pi-1wire/master/examples/raspberry-1wire-from-isdn-splitter.jpg)
- ![alt ISDN splitter](https://raw.githubusercontent.com/ewaldvangemert/signalk-raspberry-pi-1wire/master/examples/raspberry-1wire-from-isdn-splitter2.jpg)

## Contributing

Please read [Readme.md](https://github.com/SignalK/signalk-server-node) for details on Signal-K.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/ewaldvangemert/signalk-raspberry-pi-1wire/tags).

## Authors

* **Ewald van Gemert** - *Author of this plugin*

See also the list of Signalk-server [contributors](https://github.com/SignalK/signalk-server-node/graphs/contributors) who participated in this project.

## License

This project is licensed under the ISC License
