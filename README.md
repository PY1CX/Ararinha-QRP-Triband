# Ararinha-QRP-Triband

This is a PCB for the Ararinha 6 project from Miguel PY2OHH.

You can find the correct values of the BPF for 40/20/15m bands on the RFSim99 files in the repository.

Already tested in this project:
- IF
- Microphone Pre-Amplifier
- LM386 Audio Output

Note on RF Switching: I found that the MASWSS0136TR is a better RF Switch for the project than the one in the PCB, going for it. Less expensive and doesn't have the 50 ohm termination that could ruin the project impedances.  

Note on RF transistors: I started building the project with 2n3904 but I'm going to switch to the 2SC4915 that are in use in newer radios and have better specifications on RF. Decided on them because I wanna beat the record for Ararinha design, using it on 15m and later on 
6m band.

A 3D preview of the 4 layer board for the Ararinha 6 Project
![Preview](https://github.com/PY1CX/Ararinha-QRP-Triband/raw/master/ArarinhaPCB3D.png)

It's free to copy or modify and uses the Beerware License ( https://en.wikipedia.org/wiki/Beerware )


