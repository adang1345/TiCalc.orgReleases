Multiple Pixel Change by Aohan Dang

Description
The TI-89's functions PxlOn, PxlOff, and PxlChg can change only one pixel on the graph screen at
a time. Included are three programs that can change multiple pixels at a time.

How to install and run
Send plxonm.89p, plxoffm.89p, and pxlchgm.89p to your TI-89 or TI-89 Titanium. The correct
syntax for each of these programs is prgmname({row1,column1,row2,column2,row3,column3...}). The
argument is a matrix in which every two elements are the coordinates of one pixel on the
graph screen. For example, pxlonm({1,3,4,6}) is the same as PxlOn(1,3):PxlOn(4,6).