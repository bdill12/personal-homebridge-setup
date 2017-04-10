# personal-homebridge-setup
The current state of my ongoing attempt to automate using Homebridge. This is a personal configuration. You are welcome to use it to help you setup your own, but I will not guarantee anything will work.

## Limitations
Homekit, as I understand it, only allows you to set up a few types of devices. I have only experimented with switches and sensors. Basically, Homebridge is useful for powering things on and off or for setting a property to a specific value.

## Home
The config.json file in /Home is the configuration that I currently have running on my home server.

### Running 
The following packages have been successfully added to the Home configuration:
- [Harmony Hub](https://www.npmjs.com/package/homebridge-harmonyhub)
- [Wemo Platform](https://www.npmjs.com/package/homebridge-platform-wemo)

## Tests
Anything found in /Tests is not ready to be added to the system, yet.

### Testing
Currently testing configs with:
- [Nest](https://www.npmjs.com/package/homebridge-nest)
- [Yamaha](https://www.npmjs.com/package/homebridge-yamaha)
- 

### Past Attempts
Plugins I have experimented with, but decided to put aside for the listed reason:
- [Samsungtv-control](https://www.npmjs.com/package/homebridge-samsungtv-control) : TV disconnects from network on power off, meaning you can't turn the TV on. Only off.
- [Applescript](https://www.npmjs.com/package/homebridge-applescript) : It works, but I just don't have a reason to use it at the moment.
