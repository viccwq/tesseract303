tesseract dependencies-vs2010    
================    

### Modifications by [VIC](http://blog.csdn.net/k_shmily)    
This project built a open source leptonica(v1.70) for Tesseract(v3.03) in VS2010. The origianl project is built in [VS2013](https://vorba.ch/2014/tesseract-3.03-vs2013.html), and now a modified version is created in VS2010.     
Besides of the changed platform, the library of png(version1.6.29) is updated because of the error in previouse version.    

[Compiling Instructions 1](https://github.com/tesseract-ocr/tesseract/wiki/Compiling)    
[Compiling Instructions 2](https://vorba.ch/2014/tesseract-3.03-vs2013.html)

tesseract-vs2013
================

Tesseract OCR engine dependencies with VS 2013 support, both 64 and 32 bit.

This repository contains the dependencies for Google's [Tesseract OCR project](https://code.google.com/p/tesseract-ocr/) for tesseract 3.03 and leptonica 1.70, along with dependencies for everything but WEBP support.

### Build Instructions

1. Open VS 2013 Developer Command Prompt and change the directory to this repository.
2. Execute the following command ``msbuild build.proj``

The build libraries and headers will be copied to ``~\release`` when done.    
    
