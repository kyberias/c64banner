# c64banner

C64 basic program that outputs big text banners to a seq file that
can then be printed on tractor-feed paper with a dot-matrix printer.

Uses C64 character ROM for the characters. Blows each pixel 3x3.

See [hello.seq](hello.seq) as an example output.

## Usage

```basic
LOAD "BANNER",8
RUN
TEXT ? <text to print>
FILENAME ? <output file name on device 8>
```
