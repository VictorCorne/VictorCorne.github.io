---
show_in_navigation: false
layout: page
---

## OCaml Interpreter for a time-reversible programming language
For the [Comparative study of programming languages course](https://onderwijsaanbod.kuleuven.be/syllabi/v/e/H04L5AE.htm#activetab=doelstellingen_idp11613024), we developped an interpreter for a new programming language.

This language (jaysub) had the main feature of being time reversible (that being that every line of code could be ran backwards). 
The language itself was fairly simple (contained assignments, conditional operators, loops, function calls, a program store, backward evaluation, ...), and we developped an interpreter for it in [OCaml](https://ocaml.org/) (an industrial strength functional programming language with emphasis on safety). We implemented the interpreter for forward and backwards evaluation of programs, as well as several optimisations for the source-to-source compiler to optimize runtime and memory usage (such as dead code elimination, constant folding and procedure inlining). 

A big thank you to [Denis Carnier](https://www.kuleuven.be/wieiswie/nl/person/00156298) for making such an interesting assignment!
- skills: Programming language fundamentals, functional programming, software design
- status: Completed (December 2023)
