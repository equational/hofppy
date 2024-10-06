# hofppy

Example and trial higher order functional programming in Python.
Three goals:
* Share and help others in applying higher order FP within classical language settings.
* Understand how best to use Python object and class artifacts to keep development productive.
* Understand how best to stage execution so as to preserve proper JAX JIT compilation even for complex constructions.
* Understand how best to package these concepts as reusable library component.

History:
* hofppy01.ipynb: building state/maybe/free monads bottom up. (initially based on my F# presentation https://www.youtube.com/watch?v=opm3KfHLqcI )
* hofppy02.ipynb: caputure monadic bind variable with pointfree accessors, and check that JAX's JIT is happy with this.
* hofppy03.ipynb: store comonad bottom up, and check that JAX JIT can deal with a shallow example. (Deeper for next update).
