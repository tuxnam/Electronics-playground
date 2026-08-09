# Description

The goal of this project was to learn and tinker with electronics but also understand low-level CPU principles (basic ones).
I came accross Ben's project(s) and his amazing pedagogic work and kits allow to build knowledge from the ground up. 
I document here some info, schemas and pictures of the [8-Bit computer project](https://eater.net/8bit) which I followed using the series of [YT videos](https://youtu.be/kRlSFm519Bo?si=gK9NJFnHcegY1x9O) from Ben.
I also document a few references which allow to expand knowledge of the components used.

## Part 1 - The Clock 

*The computer's clock is used to synchronize all operations. The clock we're building is based on the popular 555 timer IC.* ([source](https://eater.net/8bit/clock))

### Part 1.1 - The timer or astable circuit 

The first "clock" is configured as an astable oscillator.

#### Circuit

![]([https://github.com/tuxnam/Electronics-playground/blob/main/BenEater-8Bit-Project/8Bit-Clock-Part1-Pic1.jpg](https://github.com/tuxnam/Electronics-playground/blob/main/BenEater-8Bit-Project/Circuit-BenEater-8Bit-Clock-Part-1.png)

#### Pictures of my breadboard

(ignore the blue wire going from pin 4, its for part 3 of the clock!)

![](https://github.com/tuxnam/Electronics-playground/blob/main/BenEater-8Bit-Project/8Bit-Clock-Part1-Pic1.jpg)
![](https://github.com/tuxnam/Electronics-playground/blob/main/BenEater-8Bit-Project/8Bit-Clock-Part1-Pic2.jpg)
![](https://github.com/tuxnam/Electronics-playground/blob/main/BenEater-8Bit-Project/8Bit-Clock-Part1-Pic3.jpg)


**Components not represented on the schema:**
- Resistors on potentiometer input/output (input is used to protect voltage short, and output is used to protect pin 7 from direct dicharge by the capacitor nearby)
- Ceramic Capacitors (one sits near power supply and the other one on the pin 5 of the 555 chip)

### References

- Ben's 8-bit computer project - [8-Bit computer project](https://eater.net/8bit)
- 555 chip in-depth - https://www.instructables.com/555-Timer-IC/ and https://www.electronics-tutorials.ws/waveforms/555_timer.html
- [How resistors work](https://theengineeringmindset.com/how-resistors-work/)
- [How capacitors work](https://www.build-electronic-circuits.com/how-does-a-capacitor-work/)
- [How breadboards work](https://www.sciencebuddies.org/science-fair-projects/references/how-to-use-a-breadboard)
- [How current flow](https://www.albert.io/blog/how-does-electricity-flow/)
- The e-shop for the kits - [eShop](https://eater.net/8bit/kits) 

