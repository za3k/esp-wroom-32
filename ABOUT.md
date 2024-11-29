## Pinout diagram

## Tech specs
ESP32 is a single 2.4 GHz Wi-Fi-and-Bluetooth combo chip.

- GPIO is 3.3V out, and is **not** 5V tolerant.
- 0.03 mW deep sleep (about 2.6 J/day)

- [Datasheet](https://www.espressif.com/sites/default/files/documentation/esp32_datasheet_en.pdf)

## Features
- [Xtensa](https://www.cadence.com/content/dam/cadence-www/global/en_US/documents/tools/silicon-solutions/compute-ip/isa-summary.pdf)® single-/dual-core 32-bit LX6 microprocessor(s)
    - Internal 8 MHz oscillator with calibration, PLL running at 160 Mhz, or supports external oscillator
- 448 KB ROM, 520 KB SRAM
- 34 programmable GPIOs
    – Five strapping GPIOs
    – Six input-only GPIOs
    – Six GPIOs needed for in-package flash/PSRAM (ESP32-D0WDR2-V3, ESP32-U4WDH)
- 12-bit SAR ADC up to 18 channels, Two 8-bit DAC
- LED PWM up to 16 channels
- Five power modes designed for typical scenarios: Active (varies), Modem-sleep (30-45 mA), Light-sleep (0.8 mA), Deep-sleep (10 µA), Hibernation (5 µA)[, Off (1 µA). Power consumption in Deep-sleep mode is 10 µA
    - Two timer groups, including 2 × 64-bit timers and 1 × main watchdog in each group. One RTC timer

