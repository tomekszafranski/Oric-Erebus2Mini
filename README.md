# Mini EREBUS II for Oric-1/Atmos

## Story

Oric-1 and Oric Atmos were 8-bit machines designed in early 80's by Tangerine Computer Systems to compete with Sinclair ZX Spectrum. In spite of being interesting machines, success was very limited at best. Both machines differed only in keyboard and internally utilized: 6502 processor, 16KB ROM, 48KB RAM, AY 3-8912 based sound and used cassette tape as storage. They were also equipped with printer and extension ports.

Extension port allows today to use simple device to read programs from SD card instead of tape. The device is called EREBUS and consist of couple of logic gates and flip-flops and 64KB of ROM. EREBUS can be found on ebay but it's really hard to find its sources. What can be found is [EREBUS II version](https://github.com/f4goh/oric/tree/main/Erebus) by Kenneth that uses GAL instead of logic gates, which in turn is based on [another CPLD version](https://github.com/Fred72z/ORIC/tree/main/BUS_ORIC/Extensions/Erebus) by Fred72. It is also worth mentioning that Oric I used had problems with EREBUS application and works nicely with EREBUS II.

## Description

This project is mini version of GAL based EREBUS II:

* The PCB is much smaller then original EREBUS and EREBUS II
* Module is directly (without IDC cable) connected to Oric extension port
* There is Reset switch :-) because not-easily-accessible-button on the bottom is in fact NMI.

## Remarks

* The only probelm I had was SD card that didn't work. Card should be less then 2GB, formatted to FAT16, no folders, 8.3 names recommended
* Oric software can be found in [Internet Archive](https://archive.org/details/Tangerine_Oric_1_and_Atmos_TOSEC_2012_04_23) also, new software is developed - find it on [itch.io](https://itch.io)

Have fun!

Tomek

> [!NOTE]
> **Disclaimer**: This is my project that I’ve built and it works for me. You can do it as well but remember, you’re responsible for your own doings 
