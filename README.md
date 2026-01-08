# Realme X7 Max Audio Policy Fix
**Author:** xCaptaiN09
**Device:** Realme X7 Max (RMX3031)

## ⚠️ Compatibility Warning
This module replaces `/vendor/etc/audio_policy_configuration.xml` with a version extracted from a working Realme X7 Max ROM.
* **Safe for:** Realme X7 Max (RMX3031).
* **Risky for:** Other devices (will break Speaker/Mic).

## ⚡ Features
1.  **Native Routing:** Uses official XMLs to fix USB audio paths correctly.
2.  **Smart Watchdog:** Restarts `audioserver` **once** when a DAC is detected (fixes "Silence on Connect").
3.  **Power Fix:** Prevents kernel sleep ("Pause Death").

##  Alternative Solution
If this module does not work for you, or if you are using a different device, try my universal kernel-level fix:
* **[USB Wakelock Injector](https://github.com/xCaptaiN09/USB_Wakelock_Injector)**

##  Installation
1.  Flash in Magisk/KernelSU.
2.  Reboot.
3.  Plug in your USB DAC.
