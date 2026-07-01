# TOSLINK dual Transmitter

Converts two digital lines to optical (e.g. data and clock).

## Features

- allows inverting the clock signal
- optional chip select input for gating the clock
- if just straight-through signals are needed, omit the logic ICs and close the solder jumper for direct feed-through

## Specifications

- Optical transmitters: 2× Toshiba TOTX173 (6 Mb/s max)
- Supply: 8–18V, on-board L7805 5V regulator
- Logic: 74HC86 (clock invert), 74HC00 (clock gating via CS)

Made with KiCad version 9.

[Schematic (PDF)](toslink_dual_tx.pdf)
