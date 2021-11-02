# `hop` 🦘 Higher-Order Programs

⚠ _Unstable - work in progress_ ⚠

Program composition for Unix pipes.

```
$ todo 'Add USAGE/examples here'
```

The idea of a "higher-order program (HOP)" is inspired by the idea of
[higher-order functions](https://en.wikipedia.org/wiki/Higher-order_function)
from functional programming. A HOP provides programs that take other programs
as arguments, and applies them to lines of stdin.

Of course, the idea is not novel. `timeout` and `xargs` are HOPs. Shells also
provide higher-order functions like `eval` and `exec` (among others). `test` is
often _both_ a program _and_ a shell builtin. Pipes themselves fill a similar
role to `map` and `filter` from the FP paradigm, too.

# Credits

2021 - By J.R. Hill

