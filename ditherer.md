---
date: 2009-10-22 00:54:04
---

From my old hackniac blog


![](http://hackniac.com/images/relic/ditherer.png)

In my Information Engineering class at school we did an activity involving dithering. We were supposed to create an image using MS Paint of anything we wanted using the principles of dithering. That meant that whatever image we came up with had to be black and white and drawn in dots of varying sizes.

I knew right away that anything I would create directly in MS Paint would look horrible, and there was extra credit at stake, so I took the route that was more natural to me. As soon as we got into the computer lab I fired up the Processing environment and wrote a little program to take an image of myself (of course) and use a simple algorithm to dither it. All it did was check the brightness of every pixel in the image and fill in a block of 4 pixels according to the brightness. What resulted was a nice example of dithering, although it was inverted (because I made brighter pixels have larger dots). I took a screen print of this output and pasted it into Paint. From there it was a simple matter of cropping and printing.

Sadly I lost the competition for the extra credit; the other classes did not vote my picture into the top three. There was some yelling about cheating from the other kids in my class, which I guess is reasonable from their perspective, but made me rather sad. It's taken years of practice to get familiar with programming to the extent that I can write a little program like this in one go within a short amount of time.

Whatever the other kids in my class think, the result was really cool in my mind, so I expanded upon it. The final program I created is below, it can take any image and dither it using any number of gray levels, although it is hard coded for 10 levels at the moment.
