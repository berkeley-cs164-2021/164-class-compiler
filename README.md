The in-class compiler status after our first class session about first-class functions.  See lecture notes for more detail.

To run:

`dune utop`

Inside utop:

`open Cs164.Compile;;`

`compile_and_run "(define (f g) (g 2))
(define (mul2 x) (+ x x))
(print (f mul2))";;`
