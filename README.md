# CMOS Clock Counter
 A clock made from CMOS IC's that counts in second increments

 ![image](https://github.com/user-attachments/assets/1e5e45ff-ed89-4309-9bb1-3d80a0cc427b)


This little clock counts the seconds up to 99,999 (1.15 Days) and then starts over again. I wanted it to be a visual reminder of the seconds ticking by and to try and not waste to many of them.

The clock is really a count up counter.  It uses the 4060 Binary counter CMOS chip to keep accurate time using a crystal oscillator. The 4060 IC can be used to generate a pulse at 1 second intervals which in turn can be used as a clock input to drive some 4033 Decade Counter CMOS chips to control some 7 segment displays.

The great thing about the 4033 IC is you can string them together in as many rows as you wanted to, meaning you could build a googol clock (1 followed by 100 zeros!) if you felt like it! Most of it would be blank until the end of the universe but it would still be pretty cool thing to build.

I designed a PCB to keep everything neat and tidy and also added some red transparent acrylic across the front to help diffuse the light from the 7 segment displays.

There are 2 versions available, one that runs off a 9V battery (untested) and one that runs off 5V USB C power - Both versions are available.

![image](https://github.com/user-attachments/assets/5ecac74b-ba1e-46a8-9963-a78da28d2065)
