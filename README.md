# Teensy_4-1


- **600 MHz Cortex-M7 processor**: extremely fast, capable of handling real-time audio processing without glitches.

- **1 MB of RAM**: Huge RAM, this large memory allows huge buffers, so audio can be streamed and written to storage without dropouts. Can record minutes or hours. 

- **Built-in microSD socket**: native SDIO interface is much faster than SPI, allowing continuous audio recording for minutes or hours.

- **3.3 V logic**: compatible with most I2S microphones and peripherals without level-shifting.

- **Supports 44.1 kHz, 16-bit audio**: enabling high-quality recordings.

- Works with both I2S digital microphones and analog microphones.

- **Audio Library**: Integrated support via the Teensy Audio Library makes setup and coding much simpler compared to other microcontrollers.
  
Why Teensy? Watch [Youtube video](https://www.youtube.com/watch?v=75IvTqRwNsE)

More about using the Teensy for audio projects [here](https://www.youtube.com/watch?v=exhIvvogbsg&list=PLDnEejiR3mBwSYLSxqluI-c01M04JyP2c)

More about Teensy [here](https://www.sparkfun.com/teensy-4-1.html)

-----------
### Teensy set up (for Arduino IDE)

If you are using the Teensy 4.1 for the first time, you will need to follow the next set-up steps:

- Open your Arduino IDE, and click File > Preferences (on MacOS, click Arduino IDE > Settings).

- In "Additional boards manager URLs", copy this link: https://www.pjrc.com/teensy/package_teensy_index.json

- In the main Arduino window, open Boards Manager by clicking the left-side board icon, search for "teensy", and click "Install".

- Install the Teensyduino Library. See more [here](https://www.pjrc.com/teensy/td_download.html)

  
**On macOS**, Teensyduino installs a modified copy of Arduino IDE so you can use it with Teensy boards.

**On Windows**, the Teensyduino installer adds Teensy support directly into your existing Arduino IDE installation. Further installation guidance [for Windows](https://www.youtube.com/watch?v=az9oHKhK7Uc)

- done! Plug the Teensy 4.1 to your computer.

- Open Arduino IDE (on Windows) or Teensyduino (on macOS).

- Select Board: Teensy 4.1

- If the Teensy is not turning on, you might need to press the BOOST button. Unplug and plug again to reboot the board. 

- Upload Arduino's Blink example to test communication.


