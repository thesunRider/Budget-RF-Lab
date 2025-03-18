# Home-brew projects
Please feel free to add to this list of projects or modify this accordingly.

## List of starter projects
This contains a list of home-brew projects that you can try.


| Si. No | Name                                 | Assembly Time (in min) | Cost (in INR) | Where to Buy                                       | Comments                                                                                           | Links |
|--------|--------------------------------------|------------------------|---------------|----------------------------------------------------|--------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1      | Earthing                             | 2                      | ~0            | NA                                                 | Use a regular 220V (standard line voltage in India) LED bulb between Live and Earth to check.  | |
| 2      | RF Probe                             | 60                     | <200          | LCSC, Robu, Project Point, Synergy Telecom - Delhi |  | [Build one by following this article](https://n5ese.com/rfprobe1.htm). |
| 3      | Frequency generator (VFO)            |                        | 500-700       | NA                                                 |  | Details: [pico-hf-oscillator](https://github.com/kholia/pico-hf-oscillator), Alternate: [EasyVFO](https://github.com/kholia/EasyVFO) |
| 4      | Frequency counter                    | 2                      | 500-800       |                                                    | In many use cases, an oscilloscope can be used for checking the frequency of AF and RF signals. Pico 2 has many 5V tolerant pins. | DIY using Raspberry Pi Pico 2: [Project 1](https://github.com/kholia/pico_ft8_xcvr/tree/main/PicoFrequencyCounter-v2), [Project 2](https://github.com/kholia/pico_ft8_xcvr/tree/main/PicoFrequencyCounter), [Project 3](https://github.com/richardjkendall/rp2040-freq-counter) |
| 5      | Commercial Frequency Counter         |                        | 1100          | [Rees52](https://rees52.com/)                      | 9V Frequency Meter 500 MHz High Precision Reader RF | Related: [RF frequency counter buffer for HF](https://www.nutsvolts.com/magazine/article/build-an-rf-frequency-counter-buffer-for-hf) |
| 6      | Frequency reference                  | 15                     |               |                                                    |  | DIY using [uBlox7 TimePulse](https://github.com/kholia/uBlox7_TimePulse) |
| 7      | Local WSPR / FT8 / CW 10mW RF source | 2                      | ~500          |                                                    |  | [Easy-Digital-Beacons-v1](https://github.com/kholia/Easy-Digital-Beacons-v1), [Pico-FT8-TX](https://github.com/kholia/Pico-FT8-TX) |
| 8      | Local SSB signal source              | 15                     |               |                                                    | All it takes is one wire to solder / plug-in | [rpitx](https://github.com/kholia/rpitx) |
| 9      | RF Dummy load                        | 30                     | 500-700       |                                                    | DIY using a 50-ohm RF flange resistor + a suitable aluminum heat sink |  |
| 10     | RFGen (DIY RF Generator)        | 2 Days             | ~2000      | NA                                                 | DIY RF square wave generator (0-900 MHz) using Arduino or STM32 | [Project Link](https://github.com/thesunRider/RFGen) |


## RF security extended list

- HackRF One

- CC1101 SPI module (two)

  - https://www.ktron.in/product/cc1101-433mhz-module/

- Logic analyzer options

  - DIY using Raspberry Pi Pico

    https://github.com/pico-coder/sigrok-pico

  - [Alternate 1] DIY using Raspberry Pi Pico

    https://github.com/gusmanb/logicanalyzer

  - [Alternate 2] https://robu.in/product/usb-logic-analyze-24m-8ch-mcu-arm-fpga-dsp-debug-tool/

- Fault injection

  - https://github.com/MKesenheimer/fault-injection-library

## Fun Activities

- I want to get started with HF in 30 minutes? Tell me how!

  Build a 10mW WSPR beacon for 10m band using a Raspberry Pi Pico 2 MCU board.

  Use https://github.com/kholia/Easy-Beacons-STEM.

  Alternate: Already own a Raspberry Pi SBC? Then try https://github.com/JamesP6000/WsprryPi.

- I want to start receive HF traffic today - tell me how!

  - RTL-SDR v3 + random wire / active antenna

  - CD2003 receiver (< 500 INR) + random wire / active antenna

    See https://github.com/kholia/ConsensusBasedTimeSync for more details
