## Lisp terminology

Collection of Lisp terminology I come accross while learning haskell & functional programming!

### CAR
operation on lists that returns a pointer to the first element of the list.

### CDR
operation on lists that returns a pointer to the rest of the list.

### Dotted pair
a list notation, where the CAR & CDR are shown explicitly: `( a . b )` "a" is CAR and "b" is CDR. In haskell, something similar is `(x:xs)` where "x" is the first item of the list, and "xs" is the rest of the list.
