## Idea
The idea is to reimplement T.30 and transmit it over the air. The current idea is to use the 70cm band (433 in particular) and approach it similarly to LoRa. The issue, however is that:

> [!WARNING]
> I have no idea what I am doing. I've never done an ounce of DSP. My C is terrible. My C++ is non-existent. Not to mention that my PCBs only work 33% of the time.This is going to be fun, I think!


## Initial research and design choices
I decided to go for the RP2040 for the MCU, purely because *I did get a project to work with it* and I'd like to believe that I can do it again. As for the radio module, I'll probably go for some run-of-the-mill, well documented one - at least initially, as I am extremely new to this. I can already feel that crosstalk is going to be a major issue!
 