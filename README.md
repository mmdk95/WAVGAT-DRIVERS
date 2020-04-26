# WAVGAT ARDUINO LIBRARY

Me and [several](https://forum.arduino.cc/index.php?topic=560692.0) [other](https://forum.arduino.cc/index.php?topic=540421.0) [people](https://forum.arduino.cc/index.php?topic=606114.0) have had issue the WAVGAT UNO, WAVGAT NANO and/or the WAVGAT Pro mini arduino clones. The provided driver just seemed outdated, so I simply merged it with the new arduino code and this repository contains the result. As far as I know it should be fully compatible with the Arduino now.

## Installation

- Clone or download repository
- Close your Arduino IDE if it is open
- Copy the `WAV` directory to `[Arduino install directory]/hardware/`
- Open arduino IDE again.
- Select `Tools` > `Programmer: "[blah blah blah]"` > `LGTSWD mkII as ISP`
- Select your WAVGAT board 
- Upload your Sketch and that should do it.

Happy Coding!