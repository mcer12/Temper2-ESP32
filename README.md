# Temper2-ESP32
Temper2 is a successor of my other project [Temper-ESP8266](https://github.com/mcer12/Temper-ESP8266), aimed at longer battery life and always-on display.

Notable differences from previous project
- Uses ESP32 with all of its upsides
- Doesn't rely on NTP so it doesn't need internet connection
- Even lower power consumption, 12-15uA in deep sleep 
- E-ink, so the values stay visible
- integrated WS2812 status led
- Two buttons that also work as a wake-up.
- Double sided PCB

## What you need to make it yourself
- 1.54" Waveshare E-ink display (B/W/R 152x152 version or 200x200 B/W version is best but apart from that, any Waveshare display can be used if you adjust the firmware and don't mind it will be larger than the pcb)
- Components listed in "PCB and BOM" directory (lcsc and aliexpress links provided)
- Hot air station / reflow oven, ideally both
- Solder paste, ideally two types, one very low temp, one higher temp.
- 3D printed plastic case (link tba)
- Patience, lots of.
