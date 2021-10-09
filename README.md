The in-class compiler status after class session about output.  See lecture notes for much more detail.

To run:

`dune utop`

Inside utop:

`open Cs164.Compile;;`

`compile_and_run_io "(do (print (pair (read-num) (read-num))) (newline) (print 5))" "3\n4";;`
