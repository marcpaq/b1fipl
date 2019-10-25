# A Bestiary of Single-File Implementations of Programming Languages

![From a French Prayer-book of the Thirteenth Century, in the British Museum.](https://raw.githubusercontent.com/marcpaq/b1fipl/master/FunnyAnimals.jpg "Credit: Project Gutenberg")


## Introduction

Programming languages are amazing pieces of work. They turn our words, numbers, and symbols into the bits that make a machine do things.

It's easy to get overwhelmed when implementing a programming language. The GNU Compiler Collection is [millions of lines long](https://www.phoronix.com/scan.php?page=news_item&px=MTE1OTg).

That's too complicated to learn how to implement a programming language. Luckily, some smart people have distilled the most interesting parts of programming languages into an approachable essence. I'm referring to implementations of programming languages that fit in a single source code file. 

These single-file implementations are rarely complete, hardly sophisticated or efficient. But they are concise, clear, and easy to understand, letting you discover why programming languages are amazing.

## Functional

[7 lines of code, 3 minutes](http://matt.might.net/articles/implementing-a-programming-language/) implemented by Matt Might.

[arpilisp](https://github.com/marcpaq/arpilisp) implemented by Marc Paquette.

[How to implement a programming language in JavaScript](http://lisperator.net/pltut/) implemented by Mihai Bazon.

[(How to Write a (Lisp) Interpreter (in Python))](http://www.norvig.com/lispy.html) implemented by Peter Norvig.

[komplott](https://github.com/krig/LISP) implemented by Kristoffer Grönlund.

[Lisp9](https://www.t3x.org/lisp9/index.html) implemented by Nils M. Holm. A byte-compiling Lisp interpreter.

[Lisp90](http://howtowriteaprogram.blogspot.com/2010/11/lisp-interpreter-in-90-lines-of-c.html) implemented by Anthony C. Hay.

[Lisp In Less Than 200 Lines Of C](https://carld.github.io/2017/06/20/lisp-in-less-than-200-lines-of-c.html) implemented by Carl Douglas.

[MiniLisp](https://github.com/rui314/minilisp) implemented by Rui Ueyama.

[Mini-Scheme](https://github.com/catseye/minischeme) updated by Chris Pressey, originally implemented by Atsushi Moriwaki.

[mLite](https://www.t3x.org/mlite/index.html) implemented by Nils M. Holm. A lightweight variant of ML.

[sedlisp](https://github.com/shinh/sedlisp) implemented by Shinichiro Hamaji.

[single_cream](https://github.com/rain-1/single_cream), scheme interpreter implemented by Raymond Nicholson.


## Imperative

[asm6502.py](http://www.dabeaz.com/superboard/asm6502.py) implemented by David Beazley.

[Brainfuck](http://www.muppetlabs.com/~breadbox/software/tiny/bf.asm.txt) implemented by Brian Raiter.

[c4](https://github.com/rswier/c4) C in 4 functions, implemented by Robert Swierczek.

[dc](https://github.com/dspinellis/unix-history-repo/blob/Research-V7-Snapshot-Development/usr/src/cmd/dc/dc.c) implemented by Lorinda Cherry.

[jonesForth](https://github.com/nornagon/jonesforth/blob/master/jonesforth.S) implemented by Richard W.M. Jones.

[Mini-C](https://github.com/Fedjmike/mini-c) implemented by Sam Nipps. A small subset of C, of course. But not as small as you would guess.

[Mouse](http://users.encs.concordia.ca/~grogono/Mouse/mouse.html) implemented by Peter Grogono.

[Pascal-S](http://standardpascal.org/pascals.html) implemented by Niklaus Wirth & Scott A. Moore.

[swizzle](https://github.com/rswier/swizzle) implemented by Robert Swierczek.

[The Super Tiny Compiler!](https://github.com/thejameskyle/the-super-tiny-compiler) implemented by James Kyle.

[Tiny Basic](http://ittybittycomputers.com/IttyBitty/TinyBasic/index.htm) implemented by Tom Pittman.

[Tutorial - Write a Shell in C](https://brennan.io/2015/01/16/write-a-shell-in-c/) implemented by Stephen Brennan.

[VTL02 for 6502](https://github.com/Klaus2m5/VTL02) ported and improved by Mike Barry. VTL-02 was originally designed and implemented by [Gary Shannon & Frank McCoy](http://www.altair680kit.com/manuals/Altair_680-VTL-2%20Manual-05-Beta_1-Searchable.pdf).


## Honourable Mentions

[An Implementation of J](http://www.jsoftware.com/books/pdf/aioj.pdf) implemented by Arthur Whitney. See the appendix "Incunabulum". It's only a fragment of the J interpreter, but its conciseness is impressive.

[A Regular Expression Matcher](http://www.cs.princeton.edu/courses/archive/spr09/cos333/beautiful.html) implemented by Rob Pike, exegesis by Brian Kernighan.

[Tiny Compiler](http://blog.mgechev.com/2017/09/16/developing-simple-interpreter-transpiler-compiler-tutorial/) implemented by Minko Gechev. It translates only arithmetic expressions, but it's well written.

[256LOL](http://blog.jeff.over.bz/assembly/compilers/jit/2017/01/15/x86-assembler.html) implemented by Jeff Overbey. An x86 assembler in 256 lines or less. Technically not a single file but Jeff gives good descriptions of the problems with elegant, simple solutions.

## Epilogue

Have you implemented a programming language in a single file? Let me know with a pull request.

