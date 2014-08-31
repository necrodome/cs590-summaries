**Name**: Selem Delul
**Date**: 31 Aug, 2014

**Paper**: McCarthy, John. “Recursive Functions of Symbolic Expressions and Their Computation by Machine, Part I.” Communications of the ACM 3, no. 4 (1960): 184–95.

**Summary**: In this paper, McCarthy shows that a Turing-complete language can be
built with a few simple operators and a notation for function. He describes the
implementation details of such a language (LISP). Many key ideas in computation
history such as recursive functions, higher order functions (called Functions with
Functions as Arguments in the paper), garbage collection are presented in the paper.
He lies the foundations for a such system at the beginning, and then describes the
actual implementation of LISP Programmig System in the context of evaluating S-functions.

- - -

**Paper**: Reynolds, John C. “Definitional Interpreters for Higher-Order Programming Languages.” Higher-Order and Symbolic Computation 11, no. 4 (1998): 363–97.

**Summary**: In this paper, it is stated that a higher order programming language can
be defined in an interpreter written in a well-known language( these languages can be
called _defined_ and _defining_ languages respectively). After giving an informal language
definition, a meta-circular interpreter implementation is given as a transcription of
this informal language. A meta-circualr interpreter means that each future of the defined language
is defined in defining language's futures. While this can be useful for the reader who understands
the defining language well, it brings its own problems:

1. The meta-circular interpreter does not shed much light on the nature of higher-order functions.
2. Changing the order of application used in the defining language requires a similar change in the defined language.
3. Extending the defined language for imperative futures is impossible without extending the defining language.

The author's solution for each of these problems are given as (respectively) by introducing closures and continuations.
