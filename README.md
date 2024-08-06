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
- **LED 2**
  - GPIO 03
  - Start: 244
  - Length: 127
- **LED 3**
  - GPIO 04
  - Start: 371
  - Start: 124
 
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

### Segments

- **Segment 0:**
  - The middle building
  - 2d grid
  - 
  
  - **ledmap.json** The middle building map, as a grid
  - **ledmap1.json** Also the middle building map, as a grid (duplicate)
  - **ledmap7.json** The middle building map, as a strip. Includes all turns and bends.
- **Segment 2:** The left side burst
  - 
  - LED 2 on the controller
  - **ledmap2.json** Left burst, as a grid 
  - **ledmap8.json** Left burst, as a strip. Includes all turns and bends.
- **Segment 3:** The right side burst
  - 
  - LED 3 on the controller
  - **ledmap3.json** Right burst, as a grid 
  - **ledmap9.json** Right burst, as a strip. Includes all turns and bends.

### Power

Wiring the AC plug to the power supply:

- **Green:** Earth / ground
- **White:** Neutral / N
- **Black:** Live / L

Controller [wiring guide](https://quinled.info/2020/10/03/quinled-dig-quad-wiring-guide/). Note that no voltage jumpers are needed for our pre-assembled version.




