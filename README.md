# c64banner

C64 basic program that outputs big text banners to a seq file that
can then be printed on tractor-feed paper with a dot-matrix printer.

Uses C64 character ROM for the characters.

## Usage

```basic
LOAD "BANNER",8
RUN
TEXT ? <text to print>
FILENAME ? <output file name on device 8>
```basic
