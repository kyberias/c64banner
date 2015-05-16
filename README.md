# c64banner


This is a solution to the programming assignment I got from a friend of my brother in ~1984 (now about 30 years ago). At the time, he was a student of computer technology and I was a 9-years-old just learning to grasp the basics of... well, BASIC. In retrospect, I think the assigment was slightly too hard for me at the time. But finally, after many years of practice, I think I've nailed it.

It is a C64 BASIC program that outputs big text banners to a seq file that can then be printed on tractor-feed paper with a dot-matrix printer. 
I'm sure this was something the students of computer technology needed for some purpose in their studies. Hopefully I've recalled the original requirements correctly.

It uses the C64 character ROM for font data (amazing trick!) and blows each pixel 3x3.

See [hello.seq](hello.seq) as an example output.

## Usage

```basic
LOAD "BANNER",8
RUN
TEXT ? <text to print>
FILENAME ? <output file name on device 8>
```
