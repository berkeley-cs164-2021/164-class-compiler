The in-class compiler status after our class session about adding constant folding.  See lecture notes for more detail.

To run:

`dune utop`

Inside utop:

`open Cs164.Compile;;`

`compile_and_run "(print (add1 (sub1 (add1 5))))";;`

vs.

`compile_and_run "(print (add1 (sub1 (add1 (read-num)))))";;`
