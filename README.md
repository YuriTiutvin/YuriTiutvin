## Yuri (Iurii) Tiutvin

Electrical engineering senior at UC Davis, graduating June 2027 and based in San Jose. I'm looking for full-time roles in embedded systems, analog hardware, and validation/test engineering, and I'm open to part-time or co-op work during the school year.

The projects below were designed, built and tested outside of coursework, spanning embedded firmware and digital signal processing. Each repository carries the schematics, source code, design decisions and bench measurements behind it.

[Portfolio site](https://yuritiutvin.github.io) · [itiutvin@gmail.com](mailto:itiutvin@gmail.com)

---

### Projects

**[Audio Spectrum Visualizer](https://github.com/YuriTiutvin/audio-spectrum-visualizer)** — a desk light display for anyone who likes to see their music: it listens to the room and shows the bass, mids and treble of whatever is playing as three moving LED bars. An ESP32 microcontroller runs the frequency analysis and drives three LED bar-graph chips through filtered PWM signals.
Checked on the bench: LED driver switching points measured with a multimeter on three chips (equal 0.33 V steps); supply current 71–238 mA at 5 V; PWM filtering confirmed on an oscilloscope.
`ESP32 (Espressif microcontroller)` `C++ (Arduino)` `Signal processing (FFT)` `ADC & PWM` `Analog filtering` `USB-C power`

**[Reaction Time Game](https://github.com/YuriTiutvin/reaction-time-game)** — a handheld reaction timer for Formula 1 fans. It runs the same five-light start sequence used at an F1 race start and measures reaction time in milliseconds. Built around a Raspberry Pi Pico microcontroller, with its own rechargeable battery, charger and a hardware switch-debounce circuit.
Timer verified against an oscilloscope: every reading within 10 ms across 10 test rounds.
`Raspberry Pi Pico (RP2040)` `MicroPython` `I²C` `Digital logic` `Battery power` `Oscilloscope`

<!-- PROJECT TEMPLATE — copy, paste above this comment, replace the capitalised parts.

**[PROJECT NAME](REPO_URL)** — WHO IT IS FOR AND WHAT IT DOES, IN PLAIN LANGUAGE. ONE SENTENCE NAMING THE KEY HARDWARE WITH A PLAIN GLOSS.
HEADLINE RESULT, SAYING HOW IT WAS MEASURED AND OVER HOW MANY TRIALS.
THE PROJECT'S CANONICAL TAG LIST, 5 TO 7 TERMS, IDENTICAL TO THE SITE CARD

-->
