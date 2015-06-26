# language-swig-wrapper

https://atom.io/packages/language-swig-wrapper

Language support for [SWIG](http://www.swig.org/) (Simplified Wrapper and
Interface Generator) for the [Atom](http://atom.io/) editor.


## About SWIG

(This description is from http://www.swig.org/exec.html)

SWIG is an interface compiler that connects programs written in C and C++ with
[scripting languages](http://www.swig.org/compat.html#SupportedLanguages). It
works by taking the declarations found in C/C++ header files and using them to
generate the wrapper code that scripting languages need to access the underlying
C/C++ code. In addition, SWIG provides a variety of customization features that
let you tailor the wrapping process to suit your application.


## About `language-swig-wrapper`

Since SWIG's interface files (`.i`) usually contain C or C++ code, this package
expands on grammars from the [`language-c`](https://atom.io/packages/language-c)
package. Essentially, this package takes the `language-c` package and adds
support for SWIG's `%include`, etc.


## Contributing

This package is distributed under the MIT license (see `LICENSE.md`).

Issues and pull requests are accepted in the GitHub repository.
