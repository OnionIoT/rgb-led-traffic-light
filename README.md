# rgb-led-traffic-light
Web app that turns the Expansion Dock's RGB LED into a mini traffic light 

## Requirements

* Omega2/Omega2+
* Expansion Dock

## Installation

Connect to your Omega's command line. Then run:

```
cd /root
git clone https://github.com/OnionIoT/rgb-led-traffic-light.git
cp -r rgb-led-traffic-light/www /www/traffic
```

## Usage

1. Connect your Omega to your local WiFi network
1. On your computer, go to http://omega-XXXX.local/traffic
    * See https://docs.onion.io/omega2-docs/omega-name.html for how to replace `XXXX` in the URL above
1. Click on each of the colors to change the RGB LED on the Expansion Dock!