# Kostume Kult Lighting
Files &amp; documentation for Kostume Kult lighting projects

## Marquee Top

This is the documentation, details and files as of August 2024

See the `2024/marquee-topper` folder for all files.

### WELD Controller

- Wifi SSID: KK-MarqueeTop
- Password: ********
- Page: https://4.3.2.1
- On local network as: kk-marqueetop.local

Full [instruction manual](https://quinled.info/2020/02/11/pre-assembled-quinled-dig-uno-wled-manual/).

### LED Outputs

- **LED 1**
  - GPIO 16
  - Start: 0
  - Length: 244
  - Middle building
- **LED 2**
  - GPIO 03
  - Start: 244
  - Length: 127
  - Left side
- **LED 3**
  - GPIO 04
  - Start: 371
  - Length: 124
  - Right side
 
- [ X ] Make segment for each output

### Maps

- **ledmap**
  - Same as ledmap1
- **ledmap1**
  - Whole strip as a 2d matrix
  - `-1' placed in 2d gaps
- **ledmap2**
  - Whole strip, as a 1d row
  - Used for chases and full-display fun
  - No gaps


### Power

Wiring the AC plug to the power supply:

- **Green:** Earth / ground
- **White:** Neutral / N
- **Black:** Live / L

Controller [wiring guide](https://quinled.info/2020/10/03/quinled-dig-quad-wiring-guide/). Note that no voltage jumpers are needed for our pre-assembled version.




