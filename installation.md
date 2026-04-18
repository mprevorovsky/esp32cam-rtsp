# Installation notes for Visual Studio Code

- clean old configurations: go to `Terminal > Run Task...` and select `PlatformIO: Erase Flash (esp32cam_ai_thinker)`. *If not done, the internal configuration web server at `192.168.4.1` will remain protected by any old passwords!*
- build the FW: go to `Terminal > Run Task...` and select `PlatformIO: Build(esp32cam_ai_thinker)`
- upload the FW: go to `Terminal > Run Task...` and select `PlatformIO: Upload(esp32cam_ai_thinker)`
- monitor the ESP32-CAM device: go to `Terminal > Run Task...` and select `PlatformIO: Monitor (esp32cam_ai_thinker)`
