


# EREBUS II Mini for Oric-1/Atmos

## Story

Oric-1 and Oric Atmos were 8-bit machines designed in early 80's by Tangerine Computer Systems to compete with Sinclair ZX Spectrum. In spite of being interesting ones, their success was very limited. Both machines differed only in keyboard and utilized: 6502 processor, 16KB ROM, 48KB RAM, AY 3-8912 based sound and used cassette tape as storage. They were also equipped with printer and extension ports.

Extension port allows today to use simple device called EREBUS to read programs from SD card instead of tape. The device consists of couple of logic gates and flip-flops and 64KB of ROM. EREBUS can be bought on ebay but it's hard to find its sources. What can be found is [EREBUS II](https://github.com/f4goh/oric/tree/main/Erebus) by Kenneth that uses GAL instead of logic gates, which in turn is based on [CPLD version](https://github.com/Fred72z/ORIC/tree/main/BUS_ORIC/Extensions/Erebus) by Fred72. 

It is also worth mentioning that Oric-1 I have had problems working with EREBUS and worked nicely with EREBUS II.

## Description

This project is mini version of GAL based EREBUS II:

* The PCB is much smaller then EREBUS II and original EREBUS
* Module is supposed to be connected directly (without IDC cable) to Oric's extension port
* There is reset switch :-) because not-easily-accessible-button on the bottom of Oric's case is in fact NMI.
  
<img width="1054" height="1003" alt="EREBUS-II-Mini-schematic" src="https://github.com/user-attachments/assets/5ce2d2ba-504e-4277-8daf-6bdb8b8e2444" />

<img width="1889" height="2028" alt="925439df-7a89-4314-bb3d-89eb3ab42cc7" src="https://github.com/user-attachments/assets/680d29ab-17ef-4b08-8efa-75df063593a9" />

## Remarks

* Content of the EPROM and GAL22V10 program are taken from [EREBUS II](https://github.com/f4goh/oric/tree/main/Erebus). Thank you!
* The only problem I had was SD card that didn't work. Card should be less then 2GB, formatted to FAT16, no folders, 8.3 names recommended - if a card doesn't work, try another one
* If you want to have more compact design, do not use sockets for 74LS73 chips under the SD card reader
* Oric software can be found in [Internet Archive](https://archive.org/details/Tangerine_Oric_1_and_Atmos_TOSEC_2012_04_23) also, new software is developed - find it on [itch.io](https://itch.io)

Have fun!

Tomek

> [!NOTE]
> **Disclaimer**: This is my project that I’ve built and it works for me. You can do it as well but remember, you’re responsible for your own doings 
