# Inheritance

![Status: Not Ready](https://img.shields.io/badge/Status-Not%20Ready-red.svg)

This tutorial introduces the reader to Java inheritance and polymorphism via inheritance.

### Prerequisites

This tutorial assumes that the reader has a knowledge of basic Unix commands and experience working
with a command-line text editor (e.g. emacs, vi, etc.). The reader should be familiar with compiling
and running Java code contained in packages and working with the Javadoc tool.

To get the most out of this tutorial, you should follow along and take notes.

## Course-Specific Learning Outcomes

*

### Getting Started

### What is Inheritance?

In its simplest terms, **inheritance** in Java is a way to create a new class based on an
existing class. Without inheritance, you would be forced to take one of two approaches:

1. create a new class that is a copy-paste of the original class with additional code,
   as needed; or

1. create a new class that only contains the additional code.

The first approach results in a lot of duplicate code, thus increasing code maintenance
and decreasing code reuse. The second approach is perhaps a little nicer, however, it
would require that every object of the new class be bundled somehow with an object of
original class in order to have all the data and methods available.

In Java, inheritance actually combines the ideas in these two approaches without the
need for any manual copy-paste of the source code. This is demonstrated in the following 
video example:

VIDEO LINK HERE

VIDEO IMAGE LINK HERE

The starter code for the example in the video can be found [here](person/).

### The "is-a" Relationship

### Constructors

### Method Overrides

<hr/>

[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-nc-nd/4.0/)

<small>
Copyright &copy; Michael E. Cotterell, Bradley J. Barnes, and the University of Georgia.
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a> to students and the public.
The content and opinions expressed on this Web page do not necessarily reflect the views of nor are they endorsed by the University of Georgia or the University System of Georgia.
</small>