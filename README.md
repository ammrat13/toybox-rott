# Toybox for TinyCC

This repository hosts a fork of [Toybox][1] that can be compiled with
[TinyCC][2]. While it can be compiled, the `cpio` tests don't pass, so there are
likely some miscompilations.

To compile, simply supply the path to `tcc` in `CC` when calling `make`.

[1]: https://github.com/landley/toybox
[2]: https://bellard.org/tcc/
