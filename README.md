# Dell-Optiplex-7010-Hackintosh-OpenCore
Tested on macOs High Sierra

## What's working
- WiFi (Ethernet untested)
- Nvidia Quadro K2200 4GB
- USB ports (but not all, 7/10 working)
- Audio (might have to set in macOS: System Preferences -> Sound -> Output)

## What isn't working
- Sleep (not working correctly, once woken from sleep macOS will most likely freeze.).
I would recommend that you do the following in macOS:
    - System Preferences -> Energy Saver -> Tick "Prevent computer from sleeping automatically when the display is off".
    - Set the "Computer sleep" slider to **Never** if you have that option ("Display sleep" can be left alone as that just turns off the display).
    - UPDATE: it might work sometimes if you got lucky. I would try out Sleep before you disable it and see if it works and doesn't crash macOS.

## Supported graphics
iGPU (HD4000) is untested. I am using a Nvidia dGPU (Quadro K2200)


yeah that's really it lol
