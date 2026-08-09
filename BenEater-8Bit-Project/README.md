## Description

### Part 1 - The Clock 

*The computer's clock is used to synchronize all operations. The clock we're building is based on the popular 555 timer IC.* ((source)[https://eater.net/8bit/clock])

#### Part 1.1 - The timer or astable circuit 

The first "clock" is configured as an astable oscillator.

**Components not represented on the schema:**
- Resistors on potentiometer input/output (input is used to protect voltage short, and output is used to protect pin 7 from direct dicharge by the capacitor nearby)
- Ceramic Capacitors (one sits near power supply and the other one on the pin 5 of the 555 chip)
