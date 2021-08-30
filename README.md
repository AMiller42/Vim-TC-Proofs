# Vim TC Proofs

This is a collection of programs to prove that Vim is Turing Complete, for example by interpreting Turing Complete languages.

Note that this will be a bit different from VimScript, as all of these programs are collections of Normal/Ex mode commands. This has some key differences:

* Input/Output is done through reading/writing to/from the open buffer.
* We aren't creating any functions, only using functions that already exist. Instead, we will use macros.
* We won't use variables, or data structures like arrays or dictionaries. Data will be stored only as text, either in registers or in the buffer.
* There's probably other differences, but I don't feel like thinking of them.

You can try any of these programs yourself by opening Vim, then copy/pasting the program in to have it execute each command one after another.

You can also try them at [Try it Online!](https://tio.run/##K/sPBAA) using the V interpreter, which is backwards compatible with Vim.
