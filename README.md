The in-class compiler status after class sessions about tail call optimization.  See lecture notes for more detail.

To run:

`dune utop`

Inside utop:

`open Cs164.Compile;;`

`compile_and_run "(define (sum n total)
  (if (zero? n)
    total
    (sum (sub1 n) (+ n total))))
(print (sum 1000000 0))";;`
