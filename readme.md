# IBM 5161 Planar / Backplane

***WARNING: This board is as yet untested and still under initial manufacturing and testing, and physical tolerances are unchecked.***

This project is a clone of the IBM 5161 planar (backplane) board. The 5161 planar is a 2 layer board that is very similar to a 5150/5160 motherboard minus everything but some power rails, clock and the ISA bus.

The clone herein should be accurate to within a few millimeters. If anyone would like to loan a real 5161 planar board to me I can correct a few things. Alternatively, feel free to commit back instead!

Design notes:
*The clone board is marked 1130600(TRS) on the front. TRS stands for TRS-Eric. This is how you can verify it is a clone board of this design.
*The back contains a datecode (currently 2333, 23rd year, 33rd week). This datecode functions as the version of this board. If you create your own board with modifications or another manufacturer other than JLCPCB, you may want to consider changing this date code.
*The holes for the capacitor are larger than normal to allow for other styles / models of variable capacitor. More information can be found at [minuszerodegrees.net](https://www.minuszerodegrees.net/5160/motherboard/IBM%205160%20motherboard%20-%20Capacitor%20C1%20replacement.htm).

Further information on the IBM 5161 is available from [minuszerodegrees.net](http://minuszerodegrees.net/5161/doco/5161_documentation.htm).

Clones of the IBM 5161 Sender and Receiver cards are available from Tube Time via [github.com]
(https://github.com/schlae/ibm-extender)

![Top of the 5161 planar clone board.](https://gitlab.com/trs-eric/5161-planar-backplane-board/-/blob/main/top.png)

![Bottom of the 5161 planar clone board.](https://gitlab.com/trs-eric/5161-planar-backplane-board/-/blob/main/bottom.png)

# License

This board is reproduced without permission under Title 17, Copyright Act of 1976, Fair Use statutes, 90 Stat. 2541.

This work itself is licensed under a Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0). See [https://creativecommons.org/licenses/by-sa/4.0/] (https://creativecommons.org/licenses/by-sa/4.0/)