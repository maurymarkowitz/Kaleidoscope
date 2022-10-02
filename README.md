# Kaleidoscope
Commented Disassembly of  Li-Chen Wang's classic Kaleidoscope program for the Cromemco Dazzler

---

## What is/was Kaleidoscope

[Kaleidoscope](https://en.wikipedia.org/wiki/Li-Chen_Wang#Cromemco) is a rather tiny (127 Bytes) demo program for the [Cromemco Dazzler](https://en.wikipedia.org/wiki/Cromemco_Dazzler) by [Li-Chen Wang](https://en.wikipedia.org/wiki/Li-Chen_Wang). It displays a 64x64 colour graphic much like a mechanical [kaleidoscope](https://en.wikipedia.org/wiki/Kaleidoscope) using the repetitive structure of the Dazzlers memroy. The program was sold by Cromemco as on its own for 15 USD on [paper tape](https://americanhistory.si.edu/collections/search/object/nmah_1423437) or later on floppy disk as part of their _DAZZLER Games_ pack at 95 USD.

## Historic Relevance

While Kaleidoscope might be considered more like a short demo for same new hardware, it had an amazing effect in its time - and honest, it's still catchy - which other program can claim to have slowed down trafic to a stand still on NYC's 5th Avenue in NYC? It may also have influenced some other well known programmers to write similar programs - like the [COLOR DEMO](https://youtu.be/zF_LFsIni8Q) on the Apples DOS 3.2 Disk for the Apple II.

## Why Adding a Repository 40+ Years Later?

In early October 2022 Maury Markowitz [asked](https://retrocomputing.stackexchange.com/questions/25304) on [RetroComputing.SE](https://retrocomputing.stackexchange.com/) if there's some high level analysis for that program, as all he could find was a basic disassembly. I tried some Google-Fu, found are many sites mentioning Kaleidoscope, including a few [running some emulation](https://observablehq.com/@fil/kaleidoscope-1976) to show it's output (*1), but none offering a commented source or high level description - the only one [attempting to do so](https://www.quaxio.com/kaleidoscope_part1/) in 2020 [closed his blog](https://www.quaxio.com/last_post/) right before touching that part :(

Being curious (and a bit bored) I decided to take a look at the disassembly, resulting in what's found here.

## Further Reading

- ["Build the TV Dazzler"](http://www.bitsavers.org/pdf/cromemco/Dazzler_PE_Feb76.pdf) from February 1976 issue of Popular Elecronics (at Bitsavers)
- Dazzler as Interface Age's [Card of the Month](http://bitsavers.informatik.uni-stuttgart.de/pdf/interfaceAge/productReviews/1977-03_Cromemco_Dazzler.pdf) of March 1977 (at Bitsavers)
- [Cromemco Dazzler Instruction Manual](http://www.bitsavers.org/pdf/cromemco/Cromemco_Dazzler_Instruction_Manual_RevC_1976.pdf) Revision C of March 1976 (at Bitsavers)
- [TV-Dazzler advertisement](https://archive.org/details/CromemcoCatalogAugust1976/page/n3/mode/2up?view=theater) in the August 1976 Cromemco Catalogue (at Archive.Org), including pictures of their program offerings (on Paper tape :)).

## Files (so far)

- [Disassembly Listing](Disassembly%20Listing) -> Disassembly Listing used as base to regenerate the source
- [Kaleidoscope.asm](Kaleidoscope.asm) -> Commented source listing of the Dazzler Kaleidoscope program
- Kaleidoscope's ['manual' page](Kaleidoscope_Manual.png) from p.32 of the [Cromemco Dazzler Games Manual](http://www.bitsavers.org/pdf/cromemco/Cromemco_Dazzler_Games_1977.pdf) (at Bitsavers)
- README.md -> This file

---

*1 - Well, the [real output](https://www.youtube.com/watch?v=2tDbn1N8EWI) of a real Dazzler on a real CRT isn't as shiney and sterile as those modern browser implementations make it look:))
