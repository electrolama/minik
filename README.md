# minik

A tiny RP2040 module for small embedded things!

minik is designed by Electrolama / @omerk and licensed under the Solderpad Hardware License 2.0.


## Status

module design files are already in this repo, breakout and libraries to follow. [Here's a preview](https://twitter.com/OmerK/status/1535297431444791298) of what the module and breakout looks like.


## CircuitPython support

When [this PR](https://github.com/adafruit/circuitpython/pull/6485) is merged, you'll be able to download CircuitPython builds for minik [here](https://adafruit-circuit-python.s3.amazonaws.com/index.html?prefix=bin/electrolama_minik) (no builds available until the PR is merged). 

Until then, grab [our fork](https://github.com/electrolama/circuitpython/), checkout the `add-board-electrolama-minik` branch and build following the instructions [here](https://learn.adafruit.com/building-circuitpython/introduction). Replace build command in those instructions with `make BOARD=electrolama_minik`.

Alternatively, you can use the [build for Pico](https://circuitpython.org/board/raspberry_pi_pico/) for now while we sort out the custom build.