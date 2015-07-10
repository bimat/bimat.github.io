---
layout: page
title:  Octave port
date:   25-02-17 21:12:57
category: inst
order: 4
---

With the intention of making <tt>BiMat</tt> fully available to anybody, a fully functional port <tt>BiMat-oct</tt> was developed for <tt>Octave</tt> too.
 
### Download

* [Bimat-oct Ver 0.99](https://github.com/cesar7f/BiMat/archive/bimat-oct.zip)

### Requierements

* [Octave Ver 4.0](http://www.gnu.org/software/octave/download.html). Unfortunately because previous versions of <tt>Octave</tt> lack the <tt>classdef</tt>
  constructor, <tt>BiMat-oct</tt> can not be used in such versions.<br><br>
* Additional build in <tt>Octave</tt> packages. The follwing lines install them from the octave port:
    * <tt>>>cd C:\octave\Octave-4.0\src</tt>    
    * <tt>>>build_packages</tt>
    * <tt>>>pkg rebuild -auto io</tt>
    * <tt>>>pkg rebuild -auto statistics</tt><br><br>
* _Recommended: Windows 7._ <tt>BiMat-oct</tt> was tested in both Windows 7 and Windows 8.1. While in Windows 7 we never observe a crash of the
  Octave GUI, under Windows 8.1 we observe a lot of craches during figure plotting. The reason appears to be that <tt>Octave 4.0</tt> is not fully stable
  on Windows 8.x. However the user can still make all sort of statistical analysis under this version of Windows.

### Installation:

For installing <tt>BiMat-oct</tt> you can follow the same instructions than the original version [<tt>BiMat</tt>](getting_started.html#2). That is, the user only need to add
<tt>BiMat-oct</tt> directory to <tt>Octave</tt> search path.

### Important differences between the Matlab and the Octave versions

Some important differences <tt>BiMat-oct</tt> with the original <tt>BiMat</tt> version are:

* <tt>Bimat-oct</tt> use strings instead of function handles when passing functions as arguments. For example an argument of the type
  <tt>@NestednessNTC</tt> need to be transformed to <tt>'NestednessNTC'</tt> when using a function that uses such argument. 
* Because documentation in <tt>octave</tt> does not follow the same convenction than in <tt>MATLAB</tt>, documentation in <tt>BiMat-oct</tt> 
  can not be acceded from the <tt>octave</tt> prompt.
* As the code was optimized to run in <tt>MATLAB</tt>, some of the code will run slower in the <tt>Bimat-oct</tt>.


### Examples:

Similar to <tt>BiMat</tt>, the user can execute all the examples in this website and on the [start guide](getting_started.html#5) by running the scripts 
on the <tt>examples</tt> directory of <tt>BiMat-oct</tt>. These scripts include the change of function handlers to strings mentioned above.

