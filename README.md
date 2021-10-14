The in-class compiler status after class sessions about functions.  See lecture notes for more detail.

To run:

`dune utop`

Inside utop:

`open Cs164.Compile;;`

`compile_and_run "(define (fib n) (if (< n 2) n (+ (fib (- n 1)) (fib (- n 2)))))
(print (fib (read-num)))";;`
