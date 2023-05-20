### Hello everyone,

This document will serve as a guide to my repositories and will be updated regularly.

I'm a french computer engineer, with a very wide range of interests related to computer sciences and maths.

I'm working on a couple of projects which ought to be used together to ease software development.

### Documentation

In the repository "Documentation", you will find a project of documentation format intended for computer programs, although it can be used to document pretty much anything.

The format is based on the use of first-order logic. For those of you not familiar with maths, it basically means formal reasoning on propositions.

The aim of this project is to enable documentation of code toward a fully explicit documentation, and to get away from traditionnally implicit natural languages.

Developers are spending a fair amount of time solving bugs in their codes, some even states that it represent more than 50% of working time. I believe that this issue is partly due to poorly written, or even useless documentation of code. The documentation of code should show the concepts behind the code, rather than how those concepts are implemented in a specific context.

By describing concepts using this format, you can have a documentation which is ready to be exported to any project using related concepts, and you only need to write pieces specific to a particular implementation.

Additionnally, the aim of this format is to use whole librairies without even having to look at one piece of it's source code, something which is far from true to date.

On the one hand, the documentation should be made clean and clear, to enable information sharing about pieces of softwares.

On the other hand, the code should be made so as to fulfil performance requirements, and we shouldn't care about it's readability more than for future developers on the library. Libraries' users shouldn't have to look at the source code, and should only refer themselves to the documentation, which specify all possible behaviors of the libraries (even undefined ones, analoguously to what we can see in C++ specification).
