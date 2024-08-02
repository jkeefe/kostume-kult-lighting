# Kostume Kult Lighting
Files &amp; documentation for Kostume Kult lighting projects

## Marquee Top

This is the documentation, details and files as of August 2024

### WELD Controller

- Wifi SSID: KK-MarqueeTop
- Password: ********
- Page: https://4.3.2.1
- On local network as: kk-marqueetop.local

Full [instruction manual](https://quinled.info/2020/02/11/pre-assembled-quinled-dig-uno-wled-manual/).

### Segments

See the `2024/marquee-topper` folder for the files.

- **Segment 1:** The middle building
  - GPIO 16
  - LED 1 on the controller
  - **ledmap.json** The middle building map, as a grid
  - **ledmap1.json** Also the middle building map, as a grid (duplicate)
  - **ledmap7.json** The middle building map, as a strip. Includes all turns and bends.
- **Segment 2:** The left side burst
  - GPIO 03
  - LED 2 on the controller
  - **ledmap2.json** Left burst, as a grid 
  - **ledmap8.json** Left burst, as a strip. Includes all turns and bends.
- **Segment 3:** The right side burst
  - GPIO 04
  - LED 3 on the controller
  - **ledmap3.json** Right burst, as a grid 
  - **ledmap9.json** Right burst, as a strip. Includes all turns and bends.

### Power

Wiring the AC plug to the power supply:

- **Green:** Earth / ground
- **White:** Neutral / N
- **Black:** Live / L

Controller [wiring guide](https://quinled.info/2020/10/03/quinled-dig-quad-wiring-guide/). Note that no voltage jumpers are needed for our pre-assembled version.




