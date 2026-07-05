# Mini EREBUS for Oric-1/Atmos

## Story

Oric-1 and Oric Atmos were 8-bit machines designed in early 80's by Tangerine Computer Systems to compete with Sinclair ZX Spectrum. The success however, was very limited at best. Both machines differed only in keyboard and utilized 6502 processor, 16KB ROM, 48KB RAM, AY 3-8912 based sound and used tape as storage. They were also equipped with printer and extension ports.

Extension port allows today to build simple device to read programs from SD card. The device is called EREBUS and consist of couple of gates and flip-flops and 64KB of ROM. Could be bought on ebay but it's really hard to find its sources). There is also [EREBUS II version](https://github.com/f4goh/oric/tree/main/Erebus) by Kenneth that uses GAL instead of mentioned logic gates (which in turn is based on [another CPLD version](https://github.com/Fred72z/ORIC/tree/main/BUS_ORIC/Extensions/Erebus) by Fred72). THIS project is mini version of GAL one:

## Description

* The PCB is much smaller then original EREBUS (and EREBUS II as well)
* PCB is directly (without IDC cable) connected to Oric extension port
* There is Reset switch :-) because not-easily-accessible switch on bottom is in fact NMI.

Have fun!

Tomek

> [!NOTE]
> **Disclaimer**: This is my project that I’ve built and it works for me. You can do it as well but remember, you’re responsible for your own doings 
