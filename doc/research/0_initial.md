## Idea
The idea is to reimplement T.30 and transmit it over the air. The current idea is to use the 70cm band (433 in particular) and approach it similarly to LoRa. The issue, however is that:

> [!WARNING]
> I have no idea what I am doing. I've never done an ounce of DSP. My C is terrible. My C++ is non-existent. Not to mention that my PCBs only work 33% of the time.This is going to be fun, I think!

The issue is that I would like to do too many things at once. Alongside the general lack of knowledge related to this project, I also want to experiment with Rust on embedded. We'll see how that one goes, if it goes at all <sub> foreshadowing </sub>.

Here's a list of the initial stack I'm working with along with my confidence/experience in each component:
- KiCad: I have no idea what I'm doing, I've only ever used EasyEDA
- C/C++ w/ pico-sdk: Again, no idea what I'm doing. Idk how CMakeLists works. I've read very limited documentation.
- Rust(?): Total beginner, still at basic data manipulation.
- General electronics: I pretty much only know that R = V/I (and I had to look it up to make sure that I remember it correctly...)!
- Time: Limited

## Initial research and design choices
I decided to go for the RP2040 for the MCU, purely because *I did get a project to work with it* and I'd like to believe that I can do it again. As for the radio module, I'll probably go for some run-of-the-mill, well documented one - at least initially, as I am extremely new to this. I can already feel that crosstalk is going to be a major issue!
