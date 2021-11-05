The in-class compiler status after our second class session about first-class functions, the one that adds lambdas via desugaring.  See lecture notes for more detail.

To run:

`dune utop`

Inside utop:

`open Cs164.Interp;;`

`compile_and_run "(define (call-with-two func-arg) (func-arg 2))
(do 
    (let 
        ((y 3)) 
        (print 
            (call-with-two (lambda (x) (+ x y)))
        )
    ) 
    (newline))";;`
