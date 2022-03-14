# A Bestiary of Single-File Implementations of Programming Languages

![From a French Prayer-book of the Thirteenth Century, in the British Museum.](https://raw.githubusercontent.com/marcpaq/b1fipl/master/FunnyAnimals.jpg)


## Programming langauges are amazing

Programming languages are amazing pieces of work. They turn our words, numbers, and symbols into the bits that make a machine do things.

It's easy to get overwhelmed when implementing a programming language. The GNU Compiler Collection is [millions of lines long](https://www.phoronix.com/scan.php?page=news_item&px=MTE1OTg).

That's too complicated to learn how to implement a programming language. Luckily, some smart people have distilled the most interesting parts of programming languages into an approachable essence. I'm referring to implementations of programming languages that fit in a single source code file.

These single-file implementations are rarely complete, hardly sophisticated or efficient. But they are self-contained, concise, and clear. They make it fun to discover why programming languages are amazing.

## Concatenative

[bbf, v3](https://github.com/blippy/cerbo/blob/master/forth/v3/forth.c) implemented by Mark Carter. A Forth in C.

[dc](https://github.com/dspinellis/unix-history-repo/blob/Research-V7-Snapshot-Development/usr/src/cmd/dc/dc.c) implemented by Lorinda Cherry.

[Forth1](https://gist.github.com/tluyben/16ee2645c4c8aed813005d51488d5c6a) implemented by Tycho Luyben.

[jonesForth](https://github.com/nornagon/jonesforth/blob/master/jonesforth.S) implemented by Richard W.M. Jones.

[Mouse](http://users.encs.concordia.ca/~grogono/Mouse/mouse.html) implemented by Peter Grogono.

## Functional

[7 lines of code, 3 minutes](http://matt.might.net/articles/implementing-a-programming-language/) implemented by Matt Might.

[arpilisp](https://github.com/marcpaq/arpilisp) implemented by Marc Paquette.

[How to implement a programming language in JavaScript](http://lisperator.net/pltut/) implemented by Mihai Bazon.

[(How to Write a (Lisp) Interpreter (in Python))](http://www.norvig.com/lispy.html) implemented by Peter Norvig.

[komplott](https://github.com/krig/LISP) implemented by Kristoffer Grönlund.

[Lisp500](https://web.archive.org/web/20040305005602/http://modeemi.cs.tut.fi/~chery/lisp500/) implemented by Teemu Kalvas. 

[Lisp9](https://www.t3x.org/lisp9/index.html) implemented by Nils M. Holm. A byte-compiling Lisp interpreter.

[Lisp90](http://howtowriteaprogram.blogspot.com/2010/11/lisp-interpreter-in-90-lines-of-c.html) implemented by Anthony C. Hay.

[Lisp In Less Than 200 Lines Of C](https://carld.github.io/2017/06/20/lisp-in-less-than-200-lines-of-c.html) implemented by Carl Douglas.

[MiniLisp](https://github.com/rui314/minilisp) implemented by Rui Ueyama.

[Mini-Scheme](https://github.com/catseye/minischeme) updated by Chris Pressey, originally implemented by Atsushi Moriwaki.

[mLite](https://www.t3x.org/mlite/index.html) implemented by Nils M. Holm. A lightweight variant of ML.

[Most functional](http://www.ioccc.org/2012/tromp/hint.html) implemented by John Tromp. An implementation of binary lambda calculus in 25 lines of obfuscated C.

[sectorlisp](https://github.com/jart/sectorlisp/blob/main/sectorlisp.S) implemented by Justine Alexandra Roberts Tunney et al. An x86 Lisp interpreter that fits in a boot sector.

[sedlisp](https://github.com/shinh/sedlisp) implemented by Shinichiro Hamaji.

[single_cream](https://github.com/rain-1/single_cream), scheme interpreter implemented by Raymond Nicholson.

[ulc](https://github.com/masaeedu/ulc) implemented by Asad Saeeduddin. A minimalistic implementation of the untyped lambda calculus in JS

## Imperative

[asm6502.py](http://www.dabeaz.com/superboard/asm6502.py) implemented by David Beazley.

[bc](https://github.com/depsterr/bc) implemented by depsterr. Compiles brainfuck into an x86_64 linux binary.

[Brainfuck](http://www.muppetlabs.com/~breadbox/software/tiny/bf.asm.txt) implemented by Brian Raiter.

[c4](https://github.com/rswier/c4) C in 4 functions, implemented by Robert Swierczek.

[Jasic](https://github.com/munificent/jasic) implemented by Robert Nystrom. Old-school BASIC in Java.

mescc-tools-seed, implemented by Jeremiah Orians. A complete chain of
one-file languages, from compiler to assemblers and even a shell, for Intel x86: 
[C compiler in assembly](https://github.com/oriansj/mescc-tools-seed/blob/master/x86/cc_x86.M1),
[macro assembler to build the C compiler](https://github.com/oriansj/mescc-tools-seed/blob/master/x86/M0_x86.hex2),
[hex2 assembler to build the macro assembler](https://github.com/oriansj/mescc-tools-seed/blob/master/x86/hex2_x86.hex1),
[hex1 assembler to build the hex2 assembler](https://github.com/oriansj/mescc-tools-seed/blob/master/x86/hex1_x86.hex0),
[hex0 assembler to bootstrap the whole thing](https://github.com/oriansj/mescc-tools-seed/blob/master/x86/hex0_x86.hex0), and finally, a
[shell to script the previous stages](https://github.com/oriansj/bootstrap-seeds/blob/master/kaem-optional-seed.hex0).

[Mini-C](https://github.com/Fedjmike/mini-c) implemented by Sam Nipps. A small subset of C, of course. But not as small as you would guess.

[Pascal-S](http://standardpascal.org/pascals.html) implemented by Niklaus Wirth & Scott A. Moore.

[picol](http://oldblog.antirez.com/page/picol.html) is a Tcl interpreter implemented in C. Implemented by Salvatore Sanfilippo, aka antirez.

[Selfie](https://github.com/cksystemsteaching/selfie) includes a 1-file C compiler in C. Implemented by the Computational Systems Group at the Department of Computer Sciences of the University of Salzburg.

[swizzle](https://github.com/rswier/swizzle) implemented by Robert Swierczek.

[The Super Tiny Compiler!](https://github.com/thejameskyle/the-super-tiny-compiler) implemented by James Kyle.

[Tiny Basic](http://ittybittycomputers.com/IttyBitty/TinyBasic/index.htm) implemented by Tom Pittman.

[Trac](http://code.activestate.com/recipes/577366-trac-interpreter-sixties-programming-language/) implemented by Jack Trainor.

[Tutorial - Write a Shell in C](https://brennan.io/2015/01/16/write-a-shell-in-c/) implemented by Stephen Brennan.

[VTL02 for 6502](https://github.com/Klaus2m5/VTL02) ported and improved by Mike Barry. VTL-02 was originally designed and implemented by [Gary Shannon & Frank McCoy](http://www.altair680kit.com/manuals/Altair_680-VTL-2%20Manual-05-Beta_1-Searchable.pdf).

## Logical

[microKanren](https://github.com/jasonhemann/microKanren-DLS-16/blob/master/mk.rkt) is a Kanren interpreter, implemented by Jason Hemann.

[prolog.c](http://www.cl.cam.ac.uk/~am21/research/funnel/prolog.c) is a simple Prolog interpreter written in C++, implemented by Alan Mycroft.

[Prolog](http://t3x.org/lisp64k/prolog.html) originally implemented by Ken Kahn, adapted by Nils M. Holm.

[Tiny Prolog in OCaml](https://github.com/Naereen/Tiny-Prolog-in-OCaml-OneFile) is an interpreter for a subset of Prolog, in OCaml, implemented by [Lilian Besson (@Naereen)](https://github.com/Naereen/)

## Honourable Mentions

[256LOL](http://blog.jeff.over.bz/assembly/compilers/jit/2017/01/15/x86-assembler.html) implemented by Jeff Overbey. An x86 assembler in 256 lines or less. Technically not a single file but Jeff gives good descriptions of the problems with elegant, simple solutions.

[An Implementation of J](http://www.jsoftware.com/books/pdf/aioj.pdf) implemented by Arthur Whitney. See the appendix "Incunabulum". It's only a fragment of the J interpreter, but its conciseness is impressive.

[A Regular Expression Matcher](http://www.cs.princeton.edu/courses/archive/spr09/cos333/beautiful.html) implemented by Rob Pike, exegesis by Brian Kernighan.

[JS-Interpreter](https://github.com/NeilFraser/JS-Interpreter/blob/master/interpreter.js) implemented by Neil Fraser. A JavaScript interpreter in JavaScript. This file is part of a larger project for running JavaScript in a sandbox. 

[Microlisp](https://github.com/lazear/microlisp), a Scheme-like lisp in less than 1000 loc of C, implemented by Michael Lazear. A single-implementation with extra files for examples and building.

[Tiny Compiler](http://blog.mgechev.com/2017/09/16/developing-simple-interpreter-transpiler-compiler-tutorial/) implemented by Minko Gechev. It translates only arithmetic expressions, but it's well written.

## Epilogue

Have you implemented a programming language in a single file? Let me know with a pull request.

Or branch your own b1fipl. If you do, please give me credit.

## Image credit

Parton, James. _Caricature and Other Comic Art in all Times and many Lands_. Project Gutenberg. Retrieved 2021-02-04. http://gutenberg.org/ebooks/39347
