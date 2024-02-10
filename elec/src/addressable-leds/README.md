# Addressable LEDs

## Installation
Run in the terminal:

```ato install addressable-leds```

Add to your `.ato` project:

```import WS2812B from "addressable-leds/addressable-leds.ato"```

## Overview

This package currently includes the WS2812B 5050 RGB LED. This is a common addressable LED that can be used for a variety of applications.

![WS2812B](https://assets.lcsc.com/images/lcsc/900x900/20230111_XINGLIGHT-XL-5050RGBC-WS2812B_C2843785_front.jpg)

## Usage

- **Power** These require 5V to operate, which is a little bit annoying. For an example usage with a 3.3V microcontroller, see the [Bike Light project](https://gitlab.atopile.io/atopile/skate-board-brake-light) which uses a [5V boost converter](http://docs.atopile.io/readme_regulators/) to power the LEDs and a [level shifter](http://docs.atopile.io/readme_level-shifter/) to communicate with the microcontroller.
- **Communication** These LEDs communicate using a single wire protocol. This means that you can chain them together and control them all with a single pin on your microcontroller. The [Adafruit Neopixel library](https://github.com/adafruit/Adafruit_NeoPixel) is a good place to start for programming the WS2812B.

## Contributing

Contribute to this package using pull requests. More information can be found in the [contributing guide](https://docs.atopile.io/).

## License

This usb module is provided under the [MIT License](https://opensource.org/license/mit/).

## Contact

For further inquiries or support, please contact me at [narayan@atopile.io](mailto:email@example.com).
