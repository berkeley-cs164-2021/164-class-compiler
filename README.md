The in-class compiler status after our second class session about first-class functions, the one that adds lambdas via desugaring.  See lecture notes for more detail.

To run:

`dune utop`

Inside utop:

`open Cs164.Compile;;`

`compile_and_run "(define (f g) (g 2))
(do (print (f (lambda (x) (+ x x)))) (newline))";;`
