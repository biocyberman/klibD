# klibD
Port of klib https://github.com/attractivechaos/klib to play with D

Try to make a pure D version of klib.

## Why a pure D version?

`D` advocates (ref) point out that it is not necessary to convert numerous C libraries to D. Instead, they recommend [interfacing with C library directly](https://dlang.org/spec/interfaceToC.html). At the same time, there is a [guide](https://dlang.org/ctod.html) of how to do some common patterns in C with D. I personally would like to see how to do more advanced things in C in pure D. This makes it more attractive to use more D instead of C. Furthermore, with more modern style and features, the pure D version will allow easy maintenance and development. `klib` is a relatively small library with some advanced C stuffs. Therefore it is a good real-world demonstration of how to go from C to pure D.
