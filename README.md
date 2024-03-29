# CWPal

![CWPal image](https://github.com/cwestend/CWPal/blob/master/CWPal.gif)

Simple 10+2 (black and white are not real colors!) color palette from the time when people needed to print lines on screen and on paper! 

In the days of old, the poor scientists had to use trial-and-error to choose individual colors out
of weird color-schemes or palettes. A decent red was hard to find, let alone other different colors
that would stand-out on a data-visualization artifact called "screen" or "monitor" (black backgound,
of course!). When having to actually transfer these graphs to paper (white or what was the fashion 
at the time and had a dirty-greyish hue, a so-called "recycled" paper that stuck in printers and faded
fast as hell) to show to other coleagues the quest was really a daunting one!

But one foolhardy student at the time came up with a set of colors to get rid of this nonesense, 
basically out of boredom and anger in equal parts.

The student was lucky to be in a particularly successful Solar Physics group in Spain, and some colors
actually appeared in graphics on high impact journals such as Nature or The Astrophysical Journal.

Other crazy researchers chose to use these same colors at their own peril with different luck, demostrating
that luck and chance are different things and that a silly little palette only gives off some good-vibes,
if anything at all.

Use it at your own risk, and if you want to keep the good karma, tell your colleagues and friends 
and give some feedback!

cwestend.

P.D: Some papers, just to show off!
Nature doi:10.1038/37933
ApJ doi:10.1086/318376, 10.1086/318377

Setup (python):

The easiest way I found is to add a .mplstyle file and either call it with matplotlib.pyplot.style.use or just create it in ~/.config/matplotlib/stylelib:

(see https://matplotlib.org/stable/tutorials/introductory/customizing.html)

If you create a file in ~/.config/matplotlib/stylelib - default style directory for matplotlib, check yours with matplotlib.get_configdir() then you can just do:

```
% import matplotlib.pyplot as pl
% pl.style.use('cwpal')
```


