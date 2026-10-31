## How it works

A combinational two-input AND gate connects ui[0] (A) and ui[1] (B) to uo[0] (A AND B). The output is high only when both inputs are high. No clock is required.

## How to test

Start the Wokwi simulation and toggle DIP switches 1 and 2. Check all four combinations:

| A | B | Output |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

The LED on output 0 should light only for A=1 and B=1.

## External hardware

The browser simulation uses two DIP switch inputs and a red LED connected to output 0 and ground. No physical hardware is needed for this activity; FPGA testing is deferred.
