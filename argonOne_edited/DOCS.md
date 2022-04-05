# Configuration

## I2C bus configuration

Set I2C bus to be used.

- **i2cDevice** - Configures which I2C bus should be scanned for Argon One (available options: 1, 2 or 3). 

![image](https://user-images.githubusercontent.com/62244838/161707733-20389fc7-d9f7-46f4-ac33-46234923e069.png)

## Celsius or Fahrenheit

Choose Celsius or Fahrenheit.

- **CorF** - Configures Celsius or Fahrenheit.

## Temperature Ranges

![image](https://raw.githubusercontent.com/adamoutler/HassOSArgonOneAddon/main/gitResources/FanRangeExplaination.png)

Set your fan ranges appropriately.

- **LowRange** Minimum Temperature to turn on 33%. Anything lower will turn off.
- **MediumRange** to be the temperature divider between 33 and 66%.
- **HighRange** to be the maximum temperature before 100% fan.

## Enable I2C

In order to enable i2C, you must follow one of the methods below.

### The easy way

[Addon](https://community.home-assistant.io/t/add-on-hassos-i2c-configurator/264167)

### The official way

[Official Guide](https://www.home-assistant.io/hassio/enable_i2c/)

## Support

No :(

## Based on
Click [here](https://community.home-assistant.io/t/argon-one-active-cooling-addon/262598/8).
