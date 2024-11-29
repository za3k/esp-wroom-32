## Pinout diagram

## Battery options

| Battery Name | Type     | Voltage | Stoage (claimed, mWH) | Power (claimed, J)
| AG13LR44     | Alkaline | 1.5V    | 240 mWH [160 mAH]     | 864 J
| CR2032       | Lithium  | 3V      | 720 mWH [240 mAH]     | 2,592 J
| AAA (nimh)   | NiMH     | 1.2V    | 1,020 mWH [850 mAH]    | 3,672 J
| AA (nimh)    | NiMH     | 1.2V    | 1,200 mWH [1,000 mAH]  | 4,320 J
| 18650        | Li-ion   | 3.6V    | 9,000 mWH [2500 mAH]   | 32,400 J

## Power usage

| State       | Watts (datasheet) | Joules / day | Days / AAA
| Active      | ???                  | ???                  | ???
| Modem-sleep | 89-158 mW = 27-48 mA | 7,600 - 14,000 J/day | 0.26-0.48 days (6-12 hours)
| Light-sleep | 2.64   mW = 0.8 mA   | 228 J/day         | 16 days
| Deep-sleep  | 0.033  mW = 10 µA    | 2.9 J/day         | 1,266 days (3.5 years)
| Hibernation | 0.0165 mW = 5 µA     | 1.4 J/day         | 2,622 days (7 years)
| Off         | 0.0033 mW = 1 µA     | 0.29 J/day        | 12,662 days (35 years)

- GPIO is 3.3V out, and is **not** 5V tolerant.
- Screen refresh power usage: unknown
- Power usage to make a web request: unknown
- Power usage to connect to wifi: unknown
