# Differential Fault Injection on Atmega320 and AES

This repository contains the files associated
with the [differential fault injection tutorial](https://rot256.io/post/glitch/) posted on my site:

The `victim` directory holds the files for flashing the victim. Use USBasp via
the Makefile to write the correct "8 MHz fuses" to the chip.

The `attacker` directory holds the samples and scripts for recovering the key-material from these samples.

Also see https://github.com/kholia/avr-glitch-101.
