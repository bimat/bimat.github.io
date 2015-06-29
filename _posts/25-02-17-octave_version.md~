---
layout: page
title:  Octave port
date:   25-02-17 21:12:57
category: inst
order: 4
---
 
Altough <tt>BiMat</tt> was tested exhaustively in <tt>MATLAB</tt> only, a port was developed for <tt>octave</tt> too.

### Download

* [Bimat-oct Ver 1.0](https://github.com/cesar7f/BiMat/archive/bimat-oct.zip)

### Requierements

The biggest barrier to make <tt>BiMat</tt> available in <tt>octave</tt> in the past was the missing of the <tt>classdef</tt> constructor. However,
the newest realease of <tt>octave</tt> includes it. Therefore the user need to be sure to follow the next steps in order to use the <tt>octave</tt>
port:

* Install [<tt>octave 4.0</tt>](<tt>octave</tt>).
* Install the additional <tt>octave</tt> packages <tt>statistics</tt>. An easy way of doing it is by typing in the 
  <tt>octave</tt> prompt the following lines:
    * <tt>>>build_packages</tt>
    * <tt>>>pkg rebuild -auto io</tt>
    * <tt>>>pkg rebuild -auto statistics</tt>

### Important differences

Some important differences <tt>BiMat-oct</tt> with the original <tt>BiMat</tt> version are:

* <tt>Bimat-oct</tt> use strings instead of function handles when passing functions as arguments. For example an argument of the type
  <tt>@NestednessNTC</tt> need to be transformed to <tt>'NestednessNTC'</tt> when using a function that uses such argument. 
* Because documentation in <tt>octave</tt> does not follow the same convenction than in <tt>MATLAB</tt>, documentation in <tt>BiMat-oct</tt> 
  can not be acceded from the <tt>octave</tt> prompt.
* As the code was optimized to run in <tt>MATLAB</tt>, some of the code will run slower in the <tt>Bimat-oct</tt>.

