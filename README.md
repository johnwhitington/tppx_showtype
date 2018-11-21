# tppx_showtype
Example typed PPX. Now we can do:

`ocamlopt -tppx tppx_showtype example.ml`

and see:

```
$ocamlopt -tppx ./tppx_showtype example.ml 
f : int -> int -> int
result : int
x : int
```

Do not try to install -- ocamlfind doesn't know about tppx (yet).


