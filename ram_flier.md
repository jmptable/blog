---
date: 2010-02-13 01:17:54
---

From my old hackniac blog.


![](http://hackniac.com/images/relic/ram_flier.png)

This project was started during an unexpected 6 day winter vacation (due to snow). The idea is to allow the user of a TI-84 calculator to scroll through the entirety of the calculator's RAM visually and be allowed to modify values. The ultimate goal is a full hex editor for the calculator with support for modifying and analyzing the RAM of other running programs. It is my first TI Assembly project.

Currently you can scroll through the calculator's RAM in any direction. The values in RAM at the viewing area are simply dumped to the screen, meaning that each pixel represents a bit and bytes can be seen from left to right (12 on each row because the screen is 96 pixels wide).
