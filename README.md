# ESP32-Audio-Kit

* Installed [CP210X](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers) and [CH340X](https://github.com/justcallmekoko/ESP32Marauder/blob/master/Drivers/CH34x_Install_Windows_v3_4.EXE) drivers
* Connected board via UART
* ESPHome web installer: https://web.esphome.io/
* Installed esphome on brick, and adopted device
* 

Gave up, I'd have to solder a TINY capacitor, which I'm unable to do: https://community.home-assistant.io/t/esp32-a1s-audio-kit-for-voice-assistant/568301/18

Software-wise, I could change adc_input = AUDIO_HAL_ADC_INPUT_LINE2, but I don't know how to do that on ESPHome, and I don't want to do anything manually
https://github.com/Ai-Thinker-Open/ESP32-A1S-AudioKit/issues/26#issuecomment-1017147212
https://www.pschatzmann.ch/home/2021/12/15/audiokit-audio-input/
https://www.pschatzmann.ch/home/2021/12/15/the-ai-thinker-audiokit-audio-input-bug/

I bought a M5Stack ATOM Echo

## References
* https://www.aliexpress.com/item/33003284057.html
* https://docs.ai-thinker.com/en/esp32-a1s
* https://github.com/comigor/esp-01-demo
* https://community.home-assistant.io/t/esp32-a1s-audio-kit-media-player/522245
* https://community.home-assistant.io/t/esp32-a1s-audio-kit-for-voice-assistant/568301/4
* https://forums.slimdevices.com/forum/user-forums/3rd-party-hardware/112805-squeezelite-esp32-on-esp32-audio-kit-v2-2-rotary-encoder-ssd1322-screen-2-keys?116009-Squeezelite-esp32-on-ESP32-Audio-Kit-v2-2-Rotary-Encoder-SSD1322-Screen-2-keys=
* https://community.home-assistant.io/t/esp32-audio-kit-esp32-a1s-with-squeezelite-for-notifications/376835/10
