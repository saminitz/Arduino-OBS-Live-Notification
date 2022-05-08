# ESP32 OBS Live LED & Twitch Web Interface (German)(work in progress)
An Arduino script that uses the [obs-websocket](https://github.com/obsproject/obs-websocket) to connect to [OBS Studio](https://github.com/obsproject/obs-studio) and set the to the ESP32 connected LEDs to a specific color.
All settings are controlled via a web interface. The website has a Twitch theme.

### Implemented Features ✓
- Control connected LEDs according to the OBS status
- Web Interface (German)
  - Save and load settings from ESP32 storage
  - Regulation of streaming and recording color
  - Regulation of the brightness
  - Time schedule after which the LEDs do not turn on even if OBS is still live
  - Manual control of the LEDs
  - Manual color
  - Access log via "/log"

### Coming Features 🕑
- Web Interface
  - Time schedule for manual control
